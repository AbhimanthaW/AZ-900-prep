Deployment of Cloud Application (Key Considerations)
1. Uptime (Availability)
2. Scalability (Ability to handle demand)
3. Reliability

==**Uptime**==
ensuring maximum availability - regardless of disruptions/errors

**SLA (Service Level Agreement)**
formal agreement between cloud service provider and customer
	- that guarantees a certain level of uptime

document includes:
	- uptime %
	- downtime
	- credits entitled if SLA not met

Commercial Company (MS Azure) x Customer **OR**
  intra-org: IT dep. x business users

represented as a percentage %

100% uptime - difficult + costly
* no time to take server down for maintenance/upgrades
* duplicating each component - in case if 1 fails
* backup components must pick up service tasks with 0 interruption to customer

99% vs 99.9% uptime

| Downtime |  99%   |  99.9%   |
| :------: | :----: | :------: |
|   Week   | 1.6hrs |  10mins  |
|  Month   | 7.2hrs | 43.2mins |

==**Scalability**==
the ability to adjust resources to meet demand

consumption-based model:
- overpaying for resources ❌
- drop in demand
	- reduce resources --> reduce costs

**Vertical scaling**
* scaling up
* increasing capacity - adding more resources

eg: more processing: more CPU/RAM in VM

**Horizontal scaling**
* scaling out
* increasing # of machines/nodes to resource pool

eg: more processing: more VMs

==**Reliability**==
the ability of a system to recover from failures
[Microsoft Azure Well-Architected Framework]

* cloud - **decentralised** by nature (resources deployed around the world)
	* reliable/resilient

**==Predictability==**
1. performance
	* predicting the resources needed to deliver good performance
		* autoscaling: scale as per demand 
		* load balancing: redirect traffic/overload to less stressed areas
		* high availability
2. cost
	* forecasting the cost of the cloud spend
		* track/monitor resources real-time
		* apply data analytics
			* find patterns and trends
				* help better plan resource deployments
		* Total Cost of Ownership (TCO) or Pricing Calculator
			* estimate of potential cloud spend

[Microsoft Azure Well-Architected Framework]

==**Security**==
* IaaS: max control over security
* PaaS/SaaS:  patches and maintenance taken care of

==**Governance**==
* set templates
	* ensure deployed resources
		* meet corporate standards and government regulatory requirements
	* can update all your deployed resources to new standards as standards change
* cloud-based auditing
	* helps flag resources out of compliance with corporate standards
	* provides mitigation strategies
* depending on, operating model
	* software patches and updates may also automatically be applied

