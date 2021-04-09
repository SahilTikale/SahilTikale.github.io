# Bare-metal Marketplace at the Bottom of the Cloud
Phd Thesis Prospectus | Sahil Tikale, PhD Candidate, ECE, Boston University

## Overview

Today's clouds offer huge benefits in terms of on-demand elasticity, 
economies of scale and its pay-as-you-go model. Yet many organizations 
continue to host their clusters outside of cloud for security, 
price or performance reasons. Such organizations form a large section of 
the economy including financial companies, medical institutions 
and government agencies. Clusters are typically stood up with sufficient 
capacity to deal with peak demand; resulting in silos of under-utilized
hardware. This situation is common place not only within an individually 
owned data-center running multiple clusters but also across colocation 
facilities like the MGHPCC -- a 15 megawatt data-center that hosts 
infrastructure from 5 different universities. 

In the thesis we ask the question, What if we could easily and securely 
move infrastructure across these silos to match demand?
This would obviously increase utilization and reduce the cost. 
Moreover, as we will see, such a capability could enable an alternative 
model of cloud; an Open Cloud eXchange (OCX) where multiple 
organizations, freely cooperate and compete with each other for 
offering different hardware resources while customers can choose 
from numerous competing services instead of a single provider.

**The objective of this thesis is to build a system that allows mutually
non-trusting physically deployed services to efficiently share the physical
servers of a data center.** The approach proposed here is to build a 
system composed of a set of services each fulfilling a specific 
functionality. The scope of this work is limited to design and implementation of only the core set of functionalities critical
for sharing bare-metal servers between clusters across different deployment systems
and ownership. These functionalities are: 
1. A **Bare-metal Allocation and Isolation Service** to allow
different users to stand up clusters from a common pool of hardware. 
2. A **Diskless Rapid Provisioning Service** that allows deploying the 
cluster fast enough to be able to respond to rapid fluctuations in demand. 
3. A **Security Framework** that enables cluster owners to control trade-offs 
between security, price, and performance. 
4. A **Market based incentive system** that uses an economic model of 
a marketplace to ensure that resources are allocated to the cluster that 
needs it most. we have completed (1-3) and describe its architecture 
and results. Thereafter open questions regarding the (4) will be 
discussed followed by proposed timeline for the work pending towards 
completion of this thesis.

## Thesis proposal document
[Download](https://sahiltikale.github.io/Sahil_PHDproposal_V4.0.pdf)<br>

## Thesis Committee

* **Orran Krieger**, Professor, Boston University, (Advisor) [Homepage](https://www.bu.edu/eng/profile/orran-krieger/)
* **Larry Rudolph**, Professor, CSAIL MIT, (Co-Advisor) [Homepage](https://people.csail.mit.edu/rudolph/)
* **Peter Desnoyers**, Associate Professor, Northeastern University
* **David Starobinski**, Professor, Boston University
* **Manual Egele**,  Associate Professor, Boston University
