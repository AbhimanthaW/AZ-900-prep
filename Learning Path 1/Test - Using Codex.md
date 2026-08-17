## Round 1 — Core concepts

Answer without consulting your notes. Some questions require more than one answer.

**1. Single answer**

A company must retain some workloads in its own datacenter for regulatory reasons. During demand spikes, it wants those workloads to use resources from a public cloud.

Which cloud model should it use?

A. Public cloud  
B. Private cloud  
C. Hybrid cloud  
D. Multicloud

**2. Select two answers**

Which two are benefits of a consumption-based model?

A. Resources always require an upfront capital investment  
B. Resources can be added when demand increases  
C. Organizations pay for unused capacity indefinitely  
D. Resources can be removed when they are no longer needed  
E. Monthly costs are guaranteed to remain identical

**3. Single answer**

An application needs more processing power. An administrator increases the CPU and RAM of its existing virtual machine.

Which type of scaling is this?

A. Horizontal scaling  
B. Vertical scaling  
C. High availability  
D. Load balancing

**4. Yes or No**

For each statement, answer **Yes** or **No**.

|Statement|Answer|
|---|---|
|In IaaS, the cloud provider manages the physical host.|Yes/No|
|In PaaS, the customer manages the operating system.|Yes/No|
|In SaaS, the customer remains responsible for its accounts and data.|Yes/No|

**5. Matching**

Match each requirement with the most appropriate cloud service type. Each answer may be used once, more than once, or not at all.

Service types: **IaaS, PaaS, SaaS**

|Requirement|Service type|
|---|---|
|Migrate an existing server with minimal application changes|?|
|Develop an application without managing its operating system|?|
|Use a completed email application through a subscription|?|

**6. Single answer**

Which cloud benefit describes a system’s ability to recover from failures and continue functioning?

A. Scalability  
B. Predictability  
C. Reliability  
D. Governance

**7. Single answer**

Which statement best describes serverless computing?

A. The customer purchases physical servers but does not configure them  
B. The customer manages virtual machines while the provider manages networking  
C. The provider automatically manages infrastructure and allocates resources when code runs  
D. The application runs only on an organization’s private servers

**8. Select two answers**

Which two capabilities are examples of **management in the cloud**?

A. Managing resources through the Azure portal  
B. Replacing physical disks in a cloud provider’s datacenter  
C. Managing resources by using a command-line interface  
D. Installing security cameras in the provider’s datacenter  
E. Repairing the provider’s physical network equipment

**My Answers:**
1. C
2. B & D
3. B
4. Yes, No, Yes
5. IaaS, PaaS, SaaS
6. C
7. D
8. A & C

Round 1 score: **7/8 — 87.5%**.

You demonstrated strong command of cloud models, consumption pricing, scaling, shared responsibility, service types, reliability, and cloud management interfaces.

Your only error was Question 7:

- Your answer: **D**
- Correct answer: **C**

Serverless means the cloud provider manages the underlying servers, operating system, scaling, and resource allocation. You provide code or a workload that typically executes in response to events. “Serverless” does **not** mean no servers exist—it means you don’t provision or manage them.

This is a genuine notes gap: **serverless is included in Microsoft’s current AZ-900 cloud-concepts objectives but is absent from your notes**. [Current AZ-900 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900)

## Round 2 — Applied scenarios

**1. Single answer**

An organization requires a cloud environment dedicated exclusively to itself. It wants complete control over its resources and accepts responsibility for purchasing and maintaining the underlying hardware.

Which cloud model is this?

A. Public  
B. Private  
C. Hybrid  
D. Multicloud

**2. Yes or No**

|Statement|Answer|
|---|---|
|A hybrid cloud combines public-cloud and private-cloud environments.|Yes/No|
|A public cloud requires the customer to purchase the provider’s physical hardware.|Yes/No|
|Multicloud means using services from two or more public-cloud providers.|Yes/No|

**3. Select two answers**

Which two characteristics are associated with operational expenditure rather than capital expenditure?

A. A large upfront purchase of servers  
B. Recurring payment for services over time  
C. Purchasing a datacenter building  
D. Paying for computing resources as they are consumed  
E. Owning hardware that depreciates over several years

**4. Matching**

Match each description with the appropriate cloud benefit.

Benefits: **High availability, Reliability, Predictability**

|Description|Benefit|
|---|---|
|Estimating future cloud costs and expected application performance|?|
|Keeping a service accessible despite disruptions|?|
|Recovering from a component failure|?|

**5. Single answer**

A company uses standardized deployment templates and automatically identifies resources that violate corporate requirements.

Which cloud benefit does this primarily demonstrate?

A. Scalability  
B. Governance  
C. Reliability  
D. Consumption-based pricing

**6. Single answer**

A development team wants to deploy its application without managing the operating system, middleware, or development infrastructure. The team must still control its application and data.

Which service type should it choose?

A. IaaS  
B. PaaS  
C. SaaS  
D. On-premises

**7. Select two answers**

Which two statements correctly describe serverless computing?

A. The customer must patch the host operating system  
B. Resources can be allocated automatically when code executes  
C. The cloud provider manages the underlying infrastructure  
D. The customer must purchase enough servers for peak demand  
E. Serverless applications cannot respond to events

**8. Single answer**

A company migrates a legacy application to cloud virtual machines without redesigning the application. The company needs control of the operating system.

Which service type is most appropriate?

A. IaaS  
B. PaaS  
C. SaaS  
D. Serverless

**My Answers:**
1. B
2. Yes,No,Yes
3. B & D
4. Predictability,High availability,Reliability
5. B
6. B
7. B & C
8. IaaS

Your Round 2 responses are all correct: **8/8**.

## Blind assessment — 15 points

Target for progression: **12/15 or higher**, with no serious weakness in shared responsibility, service models, or cloud models.

**1. Select two answers — 2 points**

A company uses a SaaS customer-relationship management application.

Which two responsibilities remain with the company?

A. Replacing failed physical hosts  
B. Protecting its user accounts  
C. Maintaining the host operating system  
D. Managing the information entered into the application  
E. Securing the provider’s datacenter

**2. Single answer — 1 point**

A retailer adds four virtual machines to handle increased traffic instead of increasing the capacity of its existing virtual machine.

What type of scaling is this?

A. Vertical scaling  
B. Horizontal scaling  
C. Predictive scaling  
D. Manual availability

**3. Yes or No — 3 points**

Evaluate each statement independently.

|Statement|Answer|
|---|---|
|Moving from on-premises infrastructure to IaaS transfers responsibility for the guest operating system to the cloud provider.|Yes/No|
|The customer is responsible for physical datacenter security when using PaaS.|Yes/No|
|The customer retains some responsibilities even when using SaaS.|Yes/No|

**4. Single answer — 1 point**

A company uses Azure and another public-cloud provider. It does not operate a private cloud.

Which model does this describe?

A. Hybrid cloud  
B. Private cloud  
C. Multicloud  
D. Community cloud

**5. Single answer — 1 point**

An application automatically receives resources during peak demand and releases them after demand falls.

Which two benefits are most directly demonstrated?

A. Governance and security  
B. Scalability and cost efficiency  
C. Reliability and compliance  
D. Predictability and capital expenditure

**6. Matching — 3 points**

Match each workload to the most appropriate service model: **IaaS, PaaS, or SaaS**.

|Workload|Service model|
|---|---|
|A company needs complete control of a cloud-hosted operating system.|?|
|Developers need a managed application platform but control their code and data.|?|
|Employees need ready-to-use expense-management software.|?|

**7. Single answer — 1 point**

Which statement best distinguishes reliability from high availability?

A. Reliability concerns recovery from failure; high availability concerns continued accessibility  
B. Reliability concerns pricing; high availability concerns performance  
C. Reliability concerns scaling out; high availability concerns scaling up  
D. Reliability and high availability always mean exactly the same thing

**8. Single answer — 1 point**

A company automatically checks deployed resources against regulatory and organizational standards.

Which benefit is primarily demonstrated?

A. Predictability  
B. Governance  
C. Scalability  
D. Availability

**9. Single answer — 1 point**

A developer deploys code that executes when a message enters a queue. The provider provisions the required compute capacity and manages the operating system.

Which model best describes this workload?

A. Traditional on-premises computing  
B. IaaS  
C. Serverless computing  
D. Private-cloud virtualization

**10. Single answer — 1 point**

A business buys physical servers expected to last five years.

How should this purchase generally be categorized?

A. Operational expenditure  
B. Consumption-based expenditure  
C. Capital expenditure  
D. Serverless expenditure

**My Answers:**
1. B & D
2. B
3. No,No,Yes
4. C
5. B
6. IaaS,PaaS,SaaS
7. A
8. B
9. C
10. C

## Verdict

**Proceed to Learning Path 2.** You scored **15/15 (100%)** on the blind assessment, including every critical area:

- Shared responsibility
- Public, private, hybrid, and multicloud models
- CapEx, OpEx, and consumption pricing
- Scalability, availability, reliability, and governance
- IaaS, PaaS, and SaaS
- Serverless computing

This demonstrates competence in Microsoft’s current **Describe cloud concepts** domain, worth 25–30% of AZ-900. [Official AZ-900 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900)
 