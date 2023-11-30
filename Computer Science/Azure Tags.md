---
aliases:
  - Azure tags
  - resource tags
---
# What is the purpose of tags?
As your cloud usage grows, it's increasingly important to stay organized. A good organization strategy helps you understand your cloud usage and can help you manage costs.

One way to organize related resources is to place them in their own subscriptions. You can also use resource groups to manage related resources. Resource tags are another way to organize resources. Tags provide extra information, or metadata, about your resources. This metadata is useful for:

- [[Resource Management Tags|Resource management tags]] enable you to locate and act on resources that are associated with specific workloads, environments, business units, and owners.
- [[Cost Management and Optimization Tags|Cost management and optimization tags]] enable you to group resources so that you can report on costs, allocate internal cost centers, track budgets, and forecast estimated cost.
- [[Operations Management Tags|Operations management tags]] enable you to group resources according to how critical their availability is to your business. This grouping helps you formulate service-level agreements (SLAs). An SLA is an uptime or performance guarantee between you and your users.
- [[Security Tags|Security tags]] enable you to classify data by its security level, such as public or confidential.
- [[Governance and Regulatory Compliance Tags|Governance and regulatory compliance tags]] enable you to identify resources that align with governance or regulatory compliance requirements, such as ISO 27001. Tags can also be part of your standards enforcement efforts. For example, you might require that all resources be tagged with an owner or department name.
- [[Workload Optimization and Automation Tags|Workload optimization and automation tags]] can help you visualize all of the resources that participate in complex deployments. For example, you might tag a resource with its associated workload or application name and use software such as Azure DevOps to perform automated tasks on those resources.
## How do I manage them?
Adding and editing resource [[Tags|tags]] is easy and can be done from many different places. The main ways you can do this is through Windows PowerShell, the Azure CLI, Azure Resource Manager templates, the [[RESTful API]], or the Azure portal.