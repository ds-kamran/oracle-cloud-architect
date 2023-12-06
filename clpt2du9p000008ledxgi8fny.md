---
title: "Identity and Access Management"
datePublished: Wed Dec 06 2023 01:02:08 GMT+0000 (Coordinated Universal Time)
cuid: clpt2du9p000008ledxgi8fny
slug: identity-and-access-management
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1701824501107/d34f49b1-c0f5-4dc6-ae74-559f18bed79f.avif
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1701824521462/506447f1-9c73-4e4d-bb83-779ab0020a7a.avif
tags: oracle, oraclecloudinfrastructure

---

Identity Domain:

Create a Domain

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701792676568/46e004e3-1dfc-4210-97b8-c1e5f6543254.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701792790917/7978bef5-072a-4d15-a2e2-e1f866ded426.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701792801808/554c329c-4796-4a1b-a57f-1461e51f92fc.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701792854277/4c7b9982-b0ea-46dc-95de-cee99a8ad34a.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701792871013/0bb3a7e8-b964-4950-a774-4f5c4edade3e.png align="center")

AuthN:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701793196336/d4bf7015-b115-42c1-8cd6-8d19fce29537.png align="center")

User Created:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701793226810/cb413b3c-a970-490a-bc91-e759199d02ae.png align="center")

the user with email id will get an email to activate the account.

once the password created, login to the domain and you will get this page.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701793417242/b1e851d3-2d05-408a-91af-53f55c430961.png align="center")

Group creation:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701795012059/56a6f926-b334-45bc-aa3a-b42e5241a084.png align="center")

Policies:

Policies sit outside domain, One could generate a policy outside the domain

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701795249678/0787a408-010f-4455-a8f6-7a2d72aa2fd2.png align="center")

Compartment: It is a logical space to isolate your resources, the relation between compartment and resources is one to one, which means one compartment is associated with one resource.  
When you write policy you write compartments.  
It also acts as a filter to identify the resources.

You can make 6 levels of child compartments.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701823926590/56bd7bf8-c16e-429e-8d3a-b0847d1f7cdf.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701823877648/3c3d0d77-7b9c-446e-9d59-bcc90a3728ad.png align="center")

Compartment Quotas:

Service limit is set by oracle but CQ is set by admin.