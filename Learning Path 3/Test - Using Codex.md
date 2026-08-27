### Cost management — 8 points

**1. Single answer — 1 point**

A company is planning a new Azure deployment and wants to estimate its expected monthly cost before creating any resources.

Which tool should it use?

A. Azure Advisor  
B. Azure Pricing Calculator  
C. Azure Service Health  
D. Microsoft Purview

**2. Select two — 2 points**

Which two capabilities are provided by Azure Cost Management?

A. Analyze historical Azure expenditure  
B. Create budgets and cost alerts  
C. Repair failed physical servers  
D. Guarantee that service prices never change  
E. Enforce multifactor authentication

**3. Yes or No — 3 points**

Evaluate each statement independently.

|Statement|Answer|
|---|---|
|Tags can categorize resources for cost reporting.|Yes/No|
|Tags applied to a resource group are automatically inherited by all resources in it.|Yes/No|
|A tag by itself can prevent the deployment of a noncompliant resource.|Yes/No|

**4. Select two — 2 points**

Which two factors can directly affect the cost of an Azure resource?

A. Resource type and configuration  
B. The amount of the resource consumed  
C. The name assigned to its resource group  
D. The tenant’s display name  
E. The descriptive text stored in a tag

### Governance and compliance — 5 points

**5. Matching — 3 points**

Options: **Azure Policy, Resource locks, Microsoft Purview**

|Requirement|Service or feature|
|---|---|
|Assess and enforce organizational standards for Azure resources|?|
|Prevent accidental resource deletion or modification|?|
|Govern, discover, and classify data across an organization’s data estate|?|

**6. Select two — 2 points**

Which two statements correctly describe Azure resource locks?

A. A lock applied to a resource group can affect resources beneath it  
B. A protected resource cannot be deleted until the applicable delete lock is removed  
C. A read-only lock prevents users from reading the resource  
D. A resource lock encrypts the resource’s data  
E. Resource locks replace Azure RBAC permissions

### Management and deployment — 6 points

**7. Matching — 3 points**

Options: **Azure portal, Azure Cloud Shell, Azure Arc**

|Requirement|Tool or service|
|---|---|
|Manage Azure through a graphical browser interface|?|
|Use an authenticated browser-based Bash or PowerShell environment|?|
|Extend Azure management and governance to on-premises or multicloud resources|?|

**8. Single answer — 1 point**

A team wants to define an Azure deployment in a file so that it can create consistent environments repeatedly.

Which approach should it use?

A. Infrastructure as code  
B. Manual portal deployment  
C. Azure Service Health  
D. Application Insights

**9. Yes or No — 2 points**

|Statement|Answer|
|---|---|
|An ARM template is a declarative JSON file used to define Azure resources.|Yes/No|
|Infrastructure as code requires every resource to be configured manually in the Azure portal.|Yes/No|

### Monitoring — 6 points

**10. Matching — 3 points**

Options: **Azure Advisor, Azure Service Health, Azure Monitor**

|Requirement|Service|
|---|---|
|Receive personalized recommendations about cost, security, reliability, and performance|?|
|View service incidents and planned maintenance that may affect your Azure resources|?|
|Collect, analyze, and respond to telemetry from applications and infrastructure|?|

**11. Matching — 3 points**

Options: **Log Analytics, Azure Monitor alerts, Application Insights**

|Requirement|Feature|
|---|---|
|Query collected log data|?|
|Notify people or trigger actions when specified conditions occur|?|
|Monitor the performance, availability, and usage of a live application|?|

**Answers:**
- B
- A and B
- Yes Yes No
- A and B
- Policy, Resource Locks, Purview
- A and B
- Portal, Cloud Shell, Arc
- A
- Yes Yes
- Advisor, Service Health, Monitor
- Log Analytics, Monitor alerts, application insights

## Verdict: strong LP3 pass

**Score: 23/25 — 92%**

You exceeded the 80% progression threshold, and every domain was above 80%.

|Domain|Score|
|---|---|
|Cost management|7/8|
|Governance and compliance|5/5|
|Management and deployment|5/6|
|Monitoring|6/6|

This is especially encouraging because you completed it closed-book, on a phone, before creating notes. Your 0.78 confidence was slightly conservative; your immediate recall is closer to **0.85–0.9**.

## Corrections

**Question 3, statement 2: No**

Tags applied to a resource group are **not automatically inherited** by resources inside it.

- Resource-group tag: categorizes the group itself
- Resource tag: categorizes that specific resource
- Azure Policy can enforce or add required tags across resources

**Question 9, statement 2: No**

Infrastructure as code does not require manual portal configuration—it replaces repetitive manual configuration with declarative files and automated deployments.

For example, an ARM template describes the intended Azure resources and can be deployed repeatedly through tools such as Azure CLI, PowerShell, pipelines, or the portal.