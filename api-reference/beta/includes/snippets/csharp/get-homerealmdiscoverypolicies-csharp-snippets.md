---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var policy = await graphClient.Policies["homeRealmDiscoveryPolicies"]
	.Request()
	.GetAsync();

```