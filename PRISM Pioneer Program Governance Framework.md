# PRISM Pioneer Credential Governance Framework

Version: 1.1

## Table of Contents

### Document Information

This document is authored by Input Output Global’s Atala PRISM team.

### Abbreviations Used

| Abbreviation | Stands for                                                   |
| ------------ | ------------------------------------------------------------ |
| APPP         | Atala PRISM Pioneer Program                                  |
| GF           | Governance Framework                                         |
| IOG          | Input Output Global                                          |
| SSI          | Self-Sovereign Identity                                      |
| TR           | Trust Registry                                               |
| ToIP         | Trust Over IP                                                |
| VC           | Verifiable credential                                        |
| AP101        | Atala PRISM Pioneer Program<br />AP101: Foundations of Self-Sovereign Identity<br />The foundational principles and concepts of self-sovereign identity |
| AP102        | Atala PRISM Pioneer Program<br />AP102: Building with Atala PRISM<br />Building applications with Atala PRISM |
| AP103        | Atala PRISM Pioneer Program<br />AP103: Human-centric Design for Decentralized Applications<br />The foundation to design human-centric solutions for decentralized ecosystems |

### Terms of Use

This document intends to demonstrate an example of a Governance Framework as a learning tool for the Atala PRISM Pioneer Program. As part of this Governance Framework, IOG Atala PRISM tribe will be the issuer and verifier of credentials to Atala PRISM Pioneer Program participants. This document may be used by the Atala PRISM community as a reference implementation when drawing up their own ecosystem governance frameworks.

This document is made available under Creative Commons Attribution 4.0 International (CC-BY-4.0). Copyright © 2023 Input Output Global Inc. All rights reserved.

## 1. Introduction

### Overview

This document, the Atala PRISM Pioneer Program Credential Governance Framework, is an example of a simple implementation of a governance framework for credential issuance and verification. The sections included in this document will clarify how the Atala PRISM Pioneer Program Ecosystem functions, and how it is governed.

### Purpose

The purpose of the Atala PRISM Pioneer Program (APPP) Credential Governance Framework (GF) is to:

* Demonstrate implementing and using a simple governance framework for Pioneers that are working through the Atala PRISM Pioneer Program.
* Create an opportunity for Pioneers to experience operating within a governance framework.

### Context

Educating people about Atala PRISM presents an opportunity for the Atala tribe to demonstrate Self-Sovereign Identity (SSI) in practice, allowing the learners to experience digital identity innovation, and further enhancing the learning experience.

### Process

Input Output Global (IOG) will be the credential issuer for the AP101: Foundations of Self-Sovereign Identity (AP101) course. The credential received will be a prerequisite for the learner to enroll for the AP102: Building with Atala PRISM (AP102) course and the AP103: Human-centric Design for Decentralized Applications course (AP103).

![**Fig. 1** Trust Framework worksheet](/images/fig1.png)
**Fig 1.** Completed trust framework worksheet that helped conceptualize this governance framework

![**Fig. 2** Business Process Flow](/images/fig2.png)
**Fig 2.** Business process flow of credentials for this GF which allows or declines a learner enrollment into the AP102 and/or AP103 courses

### Website

The [Atala PRISM website](https://atalaprism.io/) provides more context about the Atala PRISM Pioneer Program. It will include information related to this GF that will explain the context, purpose, and process surrounding this GF.
The [ToIP Governance Metamodel Specification Companion Guide](https://trustoverip.org/wp-content/uploads/ToIP-Governance-Metamodel-Specification-Companion-Guide-V1.0-2022-12-21.pdf) version 1.0, 21 December 2021, was used to model this GF. A version of this GF and the associated trust registry will be available on GitHub and the Atala PRISM website. The website will also include links to translated copies of this GF as well as examples of other governance frameworks which learners MAY use as examples to construct their ecosystem GFs.

### Acknowledgements

Input Output Global (IOG) and the Atala PRISM tribe would like to thank the following people for their contributions to this GF:

* Contributors:
  * Darrell O’Donnell
  * Tony Rose
  * Lohan Spies
* Authors:
  * Anushka Soma-Patel
  * Peter Vielhaber

## 2. Terminology

Terminology is critically important for all aspects of the ToIP stack, especially in GFs, where terms must be accurately understood and interpreted by all stakeholders—from technical architects and developers to lawyers and policymakers.
This GF uses terminology specified in the [ToIP Governance Glossary](https://trustoverip.github.io/toip/glossary), the [European Self-Sovereign Identity Framework Lab Glossary](https://essif-lab.github.io/framework/docs/essifLab-glossary), and custom terminology used in this GF. The language used can be found within the Controlled Documents section in the [Glossary](https://docs.google.com/document/d/1v3W1so2JkCXXFZw3hxlzhcZbed76RTfeYhJ0DmoOUZg/edit#heading=h.kbnzchas32s5) section. The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY" and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).

## 3. Localization

The official language for this GF is currently English ([IETF BCP 47 language tag:](https://en.wikipedia.org/wiki/IETF_language_tag) en). Should a translation be required, any person or entity may create the translations. Submissions should include the contact details for creators, co-creators, and the trust community (if applicable) so that future updates can get translated. Only official translations approved by IOG will  get added to the official GF website.

## 4. Governing Authority

The governing authority for the Atala PRISM Pioneer Program Credential Governance Framework is IOG, specifically the Atala PRISM Tribe within IOG.

* Legal entity:
  * Entity name: Input Output Global Inc.
  * UEN: 202104148K
  * Address: Unit 201 2015 Ionosphere Street, Longmont, Colorado 80504
* Contact info:
  * Contact us on the [Atala PRISM website](https://atalaprism.io/#contact)

This GF will be available on the [Atala PRISM website](https://atalaprism.io/). The published GF will  clearly state the version history and what has changed so the trust registry (TR) will reflect the accurate version of the GF used within particular ecosystems.

## 5. Administering Authority

The administering authority will initially be the same entity as the governing authority.

The duties of the administering authority are listed below:

* Must create and maintain the Atala PRISM Pioneer Program
* Must ensure that this GF aligns with any changes to the Atala PRISM Pioneer Program that impact the rules set out in this GF

The administering authority must follow the following operational policies:

* Policy 5.1 The administering authority must ensure that a Course Completion Credential gets issued to learners for completing the AP101 course within the Atala PRISM Pioneer Program.
* Policy 5.2 The administering authority must ensure that the enrollment processes for the AP102 and AP103 courses verify the AP101 credential before allowing learners to enroll for these courses.
* Policy 5.3 The administering authority must ensure that a Course Completion Credential gets issued to learners who complete the AP102 course within the Atala PRISM Pioneer Program.
* Policy 5.4 The administering authority must ensure that a Course Completion Credential gets issued to learners who complete the AP103 course within the Atala PRISM Pioneer Program.

## 6. Scope

### Issuing of Verifiable Credentials for Courses

Course Completion Credentials will be issued to learners that enroll and complete courses within the PRISM Pioneer program.

### Credentials

The first credential, AP101, contains the following information:

**Credential Name**: Atala PRISM Pioneer Program - AP101: Foundations of Decentralized Identity

**Credential Type**: Certificate of Completion 

**Course name**: AP101: Foundations of Decentralized Identity

**Course Version**: 1.0

**Canvas Student ID**: 

**Canvas Course ID**:

**Student Name**:

**Student Email**:

**Credential Issue Date:**

The second credential, AP102, contains the following information. The course version will be based on the version of the PRISM SDK being taught in the course content.

**Credential Name**: Atala PRISM Pioneer Program - AP102: Building with Atala PRISM

**Credential Type**: Certificate of Completion

**Course name**: AP102: Building with Atala PRISM

**Course Version**: 1.4.1

**Canvas Student ID**: 

**Canvas Course ID**:

**Student Name**:

**Student Email**:

**Credential Issue Date:**

The third credential, AP103, contains the following information. The course version will be based on the version of the PRISM SDK being taught in the course content.

**Credential Name**: Atala PRISM Pioneer Program - AP103: Human-centric Design for Decentralized Applications

**Credential Type**: Certificate of Completion

**Course name**: AP103: Human-centric Design for Decentralized Applications

**Course Version**: 1.0

**Canvas Student ID**: 

**Canvas Course ID**:

**Student Name**:

**Student Email**:

**Credential Issue Date:**

### Holding Credentials

Atala PRISM Pioneers will be entitled to receive the AP101, AP102, and AP103 credentials issued to them upon completion of the respective course.

### Wallets

A holder may use any Atala PRISM compatible wallet to accept the VC issued from the Atala PRISM Pioneer Program.

### Verifying Credentials

When verifying the AP101 course credential, a verifier needs to trust the credential issued as confirmation that the holder completed the AP101 course and the verifier must confirm that IOG (specifically the Atala Tribe) has issued the VC. The course must have a unique identifier, and the version of the course must be reflected in the credential so that the verifier can assess whether the knowledge gained is up to date with the latest course material or not. The latest course version must be available in a publicly available course catalog so that the verifier can confirm that a learner (pioneer) completed the AP101 course before enrolling for the AP102 or AP103 courses.

### Data to be verified

Verifiers must be able to confirm that the Credential Name is "Atala PRISM Pioneer Program - AP101: Foundations of Self-Sovereign Identity", the Credential Type is a "Course Completion Credential," the course name is "AP101: Foundations of Self-Sovereign Identity, “ the Student ID and Course ID, the VC has not been revoked, and the version is the same as current course version on course catalog, before allowing the learner to enroll for the AP102 and/or AP103 courses. If the version is lower than the current version, the learner MUST get prompted to review the new content in the fundamentals course before enrolling for AP102 or AP103.

### Data storage

This section describes the data storage of each component of the GF solution. The wallet will hold learner info until the learner deletes their wallet. The issuer/verifier tool will keep data from the schema(s) above until the learner breaks the connection with the issuer/verifier.The GF, trust registry, and associated public website must be available while the credentials are still in use.

### Auditors

Auditors of the process will have to check and confirm that the above rules are executed and raise any discrepancies for the IOG Atala PRISM tribe to investigate and resolve.

### Key Artifacts governed by the GF

This GF governs the following artifacts:

* The website page containing information about this GF
* The trust registry related to this GF
* The course credential schema. Credential schemas will be the same for all credentials. The ‘credential name,’ ‘course name,’ ‘version,’ and ‘date’ will vary for the various courses

### Trust Decisions Enabled

This GF enables several trust decisions.
1. Whether a learner completed the AP101 course.
2. Did the learner completed the latest version of the AP101 course.
3. Did the learner completed the latest version of the AP102 course.
4. Did the learner completed the latest version of the AP103 course.




## 7. Objectives

This GF should achieve three concrete outcomes.

* The first outcome is for this GF to be included in the Atala PRISM Pioneer Program as an example to learn from
* The second outcome is for the issuer, holder, and verifier to view  and experience a governance framework in action 
* The third and last outcome is to ensure that the core Atala PRISM product develops the functionality required to implement this and other GFs

## 8. Principles

The following design principles MUST be aligned to deliver the outcomes of this GF in Section 7: Objectives:

| Principle                                | Rationale                                                    |
| ---------------------------------------- | ------------------------------------------------------------ |
| Simple                                   | The initial GF has a simple design to teach the concept to learners of the Atala PRISM Pioneer program. |
| Trusted                                  | The credential issued must have the ability to be verified with a high degree of trust. |
| Interoperable                            | Interoperability should be kept in mind for the medium to long term, not immediately or within the short term. |
| Extendable                               | The implementation of this GF has been designed to be extended, e.g., the ability to track versioning and implement new versions. In the medium to long term, the ability to refer to the other GFs that extend the use of the credentials issued in this GF shall be considered. |
| Make, learn, iterate                     | Start small. Experiment with different ways of doing things. Make prototypes to improve your understanding. Test and refine. |
| Make things open. It makes things better | Share your learning and work. Be transparent in your design decisions.<br/>Be accountable and have confidence in your solutions. |

## 9. Licensing

The purpose of this GF is to demonstrate its usage by the IOG Atala PRISM tribe as part of the Atal Prism Pioneer Program . Therefore, a responsible use policy and code of conduct are not necessary at this stage. An example **Responsible Use policy** is [here](https://computerexplorers.com/Responsible-use-Policy-Template.pdf), and more information about a **Code of conduct** is [here](https://en.wikipedia.org/wiki/Code_of_conduct). 

Actors:

* Issuer - IOG Atala Tribe
* Holder - Any pioneer who successfully completed AP101
* Verifier - IOG Atala Tribe, Student Reader

## 10. Revisions

The framework is a closed-loop trust framework and will periodically get reviewed. Revisions will get distributed to the Pioneer and Astros communities. To suggest an update to the GF, submit the change via the Contact form on the [Atala PRISM website](https://www.atalaprism.io). The Governing authority of this GF will manage revisions to this GF. Revision suggestions will be received, reviewed, and clarified with the requestor(s). An assessment will occur, and if agreed upon, it will be determined if consultation within the trust ecosystem is required. Once approved, updates to the GF will be made and communicated for adoption by the participants of the GF. Versioning of this document will be available on the site where this GF is published and within this document.

## 11. Extensions

This section applies to GFs that permit extension GFs (a common feature of some ecosystem GFs). At this time, this GF IS NOT extended for the sake of simplicity. In the event an extension is needed, the following considerations must occur:


* Must specify the requirements an extension GF must meet to be approved.
* Must specify the approval process by which a GF extension will get created.
* Must define requirements for registration, activation, and deactivation of an approved extension GF.
* Must define the requirements for notification of trust community members about activation or deactivation of an approved extension GF.


## 12. Schedule of Controlled Documents

All control documents are included in this GF section to keep all information related to this GF in one place, thereby implementing the principle of ‘simplicity.’

### 12.1 Glossary

The following list of terms from the [ToIP glossary](https://trustoverip.github.io/toip/glossary) are used in this document.

| Term                    | Definition                                                   |
| ----------------------- | ------------------------------------------------------------ |
| Administering Authority | The [party](https://essif-lab.github.io/framework/docs/essifLab-glossary#party) tasked with operating the management of a particular [governance framework](https://trustoverip.github.io/toip/glossary#governance-framework). The administering authority may or may not be the [governing authority](https://trustoverip.github.io/toip/glossary#governing-authority). For example, a government may be the governing authority for a governance framework administered by an NGO as the administering authority. |
| Governing Authority     | The [party](https://essif-lab.github.io/framework/docs/essifLab-glossary#party) responsible for governing a particular [governance framework](https://trustoverip.github.io/toip/glossary#governance-framework). The governing authority may or may not be the [administering authority](https://trustoverip.github.io/toip/glossary#administering-authority). For example, a government may be the governing authority for a governance framework administered by an NGO as the administering authority. |
| Governance Framework    | A set of business, legal, and technical [definitions], [policies], [specifications], and contracts by which the members of a [trust community](https://trustoverip.github.io/gswg/glossary#trust-community) agree to be governed in order to achieve their desired [objectives](https://trustoverip.github.io/essiflab/glossary#objective). ToIP-compliant governance frameworks follow the [ToIP governance metamodel](https://github.com/trustoverip/gswg/wiki/toip-governance-metamodel). |
| Self-sovereign identity | Self-Sovereign Identity (SSI) is a term that has many different interpretations, and that we use to refer to [concepts/ideas](https://trustoverip.github.io/toip/glossary#concept), architectures, processes and technologies that aim to support (autonomous) [parties](https://trustoverip.github.io/toip/glossary#party) as they negotiate and execute electronic [transactions](https://trustoverip.github.io/toip/glossary#transaction) with one another. <br />The dialogue about what Self-Sovereign Identity (SSI) really is — started in the blog "[The Path to Self-Sovereign Identity](http://www.lifewithalacrity.com/2016/04/the-path-to-self-soverereign-identity.html)" by Christopher Allen in 2016 — has not resulted in a consensus today. While some see the ten principles of SSI that Allen proposed as the definition of SSI, he formulated them as "a departure point to provoke a discussion about what's truly important". And it is obvious that what is important differs per [party](https://trustoverip.github.io/toip/glossary#party).<br />The perspective that the eSSIF-Lab framework takes is that of supporting (autonomous) [parties](https://trustoverip.github.io/toip/glossary#party) as they negotiate and execute electronic [(business) transactions](https://trustoverip.github.io/toip/glossary#transaction) with one another. So anything that helps - e.g. concepts/ideas, architectures, processes and technologies, will be covered by that term. |
| Trust Registry          | A repository which contains a machine-readable listing of approved [governed parties](https://trustoverip.github.io/toip/glossary.html#governed-party) deemed compliant by a [governing authority](https://trustoverip.github.io/toip/glossary.html#governing-authority) over its attributable criteria of its [governance framework](https://trustoverip.github.io/toip/glossary.html#governance-framework). |
| Verifiable Credentials  | A tamper-evident [credential](https://essif-lab.github.io/framework/docs/essifLab-glossary#credential) whose authorship by an [issuer](https://essif-lab.github.io/framework/docs/terms/issuer) can be cryptographically verified. Verifiable credentials can be used to build [verifiable presentations](https://trustoverip.github.io/toip/glossary.html#verifiable-presentation), which can also be cryptographically verified. The [claims](https://trustoverip.github.io/toip/glossary.html#claim) in a credential can be about different [subjects](https://trustoverip.github.io/toip/glossary.html#subject). |

The following terms are used within this GF and defined by [eSSIF](https://essif-lab.github.io/framework/docs/essifLab-glossary):

| Term     | Definition                                                   |
| -------- | ------------------------------------------------------------ |
| Holder   | the capability to handle [**presentation requests**](https://essif-lab.github.io/framework/docs/terms/presentation-request) from a [**peer agent**](https://essif-lab.github.io/framework/docs/terms/peer-agent), produce the requested data (a presentation) according to its [**principal**](https://essif-lab.github.io/framework/docs/terms/principal)'s [**holder-policy**](https://essif-lab.github.io/framework/docs/terms/holder-policy), and send that in response to the request. |
| Issuer   | the capability to construct [**credentials**](https://essif-lab.github.io/framework/docs/terms/credential) from data objects, according to the content of its [**principal**](https://essif-lab.github.io/framework/docs/terms/principal)'s [**issuer**](https://essif-lab.github.io/framework/docs/terms/issuer)-Policy (specifically regarding the way in which the [**credential**](https://essif-lab.github.io/framework/docs/terms/credential) is to be digitally signed), and pass it to the [**wallet**](https://essif-lab.github.io/framework/docs/terms/wallet)-component of its [**principal**](https://essif-lab.github.io/framework/docs/terms/principal) allowing it to be issued. |
| Verifier | the capability to request [**peer agents**](https://essif-lab.github.io/framework/docs/terms/peer-agent) to present (provide) data from credentials (of a specified kind, issued by specified [**parties**](https://essif-lab.github.io/framework/docs/terms/party)), and to verify such responses (check structure, signatures, dates), according to its [**principal**](https://essif-lab.github.io/framework/docs/terms/principal)'s [**verifier policy**](https://essif-lab.github.io/framework/docs/terms/verifier-policy). |

The following terms are used within and are specific to this GF:

| Term                               | Definition                                                   |
| ---------------------------------- | ------------------------------------------------------------ |
| Atala PRISM Tribe                  | The Atala PRISM tribe refers to the team building the Atala PRISM Product. |
| Course Completion Credentials | Refers to a verifiable credential for completing a course within the Atala PRISM Pioneer Program. This is a certificate of completion and not competence and knowledge is tested using 5-10 multiple choice questions per section of the course. |
| Compatible wallet                  | A compatible wallet is one that is used by a holder or issuer that enables the issuing, storing and verifying of Atala PRISM DIDs and credentials. |
| Issuer Tool                        | The application/tool a party uses to issue VCs.              |
| Learner                            | People taking the Atala PRISM Pioneer Program courses.       |
| Trust Community                    | The parties that participate in a GF to enable a trusted ecosystem amongst parties that issue, hold and verify VCs. |
| Veriifable Presentation            | The schema/set of data requested from a holder by a verifier. |

### 12.2 Risk Assessment

A risk assessment will occur at least six months after the GF implementation.
The Risk Assessment template, provided by ToIP, can be found [here](https://trustoverip.org/permalink/ToIP-Risk-Assessment-Worksheet-Template-V1.0-2021-08-24.xlsx). 

### 12.3 Governance and Business Requirements

The governance and business requirements are outlined in the scope section (section 6). The basic requirements are as follows:

* IOG is the sole issuer
* IOG and Student Reader are the verifiers
* IOG will use Cardano Testnet to anchor IOG DID to issue credentials
* Holders will use a PRISM compatible wallet to receive credentials
* AP101 is a prerequisite credential to enroll for AP102 and AP103 courses


### 12.4 Technical Requirements

The following technical requirements will enable the implementation of this GF. Refer to the conceptual diagram below.

* Atala PRISM-compatible holder wallet to hold credentials
* Issuing mechanism/tool to issue credentials
* A verifier tool is needed to verify that a learner completed the latest version of the AP101 course
* A public webpage for the trust registry and the GF is required to demonstrate how credential verification works with the GF and TR


![**Fig. 12** Technical requirements](/images/fig12.png)
**Fig. 12** Technical requirements

### 12.5 Information Trust Requirements

The American Institute of Certified Public Accountants (AICPA) Assurance Services Executive Committee (ASEC) has provided requirements in five categories of trust services. The Committee on the Sponsoring Organizations of the Treadway Commission (COSO) Guidance on Internal Control provides guidance for implementing internal controls to address the five categories of trust services. To provide a learning opportunity for PRISM Pioneers, baseline requirements for governed parties are as follows:

* Information security
  * Holders and trust community members of this GF agree to secure the information that they receive and generate.
* Information availability
  * Holders and trust community members of this GF use the tools supplied at their own discretion.
* Information processing integrity
  * Information that is processed by issuers and verifiers is always supplied by the holder, unless this information is generated by the issuer or service provider.
* Information confidentiality
  * Trust community members of this GF agree to keep the information they receive confidential.
* Information privacy
  * Trust community members of this GF agree to respect the privacy of information of holders and not use information collected for purposes other than that which is approved by the holder.

## Revision History

| Version | Date Approved | Revisions                                   |
| ------- | ------------- | ------------------------------------------- |
| 0.1     | 2 Sept 2022   | Initial draft to be used as a learning tool |
| 1.0     | 17 March 2023 | Updated to align with implementation of GF  |
|         |               |                                             |
