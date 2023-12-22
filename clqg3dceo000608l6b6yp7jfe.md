---
title: "OCI Notes"
datePublished: Fri Dec 22 2023 03:48:27 GMT+0000 (Coordinated Universal Time)
cuid: clqg3dceo000608l6b6yp7jfe
slug: oci-notes

---

IAM

# Compute:

1) Generate a keypair using cloudshell.

appsdba\_ka@cloudshell:~ (ca-toronto-1)$ ssh-keygen

Generating public/private rsa key pair.

Enter file in which to save the key (/home/appsdba\_ka/.ssh/id\_rsa):

Created directory '/home/appsdba\_ka/.ssh'.

Enter passphrase (empty for no passphrase):

Enter same passphrase again:

Your identification has been saved in /home/appsdba\_ka/.ssh/id\_rsa.

Your public key has been saved in /home/appsdba\_ka/.ssh/id\_[rsa.pub](http://rsa.pub).

The key fingerprint is: SHA256:Qtgkb4bZs52aEZlvJ7OLTAGNuq3wj/1ZQ1lreLM9Cqs

appsdba\_ka@bb90036a4766 The key's randomart image is: +---\[RSA 2048\]----+ | . . | | % o | | *& . | | . =* \= . | | . = S \* | | o O B + | |. . . + = . o | | o + o + = . . | | +.o.E.o . | +----\[SHA256\]-----+

appsdba\_ka@cloudshell:~ (ca-toronto-1)$ cd .ssh

appsdba\_ka@cloudshell:.ssh (ca-toronto-1)$

ls id\_rsa id\_[rsa.pub](http://rsa.pub)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1703210168145/62b15b9d-4320-49b7-a41d-418fe4f722d3.png align="center")

Types of compute instance:

Preemptible instance, Capacity reservation, Dedicated VM Host, Burstable instance

Preemptible instances behave the same as regular compute instances, but the capacity is reclaimed when it's needed elsewhere, and the instances are terminated. If your workloads are fault-tolerant and can withstand interruptions, then preemptible instances can reduce your costs.

GPU Shapes are designed for hardware-accelerated workloads. GPU Shapes include Intel or AMD CPUs and NVIDIA graphics processors.

Dedicated virtual machine hosts let you run Oracle Cloud Infrastructure Compute virtual machine (VM) instances on dedicated servers that are single tenant and not shared with other customers. Use dedicated virtual machine hosts to meet compliance and regulatory requirements for isolation that prevents you from using shared infrastructure.