---
aliases:
  - pricing calculator
---
The pricing calculator is designed to give you an estimated cost for provisioning resources in [[Microsoft Azure|Azure]]. You can get an estimate for individual resources, build out a solution, or use an example scenario to see an estimate of the [[Microsoft Azure|Azure]] spending. The pricing calculator’s focus is on the cost of provisioned resources in [[Microsoft Azure|Azure]]. With the pricing calculator, you can estimate the cost of any provisioned resources, including compute, storage, and associated network costs. You can even account for different storage options like storage type, access tier, and redundancy.
>[!info] Note
>The pricing calculator  is for information purposes only. The prices are only an estimate. Nothing is provisioned when you add resources to the pricing calculator, and you won't be charged for any services you select.
# Factors that can affect pricing on [[Microsoft Azure|Azure Cloud]]
---
## Resource Type
A number of factors influence the cost of Azure resources. The type of resources, the settings for the resource, and the Azure region will all have an impact on how much a resource costs. When you provision an Azure resource, Azure creates metered instances for that resource. The meters track the resources' usage and generate a usage record that is used to calculate your bill.
## Consumption
Pay-as-you-go is a consistent theme throughout [[Microsoft Azure|Azure Cloud Services]] , and that’s the cloud payment model where you pay for the resources that you use during a billing cycle. If you use more compute this cycle, you pay more. If you use less in the current cycle, you pay less. It’s a straight forward pricing mechanism that allows for maximum flexibility.

However, [[Microsoft Azure|Azure]] also offers the ability to commit to using a set amount of cloud resources in advance and receiving discounts on those “reserved” resources. Many services, including databases, compute, and storage all provide the option to commit to a level of use and receive a discount, in some cases up to 72 percent.

When you reserve capacity, you’re committing to using and paying for a certain amount of [[Microsoft Azure|Azure]] resources during a given period (typically one or three years). With the back-up of pay-as-you-go, if you see a sudden surge in demand that eclipses what you’ve pre-reserved, you just pay for the additional resources in excess of your reservation. This model allows you to recognize significant savings on reliable, consistent workloads while also having the flexibility to rapidly increase your cloud footprint as the need arises.
## Maintenance
The flexibility of the cloud makes it possible to rapidly adjust resources based on demand. Using resource groups can help keep all of your resources organized. In order to control costs, it’s important to maintain your cloud environment. For example, every time you provision a [[Virtual Machine|VM]], additional resources such as storage and networking are also provisioned. If you deprovision the [[Virtual Machine|VM]], those additional resources may not deprovision at the same time, either intentionally or unintentionally. By keeping an eye on your resources and making sure you’re not keeping around resources that are no longer needed, you can help control cloud costs.
## Geography
When you provision most resources in [[Microsoft Azure|Azure]], you need to define a region where the resource deploys. [[Microsoft Azure|Azure]] infrastructure is distributed globally, which enables you to deploy your services centrally or closest to your customers, or something in between. With this global deployment comes global pricing differences. The cost of power, labor, taxes, and fees vary depending on the location. Due to these variations, Azure resources can differ in costs to deploy depending on the region. Network traffic is also impacted based on geography. For example, it’s less expensive to move information within Europe than to move information from Europe to Asia or South America.
## Network Traffic 
Billing zones are a factor in determining the cost of some [[Microsoft Azure|Azure]] services. Bandwidth refers to data moving in and out of Azure [[Data Center|data-center]]s. Some inbound data transfers (data going into Azure [[Data Center|data-center]]s) are free. For outbound data transfers (data leaving Azure [[Data Center|data-center]]s), data transfer pricing is based on zones.
## Subscription Type
Some [[Microsoft Azure|Azure]] subscription types also include usage allowances, which affect costs. For example, an [[Microsoft Azure|Azure]] free trial subscription provides access to a number of [[Microsoft Azure|Azure]] products that are free for 12 months. It also includes credit to spend within your first 30 days of sign-up. You'll get access to more than 25 products that are always free (based on resource and region availability).
## 