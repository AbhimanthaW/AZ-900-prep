## Round 1 — Broad diagnostic

**20 points total.** For “select” questions, choose exactly the stated number.

### 1. Single answer — 1 point

Which Azure component is a physical location containing servers arranged in racks with dedicated power, cooling, and networking?

A. Region  
B. Datacenter  
C. Resource group  
D. Availability zone

### 2. Matching — 3 points

Match each requirement with the most appropriate scope.

Scopes: **Management group, Subscription, Resource group**

|Requirement|Scope|
|---|---|
|Apply governance across several subscriptions|?|
|Establish a billing and access-control boundary|?|
|Organize related resources for a single application|?|

### 3. Select two — 2 points

Which two statements correctly describe Availability Zones?

A. They are separate physical locations within an Azure region  
B. They connect separate Microsoft Entra tenants  
C. They provide isolation from localized datacenter failures  
D. Every Azure service automatically supports them  
E. They are used primarily as billing boundaries

### 4. Matching — 3 points

Match each requirement with the best compute option.

Options: **Azure virtual machine, Azure Container Instances, Azure Functions**

|Requirement|Compute option|
|---|---|
|Complete control of the guest operating system|?|
|Run a container without managing a virtual machine|?|
|Execute event-driven code without managing infrastructure|?|

### 5. Single answer — 1 point

A company must create and manage a group of identical, load-balanced virtual machines that can automatically add instances as demand increases.

Which service should it use?

A. Availability sets  
B. Virtual Machine Scale Sets  
C. Azure Virtual Desktop  
D. Azure Functions

### 6. Matching — 3 points

Match each requirement with the most appropriate networking option.

Options: **Point-to-site VPN, Site-to-site VPN, ExpressRoute**

|Requirement|Networking option|
|---|---|
|Connect one remote employee securely to an Azure virtual network|?|
|Connect an entire on-premises network over an encrypted internet connection|?|
|Establish a dedicated private connection that avoids the public internet|?|

### 7. Yes or No — 2 points

Evaluate each statement independently.

|Statement|Answer|
|---|---|
|VNet peering allows two virtual networks to communicate over Microsoft’s backbone.|Yes/No|
|A private endpoint assigns a publicly routable IP address to an Azure service.|Yes/No|

### 8. Matching — 3 points

Match each workload with the most appropriate Azure Storage service.

Options: **Blob storage, Azure Files, Queue storage**

|Workload|Storage service|
|---|---|
|Store images and video as unstructured objects|?|
|Provide managed file shares using SMB|?|
|Store messages for asynchronous processing|?|

### 9. Single answer — 1 point

A company must retain infrequently accessed data at the lowest storage cost. Waiting several hours to retrieve it is acceptable.

Which access tier should it use?

A. Hot  
B. Cool  
C. Cold  
D. Archive

### 10. Single answer — 1 point

An organization must transfer hundreds of terabytes to Azure, but its network connection is too slow for an online transfer.

Which service should it use?

A. Azure Migrate  
B. Azure File Sync  
C. Azure Data Box  
D. Azure Storage Explorer

### 11. Select two — 2 points

A legacy application requires LDAP, Kerberos authentication, traditional domain join, and Group Policy. The organization does not want to manage domain controllers.

Which two statements are correct?

A. Microsoft Entra Domain Services is appropriate  
B. Microsoft Entra ID alone supplies traditional Group Policy  
C. Microsoft manages the domain controllers  
D. Azure RBAC replaces Kerberos authentication  
E. Azure VPN Gateway provides the directory service

### 12. Matching — 3 points

Match each description with the correct security concept.

Options: **Conditional Access, Azure RBAC, Microsoft Defender for Cloud**

|Description|Security concept|
|---|---|
|Require MFA when sign-in risk or location meets specified conditions|?|
|Grant a user permission to manage resources at a particular scope|?|
|Assess security posture and recommend improvements across cloud resources|?|

**Answers:**
- B
- Subscription, Management group, Resource group
- A, C
- Azure virtual machine,Azure Container Instances,Azure Functions
- B
- Point-to-site VPN, Site-to-site VPN, ExpressRoute
- Yes, No
- Blob storage, Azure Files, Queue storage
- D
- Azure Migrate
- B , E
- Conditional Access, Azure RBAC, Microsoft Defender for Cloud

## Round 1 result: 20/25 — 80%

You reached the progression threshold exactly, but you are **not yet securely ready to leave LP2 behind**. Your 0.65 confidence is fairly well calibrated: your broad understanding is good, but two foundational distinctions need reinforcement.

I incorrectly labelled the round as 20 points; the individual question values totalled **25**. The score above uses the actual 25-point total.

|Domain|Score|Assessment|
|---|---|---|
|Architecture|4/6|Needs reinforcement|
|Compute|4/4|Strong|
|Networking|5/5|Strong|
|Storage|4/5|Good, with a migration-tool gap|
|Identity and security|3/5|Minimum acceptable boundary|
|**Overall**|**20/25**|**80%**|

## Corrections

**Question 2 — 1/3**

The correct order was:

1. **Management group** — governance across multiple subscriptions
2. **Subscription** — billing and access-control boundary
3. **Resource group** — organize related resources

Think of the hierarchy as:

`Management group → Subscription → Resource group → Resource`

A management group is not normally the billing boundary. It exists primarily to apply governance and access consistently across descendant subscriptions.

**Question 10 — 0/1**

Correct answer: **Azure Data Box**

- **Azure Data Box:** physically transfers very large datasets when network transfer is impractical.
- **Azure Migrate:** discovers, assesses, and helps migrate workloads such as servers, databases, and applications.

The clue was not merely “migration.” It was **hundreds of terabytes plus insufficient bandwidth**.

**Question 11 — 0/2**

Correct answers: **A and C**

- **Microsoft Entra Domain Services** provides managed LDAP, Kerberos/NTLM, domain join, and Group Policy.
- **Microsoft manages the domain controllers.**

Microsoft Entra ID alone does not supply traditional Group Policy, and Azure VPN Gateway is a networking service—not a directory service.

## Round 2 — Targeted verification

This round retests the weak areas and covers important objectives that Round 1 did not sample. **20 points total.** Target: **16/20**, with Questions 1–3 answered correctly.

### 1. Matching — 3 points

Match each Azure object with its description.

Options: **Management group, Subscription, Resource group**

|Description|Object|
|---|---|
|Applies governance across multiple subscriptions|?|
|Provides a billing and access-management boundary|?|
|Logically contains related Azure resources|?|

### 2. Single answer — 1 point

A company wants to discover its on-premises servers, assess their Azure readiness, estimate suitable Azure sizes, and coordinate their migration.

Which service should it use?

A. Azure Data Box  
B. Azure Migrate  
C. Azure File Sync  
D. AzCopy

### 3. Select two — 2 points

A legacy application requires Kerberos authentication, LDAP, domain join, and Group Policy. The company does not want to deploy or patch domain controllers.

Which two statements are correct?

A. Microsoft Entra Domain Services is appropriate  
B. Microsoft Entra ID alone provides traditional Group Policy  
C. Microsoft manages the domain controllers  
D. Azure RBAC supplies Kerberos authentication  
E. ExpressRoute supplies the required directory features

### 4. Matching — 3 points

Options: **AzCopy, Azure Storage Explorer, Azure File Sync**

|Requirement|Tool|
|---|---|
|Automate high-performance storage transfers from a command line|?|
|Manage Azure Storage through a graphical desktop application|?|
|Maintain a cached, synchronized Azure Files share on Windows Server|?|

### 5. Single answer — 1 point

A storage account must replicate data across multiple Availability Zones in its primary region and also to a secondary geographic region.

Which redundancy option meets the requirement?

A. LRS  
B. ZRS  
C. GRS  
D. GZRS

### 6. Matching — 3 points

Options: **SSO, MFA, Passwordless authentication**

|Description|Method|
|---|---|
|Authenticate once and access several trusted applications|?|
|Require verification from more than one factor category|?|
|Authenticate using a trusted device with a PIN or biometric instead of a password|?|

### 7. Single answer — 1 point

Which Azure construct consists of physically separate locations within the same region, each with independent power, cooling, and networking?

A. Region pair  
B. Availability zone  
C. Resource group  
D. Management group

### 8. Single answer — 1 point

An administrator must allow a team to manage virtual machines in one resource group without granting access elsewhere.

What should the administrator use?

A. Azure RBAC assignment scoped to the resource group  
B. A new Availability Zone  
C. Azure DNS  
D. A storage access tier

### 9. Select two — 2 points

Which two are Zero Trust principles?

A. Trust requests originating from the corporate network  
B. Verify explicitly  
C. Grant broad permanent access to reduce administration  
D. Use least-privilege access  
E. Assume authenticated users cannot be compromised

### 10. Matching — 3 points

Match each protection with its defense-in-depth layer.

Options: **Perimeter, Compute, Data**

|Protection|Layer|
|---|---|
|DDoS protection and perimeter firewalls|?|
|Operating-system patching and endpoint protection|?|
|Encryption and controls protecting stored information|?|

**Answers:**
- Management Group, Subscription, Resource Group
- B
- A and D
- AzCopy, Azure Storage Explorer, Azure File Sync
- D
- SSO, MFA, Passwordless authentication
- A
- A
- B and D
- Perimeter, Compute, Data

