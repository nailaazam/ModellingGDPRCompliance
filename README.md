# ModellingGDPRCompliance
Modelling Technique for GDPR-compliance: Toward a Comprehensive Solution

we present a
novel comprehensive solution for developing a threat modelling
technique to address threats of non-compliance and mitigate them
by taking GDPR requirements as the baseline and combining
them with the existing security and privacy modelling techniques
(i.e., STRIDE and LINDDUN, respectively). For this purpose, we
propose a new data flow diagram integrated with the GDPR
principles, develop a knowledge base for the non-compliance
threats, and leverage an inference engine for reasoning the GDPR
non-compliance threats over the knowledge base. Finally, we
demonstrate our solution for threats of non-compliance with
legal basis and accountability in a telehealth system to show
the feasibility and effectiveness of the proposed solution.

The novel DFD is illustrated below:

![DFD-GDPRcompliance](https://user-images.githubusercontent.com/132493093/236053887-93ce97b7-9fcc-450b-b0ab-c36fe2a7c5e4.png)

#How to do Threat Modeling?

Microsoft provides a Threat Modeling Tool (MS TMT) that allows not only to prepare a model from given templates but it also allows new templates to be created for different systems. 

We have prepared a new template specifically for Telehealth Services System modeled the non-compliance threats. The noncompliance-template allows us to import GDPR entities such as DS, DP, DC, SA, etc into the model and use non-compliance specific trust boundary.

The [non-compliance template](https://github.com/nailaazam/ModellingGDPRCompliance/blob/main/nonCompliant.tb7) and its [Threat Report](https://github.com/nailaazam/ModellingGDPRCompliance/blob/main/Threat%20Modeling%20Report-noncompliance.html) is available in this repo.

To use the non-compliance-template and the non-compliance threat model you need to download [Microsoft Threat Modeling Tool](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool).
