# IT Security Guideline for Medical Devices

## **A) Meta information**

### **1. Guideline objectives**

The objective of this guideline is to provide medical device manufacturers and notified bodies with instructions and a specific checklist in order to:

- Explain what notified bodies&#39; expectations are
- Encourage the step-by-step implementation of IT security for medical devices
- Compensate for the absence of a harmonized standard (until there is one) as well as possible

Unlike a lot of other guidelines on IT security, this guideline only relates to medical devices and focus on patient safety.

This guideline are **not** intended to act as a textbook or guidelines for implementing IT security. Instead, they are intended as a guide for reviewing IT security.

The annex details gives the considerations that led to the creation of this guideline.

### **2. Scope of application**

These guidelines are intended for manufacturers of medical devices, especially networkable medical devices, and their service providers, as well as for people and organizations who have to evaluate the IT security of these devices.

It focuses on the IT security of the medical devices, not the organization&#39;s IT security.

The guidelines are also suitable for assessing the technical measures required for data protection. Nevertheless, the focus is on patient safety, not the confidentiality of data.

### **3. Notes on use**

#### **a) Structure of the guidelines**

These guidelines are based on the idea that IT security is based on three fundamental pillars:

1. Process requirements
2. Product requirements
3. Documented evidence that these process and product requirements have been met

The structure of these guidelines is based on these pillars: In section B) it starts off with the general requirements, in section C) it establishes the process requirements (including documentation), and in section D) it establishes the product requirements (including documentation). Within these &quot;main sections&quot;, the requirements are structured along software life cycle process lines:

1. **Process requirements**
   1. ***Requirements for the development process***
      1. Intended purpose and stakeholder requirements
      2. System and software requirements
      3. System and software architecture
      4. Implementation and development of the software
      5. Evaluation of software units
      6. System and software tests
      7. Product release
   2. ***Requirements for the post-development phase***
      1. Production, distribution, installation
      2. Post-market surveillance
      3. Incident response plan
2. **Product requirements**
   1. Preliminary remarks and general requirements
   2. System requirements
   3. System and software architecture
   4. Support materials

The risk management requirements are woven into the requirements throughout the product life cycle.

#### **b) Applicable sections and requirements**

Manufacturers should first use the guidelines to check the completeness of the specification's documents (process and work instructions, checklists, etc.). For this, they should look at sections B) to D).

Subsequently, they and the people who evaluate IT security on a product-specific basis (including internal and external auditors and technical documentation reviewers) should use the guidelines to evaluate IT security for the product. In this case, they can use sections C) and D) of these guidelines as a checklist.

These guidelines contain requirements that do not apply to all products. Manufacturers must justify the exceptions that are not obvious.

#### **c) Prioritization**

If the manufacturers are not able to meet all the requirements of these guidelines from the outset, the requirements should be met in the order of their priority (from level 0 to level 3) as far as possible and where reasonable. These levels are described in the annex.

Acceptance of the security level achieved must be evaluated.

#### **d) Comments**

These guidelines contain &quot;comments&quot; on most of the requirements. These comments include justifications, references, comments and, above all, tips for auditors and reviewers.

With regard to the further development of the guidelines, there is a trend towards the implementation of the ISO 2700x series of standards. This is due to detected attempts by professional attackers, who in the future will introduce malware into medical devices via the manufacturing organization&#39;s IT infrastructure, via means of communication, configuration tools, software tools and libraries. Additional security measures will therefore have to be initiated &quot;earlier&quot; in the development process, which will bring IT security issues in the company to the fore.

#### **e) Liability**

These guidelines are neither a legal requirement nor a harmonized standard. Accordingly, they do not differentiate between normative and informative elements.

Instead, the guidelines bring together best practices to describe the legally mandated &quot;state-of-the-art&quot; as well as possible.

### **4. Authors and rights of use**

These guidelines were prepared by the following authors:

- Andreas Purde ([TÜV SÜD](https://www.tuev-sued.de/))
- Olaf Teichert ([TÜV SÜD](https://www.tuev-sued.de/))
- Prof. Dr. Christian Johner ([Johner Institute](https://www.johner-institut.de))
- Dr. Georg Heidenreich ([Siemens Healthcare GmbH](https://www.healthcare.siemens.com/)) 

These guidelines are published under a [BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/) [Creative Commons license](https://creativecommons.org/licenses/?lang=en). This requires the naming of the authors (&quot;TÜV SÜD, Johner Institute and Dr. Georg Heidenreich&quot;) and allows third parties to build on this work, e.g. to improve, but only for non-commercial purposes.

The license permits commercial use of the product for consulting purposes, including audits. However, it prohibits the commercial use of this work itself, either unchanged or amended, e.g. as brochure for sales purposes.

### **5. Document control, document identification**

This document is managed via the version control system Git or the platform GitHub. Only the documents named in this repository are valid.

The version history including the respective authors can be found in the document history.

The released versions are identified as such in the repository using a tag. Versions without a tag are documents in the draft stage.

## **B) General requirements**

### **1. Process**

Manufacturers should cover all the aspects mentioned below either in the process instructions or in the corresponding plans in order to ensure that IT security is systematically ensured. Usually the following process instructions and plans are affected:

- Development
- Risk management
- Verification and validation (if not part of development)
- Post-market surveillance and vigilance
- Service, installation, decommissioning
- Customer communication
- Management evaluation (ISO 13485:2016 requires &quot;applicable new or revised regulatory requirements&quot; to be taken into account).

If the manufacturer uses outsourced processes, the requirements apply accordingly. For example, a (software) development service provider would have to observe the sections of these guidelines that are relevant for it.

### **2. Expertise**

Manufacturers must ensure and demonstrate that they have sufficient expertise to ensure IT security in line with the state of the art. This evidence is often most easily obtained through internal or external training.

In this way, manufacturers can also access the expertise of external resources.

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| B.2.1 | The manufacturer has created a list of all roles that are directly or indirectly involved with IT security.[^B2-01] | 1 |   |
| B.2.2 | The manufacturer has provided evidence of the IT-security expertise for each role.[^B2-02] | 1 |   |
| B.2.3 | The manufacturer has appropriate records of education, training and skills that lead to the conclusion that the people in question actually have this expertise. | 1 |   |
| B.2.4 | The (software) development plans define the (additional or deviating) expertise on a product-specific basis. | 2 | ISO 13485:2016 requirement |

[^B2-01]: Examples are: developers, testers, regulatory affairs and quality managers, employees in service and support, product managers, medical product consultants

[^B2-02]: competences (to understand, to be able to) and not primarily topics should be mentioned

### **3. Documentation**

The manufacturer should be able to provide evidence that it has complied with the relevant requirements of these guidelines. There are no specific requirements for the documentation and &quot;objective evidence&quot;.

In Europe (unlike in the USA), there is also no obligation to create a specific document on IT security. Instead, manufacturers can integrate these aspects into existing documents, such as the QM system specification documents and the technical documentation (e.g. software files, risk management files).

## **C) Process requirements**

### **1. Product development requirements**

#### **a) Intended purpose and stakeholder requirements**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | :-: | --- |
| C.1.a.1 | The manufacturer has identified all neighboring systems (e.g. medical devices, IT systems) that may be connected to the product. | 0 |   |
| C.1.a.2 | The manufacturer has created a list of roles (people, neighboring systems) that may interact with the product. | 0 | Ask for the list of roles. |
| C.1.a.3 | The manufacturer has identified all markets and all the regulatory requirements that are relevant in these markets. | 0 | Ask for the list of IT security regulatory requirements. |
| C.1.a.4 | The manufacturer has identified the intended primary and secondary users with their IT expertise.[^C1a-01] | 1 |   |
| C.1.a.5 | The manufacturer has defined the intended use environment.[^C1a-02] | 1 |   |
| C.1.a.6 | The manufacturer has analyzed the risks (hazards) that result if the system is not used by specified users or in the specified use environment.[^C1a-03] | 1 |   |
| C.1.a.7 | The manufacturer has described in the risk management documentation what the IT security threats are and what the consequences would be for patients, users and third parties. | 1 |   |
| C.1.a.8 | The manufacturer has traceably generated the risk acceptance criteria based on the product&#39;s use and the state-of-the-art. | 1 |   |
| C.1.a.9 | The manufacturer has developed a system it can use to evaluate IT security-related risks.[^C1a-04] | 2 | |

[^C1a-01]: Primary users are those who use the product for medical purposes. Secondary users are all other persons who use the product as intended, e.g. during installation, configuration, update/upgrade

[^C1a-02]: Examples can be found in the section on "Accompanying materials".

[^C1a-03]: Examples: A not specified users (e.g. a user without a mandatory training) uses the medical device software. A specified user uses the product in a non-specified use environment e.g. a product that is installed on a system without malware protection, despite the fact that the manufacturer has specified this malware protection as precondition. Other example: User uses software in web browser Z despite the fact that the manufacturer has specified to use the software only with web browsers X and Y.

[^C1a-04]: Examples of such classification systems are [DREAD](https://en.wikipedia.org/wiki/DREAD_risk_assessment_model) and [CVSS](https://nvd.nist.gov/vuln-metrics/cvss). However, they have no relation to safety.

#### **b) System and software requirements**

##### **i) Authentication and authorization**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.b.i.1 | The manufacturer has identified and documented all data interfaces. | 0 | Ask for the list of data interfaces (wired, WLAN, USB, etc.). |
| C.1.b.i.2 | The manufacturer has specified the protocols and standards used for each data interface.[^C1bi-01] | 1 |   |
| C.1.b.i.3 | For each data interface, the manufacturer has specified the functions offered via the interface. | 0 | Ask for the list of functions. |
| C.1.b.i.4 | The manufacturer has analyzed each function&#39;s security relevance (in terms of hazards). | 0 |   |
| C.1.b.i.5 | The manufacturer has documented the effects of the safety-relevant (in terms of hazards) functions in the risk management documentation. | 0 |   |
| C.1.b.i.6 | The manufacturer has tested all usage scenarios[^C1bi-02] in which risks are generated due to a display of information that has not been specified (e.g. no display, incorrect display or display of information is too late). | 1 | Ask for this to be shown in the risk management or usability file. |
| C.1.b.i.7 | For each role and neighboring system, the manufacturer has defined the product functions that they may have access to via the corresponding interface. | 1 | Ask for the &quot;mapping&quot; of roles to functions to be shown, e.g. as a table. |
| C.1.b.i.8 | The manufacturer has justified its choice of authentication procedure (user name/password, biometric procedure, token, e.g. card) for all roles and all neighboring systems. | 1 | The justification should be risk-based. |
| C.1.b.i.9 | Where necessary, the manufacturer has requested additional mechanisms to minimize the probability of unauthorized access.[^C1bi-04] | 2 |   |
| C.1.b.i.10 | The manufacturer has analyzed in the context of risk management process the impacts on patient safety if a person cannot access patient or device data (e.g. no authorization, they forget their password), and defined appropriate measures.[^C1bi-05] | 1 | This is about balancing the protection goals of &quot;confidentiality&quot; and &quot;safety&quot;. |

[^C1bi-01]: The standards can be divided into the structural interoperability level (e.g. TCP/IP, HTTPs, SFTP, CAN, RS232, USB), the syntactic level (e.g. csv, JSON, XML, HL7), the semantic level (e.g. nomenclatures and coding systems such as LOINC (e.g. laboratory values), ATC (drugs), ICD (diagnoses), UCUM (units) and the organizational level (IHE))

[^C1bi-02]: As an alternative to the user scenarios, you can also examine each related group of UI elements (for example, screen pages, panels) that are offered within this user scenario. This activity is part of the general analysis of the risks that can arise from the implementation of information security product measures.

[^C1bi-04]: For example, restriction of permitted IP or MAC addresses, physical access protection

[^C1bi-05]: In contrast to the points mentioned above, these are risks that arise even though the system behaves as specified. This activity is part of the general analysis of the risks that may arise from the implementation of information security product measures. It is therefore not a question of risks due to a lack of IT security, but of risks (in the sense of freedom from danger, availability and performance) resulting from measures to increase IT security.

##### **ii) Data, communication**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | :-: | --- |
| C.1.b.ii.1 | The manufacturer has created a list of all data managed by the system.[^C1bii-01] | 1 |   |
| C.1.b.ii.2 | The manufacturer has assessed how worthy of protection these data are in relation to confidentiality and their impact on patient safety. | 1 |   |
| C.1.b.ii.3 | The manufacturer has evaluated, in the context of risk management process, the impact if particularly sensitive data is no longer protected. | 1 |   |
| C.1.b.ii.4 | The manufacturer has investigated, in the context of risk management, the consequences of overloading the system with too many requests (e.g. DoS (Denial of Service)) or requests with volumes that are too large, and has defined actions if necessary. | 2 |   |
| C.1.b.ii.5 | The manufacturer has analyzed, in the context of risk management, the consequences of the network no longer being available or no longer being available in the expected quality. | 2 |   |
| C.1.b.ii.6 | The manufacturer has analyzed, in the context of risk management, the consequences of the loss of data and establishes actions (e.g. data backup and disaster recovery), if necessary. | 2 |   |
| C.1.b.ii.7 | The manufacturer has established, in general or for specific products, the criteria[^C1bii-02] for the checking of external data before they are processed further.[^C1bii-03] | 2 |   |

[^C1bii-01]: Examples of such data are patient data (e.g. demographic data, anamnesis, diagnoses), examination data (e.g. laboratory values, radiology and pathology images) and treatment data (prescriptions, settings of medical devices), configuration data of the products, user data (in particular access data), keys, software certificates, program code (including SOUP/OTS).

[^C1bii-02]: Examples of checks: Check for wrong length, completeness, wrong character set, unexpected characters, multiple sent data, outdated / delayed data, unexpected or wrong formats (e.g. no escaping of characters with special meaning like separators, no well-formed XML, invalid JSON files, wrong data types, XML that does not correspond to the specified schema), other character sets, keywords contained in the input and (invalid) commands, big-endian instead of little-endian, values that are not contained in the intended value range (e.g. in the classification or encoding system), wrong time zone, wrong number format, impossible data (e.g. birthday in the future), contradictory data, etc.

[^C1bii-03]: If possible and useful, lists of permitted values (white listing) are recommended.

##### iii) Patches and Vulnerability Management

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.b.iii.1 | The manufacturer has a documented plan of how patches are applied and removed again. This plan includes the development, distribution, installation and review of patches. | 1 | This plan can be part of the incident response plan (see below). |
| C.1.b.iii.2 | The manufacturer has a list of all SOUP/OTS components. | 1 | This requirement belongs more to the &quot;System and software architecture&quot; section. |
| C.1.b.iii.3 | The manufacturer has assessed how often patches are required and how they should be installed. | 2 |   |

##### iv) Other

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | :-: | --- |
| C.1.b.iv.1 | The manufacturer has established how the medical device informs the users in the event that IT security is compromised. | 2 | E.g. like an anti-malware program that warns about suspicious files |
| C.1.b.iv.2 | The manufacturer has assessed what functionality the medical device must guarantee in the event that IT security is compromised. | 2 |   |

#### **c) System and software architecture**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | :-: | --- |
| C.1.c.1 | The manufacturer has documented all SOUP/OTS components (incl. version, manufacturer, reference to information on updates, release notes). | 1 | Ask for the list/table to be shown. The FDA requires a &quot;Cybersecurity Bill of Materials (CBOM)&quot;. |
| C.1.c.2 | The manufacturer has analyzed the specific risks resulting from the choice of technologies (in particular programming language, SOUP/OTS components such as operating systems). | 2 |   |
| C.1.c.3 | The manufacturer has taken measures to ensure that the tools used (e.g., development environment, compiler) as well as the platforms and SOUP/OTS components are free of malicious code.[^C-1c01] | 2 |   |
| C.1.c.4 | The manufacturer has created a list of all services[^C1c-02] that the product offers or uses &quot;externally&quot; (e.g. through its operating system). | 1 | Ask for this list to be shown. |
| C.1.c.5 | For each service, the manufacturer has justified why it has to be visible externally (no time limitation). | 2 | Have the manufacturer explain how/where it is required and tested that services that are not required (or only with time limit) are actually not offered (or only with time limit). The aim of this is to reduce the &quot;attack surface&quot;. |
| C.1.c.6 | If the product provides an interface, the manufacturer has described how attacks via this interface are controlled in the context of risk management process. | 1 | Complete control of these risks is generally not really possible with USB interfaces, but also not necessary in all cases. |
| C.1.c.7 | The manufacturer has identified the process offering/running this service for each externally visible service. | 2 |   |
| C.1.c.8 | For each process, the manufacturer has identified the user (at the operating system level) and, if this user does not run with minimal rights (&quot;worst case&quot; as root), justified this. | 2 |   |
| C.1.c.9 | The manufacturer has systematically identified the risks that would be caused by deficient IT security using threat modeling. | 2 | Have the model show that at least the external actors and/or threats and the threatened objects have to be identified. |
| C.1.c.10 | The manufacturer has analyzed the risks that result from the (auto-)update of anti-malware software. | 1 |   |
| C.1.c.11 | The manufacturer has established how the product detects compromised IT security, documents (logs) this and reacts to it quickly. | 1 |   |
| C.1.c.12 | With regard to the audit log, the manufacturer has determined where its data is stored, how it is protected and updated and how this can be automatically analyzed. | 2 |   |
| C.1.c.13 | For all software components[^C1c-03], services and processes, and data and software components, the manufacturer has analyzed which risks arise if they do not behave in accordance with the specifications due to a problem with IT security. | 1 | Corresponds to an FMEA approach. |
| C.1.c.14 | The manufacturer has taken the software requirements into account in the software architecture. | 1 | For example, for the above software requirements, ask for the component(s) or technologies in the architecture that implement the requirements to be shown. |

[^C1c-01]: The measures include the requirement that development tools, development environments and libraries (SOUP, OTS components) may only be loaded from sources classified as secure and released, that the IT infrastructure is protected by appropriate measures such as virus protection and firewalls, and that libraries are checked for malware before use (e.g. with virus scanners). These requirements may also affect the purchasing process.

[^C1c-02]: Example of services typically offered by operating systems: Web server, RPC, cloud services, drives (e.g. USB), database, DICOM, services via socket connections

[^C1c-03]: at least the top-level components. These components also correspond to the objects

#### **d) Implementation and development of the software**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.d.1 | The manufacturer has created coding guidelines that establish specific requirements for IT security.[^C1d-01] | 1 | Ask the manufacturer to show the coding guidelines and corresponding requirements. |
| C.1.d.2 | The manufacturer only installs code in which reverse engineering and RAM readout cannot lead to unacceptable risks.[^C1d-02] | 3 |   |
| C.1.d.3 | The manufacturer either tests the software (source code and binaries) for malicious code before delivery and/or has protected all computers involved in the development and &quot;production&quot; of the software against malware. | 0 |   |
| C.1.d.4 | The manufacturer has defined measures that can find and eliminate buffer overflows. | 2 |   |

[^C1d-01]: Examples are code metrics (e.g. McCabe measure), specifications for the documentation/commenting of the code and for its formatting, as well as the prohibition of unsafe functions (in C "gets", "strcopy" and  [other functions](https://msdn.microsoft.com/library/bb288454.aspx)), also the obligation to use annotations (e.g. [SAL](https://msdn.microsoft.com/en-us/library/ms235402.aspx)) to avoid buffer overflows, the obligation to check the transfer parameters also for internal interfaces etc.

[^C1d-02]: Examples would be a physical access protection, obfuscation of code, operating system with Address Space Layout Randomization. This protection is usually implemented by the following operating systems

#### **e) Evaluation of software units**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.e.1 | The manufacturer has defined at least one method that is used to check compliance with the coding guidelines. | 1 | The manufacturer will achieve this if it uses tools for static code analysis and/or establishes evaluation criteria for the code reviews. |
| C.1.e.2 | The manufacturer requires code reviews for all components that map safety-relevant functions. | 1 |   |
| C.1.e.3 | The manufacturer has concrete evaluation criteria[^C1e-01] in its guidelines / instructions for code reviews. | 2 |   |
| C.1.e.4 | The code reviews are performed according to the four-eye principle and only by people who have the necessary expertise. The manufacturer has documented this expertise.[^C1e-02] |    2 |   |
| C.1.e.5 | The manufacturer has established which tests (e.g. unit tests) are necessary with which test cases[^C1e-03] and which degrees of coverage are necessary. | 1 |   |
| C.1.e.6 | The manufacturer has described how all SOUP and OTS components have to be verified. | 1 |   |

[^C1e-01]: Examples: No use of insecure functions, "input sanitization" at least for all external interfaces

[^C1e-02]: Documented is to be understood in two senses: 1. the manufacturer has defined the necessary competences (see ISO 13485:2016 subchapter 7.3.2 f). 2 The manufacturer has documented that the specific persons have the competences.

[^C1e-03]: When deriving test cases, you can use the above list of check criteria as a guide.

#### **f) System and software tests**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | :-: | --- |
| C.1.f.1 | The manufacturer includes port scans at all relevant network interfaces in the test plan[^C1f-01] and also performs them. | 1 |   |
| C.1.f.2 | The manufacturer includes penetration tests at all relevant data interfaces and/or for all known vulnerabilities of the OTS components used[^C1f-02] in the test plan and also performs them. | 2 | For a known OTS component in the [NIST Common / National Vulnerability Database](https://nvd.nist.gov/), investigate a vulnerability and have the manufacturer explain how it ensures that it cannot be exploited or why it is not relevant. |
| C.1.f.3 | The manufacturer includes the use of &quot;vulnerability scanners&quot; in the test plan. | 2 |   |
| C.1.f.4 | The manufacturer includes fuzz tests at all relevant data interfaces with at least one tool in the test plan and also performs them.[^C1f-03] | 2 |   |
| C.1.f.5 | The manufacturer includes a security check against the usual attack vectors in the test plan.[^C1f-04] | 2 |   |
| C.1.f.6 | The manufacturer includes the testing of robustness and performance in the test plan. | 2 |   |
| C.1.f.7 | The manufacturer includes the testing of all system/software requirements (see above) in the test plan. | 1 |   |
| C.1.f.8 | The manufacturer also has its software checked by IT security experts with regard to the above measures. | 3 | To reach level 3, this testing must include fuzz and penetration testing as well as analysis of the system/software architecture and the source code. |
| C.1.f.9 | The manufacturer includes third-party test reports (e.g. from SOUP manufacturers) in the system test (if available). | 3 |   |

[^C1f-01]: This plan can be part of the development plan, a V&V plan, or another plan.

[^C1f-02]: For example, the vulnerabilities are stored in the [NIST National Vulnerability Database](https://nvd.nist.gov/) (NVD). Usually scanners like Nessus or OpenVAS are used. The requirement is not that all known vulnerabilities are necessarily tested during penetration testing. The FDA demands this cross reference between the "CBOMs" and the NVD expliit.

[^C1f-03]: Fuzz testing should focus on your own code rather than on the OTS software. The use of several scanners usually leads to a larger range of input values.

[^C1f-04]: Examples: DoS, SQL injection, cross-site scripting (XSS), directory transversal, buffer overflow, syntactically or semantically incorrect queries,

#### **g) Product release**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.g.1 | The manufacturer has addressed the most common vulnerabilities[^C1g-01] and the resulting hazards in the risk analysis or can at least explain how these risks are controlled. | 1 | Select an example from one of the linked lists of the most common errors and ask the manufacturer for a justification. |
| C.1.g.2 | The manufacturer discusses the risks posed by all relevant attack vectors (see above) in the risk analysis and shows how these risks are controlled. | 1 |   |
| C.1.g.3 | The manufacturer has checked the effectiveness of all risk-control measures. | 1 | E.g. ask for references to corresponding tests to be shown. |
| C.1.g.4 | The manufacturer has created a traceability matrix it uses to document that there are measures that control all identified risks related to IT security. | 2 |   |
| C.1.g.5 | The manufacturer has prepared the risk management report and the IT security report. | 2 | In Europe but not in the USA, the IT security report can be part of the risk management report. |
| C.1.g.6 | The manufacturer has drawn up the necessary plans for the post-development phase (e.g. post-market surveillance and incident response plan). | 1 | Details below. |
| C.1.g.7 | The manufacturer has evaluated the completeness of the tests using a traceability matrix that links the tests to the requirements. | 2 |   |

[^C1g-01]: For example, according to [OWSAP top 10](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project) or [CWE/SANS top 25](http://cwe.mitre.org/top25/)

### **2. Requirements for the post-development phases**

#### **a) Production, distribution, installation**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.2.a.1 | The manufacturer has described how it ensures that only the exact intended artifacts (files) in exactly the intended version are delivered in the product or as a product. | 1 | This is about configuration management. Also relevant for downloads or app stores. |
| C.2.a.2 | The manufacturer has described how the people responsible for the installation know which is the latest version and how confusion during installation can be prevented. | 2 | This is only relevant for stand-alone software. A process or work instruction would be expected here. |
| C.2.a.3 | The manufacturer has described how it ensures during the installation that the requirements specified in the support materials (see above) are actually met. | 1 | A process or work instruction would be expected here. |
| C.2.a.4 | The manufacturer has established process/procedures that ensure that it can communicate quickly with operators and users of its products. | 1 | Level 2 is acceptable for non-critical products. [^C2a-01] |

[^C2a-01]: A higher level means, that the implementation and audit are not as critical and can be delayed.

#### **b) Market surveillance**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.2.b.1 | The manufacturer has created a post-market surveillance plan. | 0 |   |
| C.2.b.2 | The manufacturer has described which information is collected from the post-production phase.[^C2b-01] | 1 |   |
| C.2.b.3 | The manufacturer has described how and through which channels information is collected from the post-production phase. | 1 |   |
| C.2.b.4 | The manufacturer has described what information is analyzed and evaluated from the post-production phase [^C2b-02]. | 2 | Ask the manufacturer to explain how it recognizes and defines a trend reversal and the threshold values it has set.[^D2-03] |
| C.2.b.5 | The manufacturer has described the resulting measures.[^C2b-04] | 2 | Ask for the connection to the corrective and preventive actions in the process descriptions to be shown. |
| C.2.b.6 | For each OTS component, the manufacturer has defined at least one source through which it is informed of IT security problems and how often it is monitored [^C2b-05] and described the role this analysis performs with which tools. | 2 | These sources should include the websites of the OTS manufacturer and the [NIST National Vulnerability Database](https://nvd.nist.gov/). |
| C.2.b.7 | The manufacturer has described how it monitors that the technologies and procedures used (e.g. cryptology) are still secure. | 2 |   |

[^C2b-01]: Examples: Audit logs, vulnerability databases, customer complaints, hotline calls, observations (e.g. user behavior), government databases (e.g. FDA MAUDE, BfArM, SwissMedic, etc.), social media, Google search, laws, standards, etc... All also about similar products or technologies

[^C2b-02]: The MDR requires this in the Annex to the Post-Market Surveillance. The manufacturers must determine when (e.g. Incident/near Incident) the measure (see below) is to be taken.

[^C2b-03]: MDR also requires the definition of threshold values and identification of trends. 
[^C2b-04]: Measures may include: Recalls, government notifications, CAPA, product improvement, process improvement, training (user, internal), customer information, change of accompanying materials, restriction of purpose. The definition (e.g. field safety note) must therefore include the definition of who is to be informed (e.g. user, notified body, authority).
[^C2b-05]: The frequency would have to be at least annually, for critical components more frequently than monthly. ANSI UL 2900-2-1 speaks of update cycles of two weeks.

#### **c) Incident response plan**

(incl. recalls, patches, customer communication)

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.2.c.1 | The manufacturer has created an incident response plan.[^C2c-01] | 2 |   |
| C.2.c.2 | The incident response plan governs the criteria the manufacturer uses to evaluate information from the market and when it implements the emergency plan... | 2 |   |
| C.2.c.3 | Who develops and releases the patches and how and within what deadlines. | 2 |   |
| C.2.c.4 | How the customer obtains the patches. | 2 |   |
| C.2.c.5 | How the manufacturer ensures that the patches are also installed. | 2 |   |
| C.2.c.6 | Who informs the customers, how and within what deadlines. | 2 |   |
| C.2.c.7 | In which cases decommissioning or other product recalls is ordered and how. | 2 |   |
| C.2.c.8 | The manufacturer has created a plan how to develop and distribute patches and how to verify the effective distribution | 2 |   |

[^C2c-01]: The Incident Response Plan may be part of other plans or documents such as the post-market surveillance plan or vigilance requirements.

## **D) Product requirements**

### **1. Preliminary remarks and general requirements**

This section describes the product&#39;s technical functions that support IT security. They must be introduced via the requirement specification (system/software requirements) and implemented as requirements.

The following technical product measures for IT security (&quot;security controls&quot;) must, in principle, be appropriate for ensuring the intended purpose, taking into account the intended operating environment: In order to maintain the essential safety and performance requirements, the manufacturer may waive the implementation of individual product measures in justified and documented individual cases. Therefore, for each of the following requirements, instead of implementation, the manufacturer may also include a note in the documentation (e.g. performance specifications) explaining why the requirement has not been implemented with regard to the intended purpose and taking into account the operational environment, and explaining the residual risk.

Manufacturers must check each of the measures described below to see whether they introduce new risks which themselves need to be controlled.

### **2. System/software requirements**

#### **a) Authentication**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | :-: | --- |
| D.2.a.1 | The product only allows users to use it if they have authenticated themselves to the product. | 0 | Ask for the associated test cases to be shown. There may be products where an authentification is not necessary e.g. when using remote controls|
| D.2.a.2 | The product allows the neighboring systems (e.g. other medical devices, IT systems) connected at each data interface to exchange data only if they have been authenticated by the product. | 0 | Ditto. The requirement that data may only be transmitted in encrypted form is set out below. |
| D.2.a.3 | The product allows password authentication only if this has a defined minimum length of which at least one is a non-alphanumeric character and it contains at least one uppercase and one lowercase character. [^D2a-01] | 1 | The choice of the authentication mechanism has been justified by the manufacturer (see above). |
| D.2.a.4 | The product does not have a default password or requires that a password is changed during the first use. | 0 |   |
| D.2.a.5 | The product blocks users and neighboring systems for m minutes after n attempts, with the manufacturer able to define the n and m values or their lower limits. The manufacturer has analyzed the &quot;safety-related&quot; risks resulting from such a blocking and, if necessary, has implemented measures to minimize these risks.[^D2a-02] | 1 |   |
| D.2.a.6 | In the event of an unsuccessful login, the product only displays information that does not allow the user to identify the exact cause of the blocking, e.g. incorrect user name or password. | 2 |   |
| D.2.a.7 | The product terminates user and neighboring system sessions after n minutes of inactivity, with the manufacturer setting the value for n or its upper limit. | 2 |   |
| D.2.a.8 | On authentication the product assigns a role to each user and each neighboring system. | 1 | Ask for an explanation of which software component(s) this functionality will be implemented in and how this is tested. The FDA even requires a hierarchical role concept. |
| D.2.a.9 | The product allows each role to access only the functions it is authorized for. This applies in particular for product updates/upgrades. | 1 | Ditto. |
| D.2.a.10 | The product allows authorized users to block other users and neighboring systems. [^D2a-03] | 1 |   |
| D.2.a.11 | The product allows authorized users to reset the authentication of any required elements (e.g. passwords, cryptographic keys, certificates) of other users and neighboring systems. | 1 | These users typically are referred to as administrators |
| D.2.a.12 | The product allows authorized users to delete other users and neighboring systems. | 1 |   |
| D.2.a.13 | The product does not allow users to change their own permissions. | 2 |   |
| D.2.a.14 | The product allows permissions to be canceled (&quot;breaking the glass&quot;), and identifies/documents the person and the reasons. [^D2a-04] | 2 |   |
| D.2.a.15 | In a client-server architecture, all IT security measures are determined and checked on the server side. | 2 |   |
| D.2.a.16 | In a client-server architecture, all client inputs are checked on the server side. | 2 |   |

[^D2a-01]: Ideally, passwords that can be guessed through dictionary attacks should also be excluded. The minimum length depends on whether brute force attacks are possible, which is easier with a data interface than with a user interface. There are systems where "non-alphanumeric" characters are not possible. This should be considered when choosing the minimum length. Please refer to current [NIST Digital Identity Guidelines](https://pages.nist.gov/800-63-3/sp800-63b.html#sec5) (June 2017) regarding choice of password. *Memorized Secret Authenticators Memorized secrets SHALL be at least 8 characters in length if chosen by the subscriber. Memorized secrets chosen randomly by the CSP or verifier SHALL be at least 6 characters in length and MAY be entirely numeric. If the CSP or verifier disallows a chosen memorized secret based on its appearance on a blacklist of compromised values, the subscriber SHALL be required to choose a different memorized secret. No other complexity requirements for memorized secrets SHOULD be imposed.*

[^D2a-02]: For example, the manufacturer implements "Breaking the glass", i.e. a possibility to bypass the authorization concept in order to be able to access important data promptly. This circumvention must be logged and later justified.

[^D2a-03]: This blocking must also not lead to safety risks. For this reason, locking should not be possible during examination or treatment, but only in maintenance mode, for example.

[^D2a-04]: There are situations in which safety is more important than security, especially as confidentiality. In these emergency situations, a user must access data (in particular patient or prescription data), even if he or she lacks the necessary authorizations. An example would be that an emergency patient must be treated and data such as drug intolerances or laboratory values (e.g. blood group) must be accessed before treatment (e.g. medication, blood transfusion) can begin. This access must always be possible for the treating physician, regardless of the authorizations. The "Breaking-the-glass" can, for example, be implemented as a button.

#### **b) Communication and storage**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | :-: | --- |
| D.2.b.1 | The product allows users to permanently delete all patient-specific data. The product allows you to restrict permissions to do this (e.g. roles). | 2 |   |
| D.2.b.2 | The product protects data from accidental deletion. [^D2b-01] | 2 | Manufacturers must check that there is no higher value security objective that prevents this, e.g. the above requirement. |
| D.2.b.3 | The product only transmits data (or at least security-related data) via its data interfaces in encrypted form. This also applies to storage on external data carrier. | 1 | Ask which encryption is used, why this is considered to be state-of-the-art and how the initial key exchange is done. |
| D.2.b.4 | The product protects the integrity of the data against unwanted modification, e.g. through cryptographic procedures. | 2 | This applies in particular to security-relevant data, such as those mentioned in [^C1bii-01]. |
| D.2.b.5 | By default, the product rejects all incoming connections (e.g. USB, TCP, Bluetooth). | 1 | FDA requirement. |
| D.2.b.6 | The product checks all user inputs and all incoming data on the basis of verification criteria defined by the manufacturer (see above) before further processing. [^D2b-02] | 2 |  |
| D.2.b.7 | The product does not use wireless transmission for the transmission of time-critical data relevant to patient safety. | 2 |   |
| D.2.b.8 | The product stores passwords as &quot;salted hash&quot; only. | 2 | E.g. ask about the hash procedure and, if necessary, ask for it to be shown. |
| D.2.b.9 | The product stores characteristics that could be used to identify a person in encrypted form only. | 2 | Ask for an explanation as to what the manufacturer defines as characteristics that could be used to identify a person and which encryption mechanism it uses. |
| D.2.b.10 | The product protects critical data against accidental change and loss. | 2 |   |
| D.2.b.11 | Every time the program is restarted, it checks whether the mechanisms used to protect the data against loss and modification are in sync. | 2 |   |
| D.2.b.12 | The product allows users to deactivate data interfaces (e.g. USB, remote access). | 2 |   |
| D.2.b.13 | The product checks the integrity of the program code every time it is restarted. | 2 |   |
| D.2.b.14 | In the event of that IT security is compromised, the product provides an emergency mode for functions that have an impact on patient safety. | 2 |   |

[^D2b-01]: The protection can also consist of an undo function. If necessary, the period for an undo must be limited. It should be noted that the data protection requirements are met after (final) deletion of the data.

[^D2b-02]: This review should take place at all levels of interoperability. For example, the protocols would also be to check formats such as the well-formedness of XML files.

#### **c) Patches**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.2.c.1 | The product allows patches (own code, SOUP/OTS components) to be applied. | 1 | Manufacturers should be able to justify exceptions and to explain whether patching may or must be done remotely. |
| D.2.c.2 | The product allows you to remove defective patches again (&quot;roll-back&quot;). | 2 |   |
| D.2.c.3 | The product limits the ability to apply or remove patches to users with the corresponding permissions (authenticated and authorized). [^D2c-01] | 2 |   |
| D.2.c.4 | The product checks changed program code (patches) for integrity before first use and when restarted.[^D2c-02] | 2 | These checks are usually carried out using signatures, which themselves must be protected against forgery. |

[^D2c-01]: This check is usually based on a role-based authorization concept and user authentication.

[^D2c-02]: This is a special case of the requirement that every program code must be checked for integrity at restart. The program code contains the software and the firmware. The check must use cryptographic procedures.

#### **d) Other**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.2.d.1 | The product logs all essential actions[^D2d-01] on/in the system in an audit log, including day and time and actor (user, system). | 2 |   |
| D.2.d.2 | The product ensures that it has the correct system time. | 3 | Have the mechanism explained. And how it is ensured that the user cannot unintentionally changed the time without noticing. |
| D.2.d.3 | The product protects the audit log against change. | 2 | Have the manufacturer explain how the protection is ensured and how a change to the audit log is identified by the system. If necessary, even ask for the responsible software components to be shown. |
| D.2.d.4 | The product implements mechanisms that can detect penetration or an attack[^D2d-02] and react to them.[^D2d-03] | 3 |   |
| D.2.d.5 | The product allows the exchange of certificates. | 2 |   |

[^D2d-01]: For example, successful and unsuccessful login attempts, calling essential functions (including changing configuration settings), identifying security problems (e.g. self-testing by devices, detection of malware, etc.), installing and removing patches, creating, changing and deleting users, passwords and permissions, adding or removing storage media, connecting or removing neighboring systems

[^D2d-02]: For example, the system detects a CPU load greater than x%, a data traffic greater than y MB/s, a storage medium that is fuller than z%, more than n logon attempts within m minutes, and so on.

[^D2d-03]: Also formulate very specifically, ideally via a behavior observable at the interfaces such as "turns off", "disables the data connection", "displays the following warning message" etc.

### **3. System/software architecture**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.3.1 | The software only uses tried and tested libraries/components (no self-implementation) for all cryptographic functions (e.g. encryption, signing). [^D3-01] | 1 | The library must be included in the list of SOUP/OTS components. Ask the manufacturer to explain the selection (criteria) to you. |
| D.3.2 | The software uses different technologies or keys for different functions (e.g. encryption of communication, encryption of data). | 3 |   |
| D.3.3 | The software is protected against malware (viruses, worms etc.) as far as is technically possible. | 1 | Ask for an explanation of how the system is protected against malware and how this protection is maintained. |
| D.3.4 | The software is based on versions of the SOUP/OTS components that do not contain any known security vulnerabilities. Exceptions are justified. | 1 | Pick an example from the SOUP list and research which version the manufacturer has and check which vulnerabilities have been patched in subsequent versions. |

[^D3-01]: The FDA insists on the [https://csrc.nist.gov/Projects/Cryptographic-Module-Validation-Program/Standards](https://csrc.nist.gov/Projects/Cryptographic-Module-Validation-Program/Standards) and the [NIST FIPS 140-2 Suite B](https://csrc.nist.gov/CSRC/media/projects/cryptographic-module-validation-program/documents/security-policies/140sp2851.pdf) 

### **4. Accompanying materials**

The accompanying materials refer primarily to the instructions for use and installation. If necessary, the manufacturers must also provide training materials.

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.4.1 | The instructions for use establish the intended IT environment for operation.[^D4-01] | 1 |   |
| D.4.2 | The instructions for use specify which activities[^D4-02] the operator must perform, as well as how and how often they should be performed. | 1 |   |
| D.4.3 | The installation and service instructions establish which other roles (operator, service technician) are responsible for which activities[^D4-03] and how often they have to be performed. | 1 |   |
| D.4.4 | The support materials describe how to deal with lost or stolen authentication elements (e.g. cards, certificates, cryptographic keys) and forgotten passwords. | 1 |   |
| D.4.5 | The support materials describe how users can recognize an IT security problem with the product and what to do in this case. | 2 | This means that the product implements this detection. |
| D.4.6 | The support materials describe which anti-malware software has been approved for the product and where (e.g. link) it can be obtained and who is responsible for updating it. | 2 | Only to the extent applicable. |
| D.4.7 | The support materials contain the manufacturer&#39;s contact details, which can be used to contact the manufacturer, for example, in the event of problems with IT security.[^D4-04]  |    1 |   |
| D.4.8 | The support materials also give a technical description of the product. [^D4-05] |    2 | This is an FDA requirement in particular. |

[^D4-01]: Examples: Network / interfaces (bandwidth, availability, ports, IP ranges, latencies, encryption, firewalls etc.), virus protection, operating systems, physical access permissions, other software that may or may not run on the system at the same time (e.g. games, firewall, database, web server). The FDA also requires an indication of the direction of communication in the interfaces.

[^D4-02]: Examples: User training (e.g. how to handle passwords), updating virus protection, informing the manufacturer about incidents, installing updates and patches, monitoring, backup (and restore)

[^D4-03]: Examples: Installation, connection to network, evaluation of audit logs, deletion of unneeded users, exchange of keys or certificates, deletion of temporary files

[^D4-04]: The manufacturer may also be required to indicate the period for which it intends to provide support.

[^D4-05]: Network, architecture, flow and state diagrams. Interfaces, components, communication paths, authentication mechanisms for each communicating "component" such as Web pages, servers, cloud storage, and interoperable systems. "Design features that allow validated software updates and patches. List of all components such as 3rd party software (see FDA CBOM).

## **E) Annex**

### **1. Prioritization**

When prioritizing requirements, the guidelines take the following dimensions into account:

- Risk for an individual patient (combination of severity and probability of harm)
- Scope (only one patient, whole hospital, etc.)
- Feasibility (financial and time expenditure, requirements in terms of tools)

Prioritization leads to the following maturity levels

- **Level 0 (&quot;Layperson level&quot;)**: Even most laypeople would comply with this requirement. Anyone who does not even meet the requirements of this level should not be developing medical devices. An auditor may and must expect these requirements to be met in the very first audit.
- **Level 1 (&quot;Advanced beginner&quot; level)**: The manufacturer has already addressed the issue of IT security. This level can be accepted for less critical products and the initial audits. However, an improvement is expected in each subsequent year until level 2 is reached.
- **Level 2 (&quot;State-of-the-art&quot;)**: This is the level that manufacturers generally have to reach in the long run. However, it does not yet reflect the state of scientific knowledge.
- **Level 3 (&quot;Expert level&quot;)**: This level is reached by professional IT security experts. It goes beyond what an auditor can normally expect from medical devices. Energy suppliers, intelligence services and the military would have to operate at this level.

Depending on the risk posed by a product, an auditor or test may require a certain level from the outset[^E1-01].

[^E1-01]: The safety of patients has priority, even if this approach contradicts the basic idea of this guideline, which is to increase IT security step by step rather than not taking action at all.

### **2. Further reading**

#### **a) Laws**

- MDR
- IVDR
- GDPR
- 21 CFR Part 11

#### **b) Standards and best practice guides**

- **AAMI TIR57**, Principles for medical device security – Risk management
- **ANSI UL 2900-1**, Standard for Safety, Standard for Software Cybersecurity Network-Connectable      Products, Part 1: General Requirements
- **ANSI UL 2900-2-1**, Standard for Safety, Software Cybersecurity for Network-Connectable Products, Part      2-1: Particular Requirements for Network Connectable Components of Healthcare and Wellness Systems
- **BSI-CS 132**, [Cyber Security Requirements for Network-Connected Medical Devices](https://www.allianz-fuer-cybersicherheit.de/ACS/DE/_/downloads/BSI-CS_132E.pdf?__blob=publicationFile&v=3)
- **EN IEC 60601-1/AMD1**, Medical electrical equipment – Part 1: General requirements for basic safety and essential performance
- **IEC 62304/AMD1**, Medical device software – Software life cycle processes
- **IEC 62443-2-1**, Industrial communication networks – Network and system security – Part 2-1:      Establishing an industrial automation and control system security program
- **IEC 62443-4-1**, Security for industrial automation and control systems – Part 4-1: Secure product      development lifecycle requirements
- **IEC 62443-4-2**[^E2b-01], Security for industrial automation and control systems – Part 4-2: Technical security requirements for IACS components
- **IEC 80001-1**, Application of risk management for IT-networks incorporating medical devices – Part 1:      Roles, responsibilities and activities
- **IEC 82304-1**, Health software – Part 1: General requirements for product safety
- **IEC/TR 80001-2-2**, Application of risk management for IT-networks incorporating medical devices – Part      2-2: Guidance for the communication of medical device security needs, risks and controls
- **IEC TR 80001-2-8**, Application of risk management for IT-networks incorporating medical devices – Part      2-8: Application guidance – Guidance on standards for establishing the security capabilities identified in IEC TR 80001-2-2
- **ISO/IEC 29147**, Information technology – Security techniques – Vulnerability disclosure
- **ISO/IEC 30111**, Information technology – Security techniques – Vulnerability handling processes
- **FIPS 140-2**, Non-Proprietary Security Policy, Suite B Cryptographic Module
- FDA Guidance Documents
  - “Content of Premarket Submissions for Management of Cybersecurity in Medical Devices”
  - "Postmarket Management of Cybersecurity in Medical Devices"
  - "Cybersecurity for Networked Medical Devices Containing Off-the-Shelf (OTS) Software"
  - "Design Considerations and Premarket Submissions - Recommendations for Interoperable Medical Devices"
  - “Wireless Medical Telemetry Risks and Recommendations”

[^E2b-01]: This standard is still under vote. It is not published yet.

#### **b) Technical literature and books**

- Claudia Eckert: [IT-Sicherheit:](https://www.amazon.de/Sicherheit-Konzepte-Verfahren-Protokolle-Gruyter/dp/3110551586/)[Konzepte - Verfahren - Protokolle (De Gruyter Studium)](https://www.amazon.de/Sicherheit-Konzepte-Verfahren-Protokolle-Gruyter/dp/3110551586/)
- Johner Institute: [Video trainings on the IT security of medical devices](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5Cwww.auditgarant.de)
- Current trends in [Bruce Schneier&#39;s blog](https://www.schneier.com/)

### **3. Considerations**

1. Manufacturers are developing more and more networked medical devices. As a result, the risks resulting from inadequate IT security (e.g. against cyberattacks) have increased. Customers are not informed about the state of the art during the procurement process and are responsible for the costs of security - before or after IT incidents. The number of IT incidents is increasing as the professionalism of attackers is rapidly increasing. Many manufacturers do not take sufficient account of this.
2. The EU regulations (MDR, IVDR) explicitly demand IT security. The EU directives demand it indirectly. These requirements can be found in the respective Annex I with the basic (safety and performance) requirements. The IT security risk analysis goes beyond the analysis of intended usage scenarios. IT security should cover scenarios outside the intended use. Therefore, the concept of foreseeable misuse must be analyzed more precisely, because the manufacturer now has to take all technical possibilities of invasion into the networked medical device into account.
3. In contrast to most other basic requirements, there are no harmonized standards on IT security. Therefore, there is no canonical catalog of requirements that is recognized as reflecting the required state of the art.
4. The FDA has published several guidance documents as well as standards such as ANSI UL 2900-2-1. These specifications are inconsistent in terms of granularity, completeness and conceptual integrity. They only meet the requirements that are usually placed on the quality of a standard to a limited extent.
5. A lot of standards are subject to charges (despite some questionable quality). In the authors&#39; opinion, manufacturers should have free access to regulatory requirements.
6. Because most medical device manufacturers do not deal with IT security at all or only deal with it inadequately, they only meet the basic requirements. There is no consensus in Europe with regard to which technical and procedural obligations concern the manufacturer.
7. For most manufacturers, it would not be feasible in terms of time or in terms of finance to a reach an IT security level in one fell swoop, as required by ANSI UL 2900 series of Cybersecurity standards, for example. Therefore, manufacturers should gradually strive for and reach the state-of-the-art level with regard to IT security. The aim of these guidelines is to have the initial improvements implemented quickly rather than to do nothing due to excessive demands.
8. IT security has to be taken into account in all phases of the product life cycle process. Limiting it to testing is not enough. Together with technical product measures (&quot; security controls&quot;) and documentation, the guideline aims to refer to the three pillars of IT security: Requirements, process, documentation. The structure of these guidelines reflects these pillars and will continue to apply even after the foreseeable technological adjustments.
9. It must be expected that standards will be developed and harmonized for medical device IT security, but this may still take years. Therefore, a guideline is needed in this intermediate phase (only).
10. These guidelines should be available soon (by November 2018) so they can provide guidance to manufacturers in the short term and allow them to act immediately. The speed of its development makes compromises in terms of cooperation with as many parties as possible unavoidable.
11. As the guidelines are based on a step-by-step convergence with the state of the art and have also been produced in a very short time, it cannot claim to be exhaustive.
12. However, the guidelines should represent an extensive and generally accepted level of requirements. The selection and priority of its requirements must therefore be as transparent as possible.
13. Such guidelines must take into account the specifics of medical devices, including the principles of patient safety and a risk-based approach. In this particular case, selected IT security measures (&quot;controls&quot;) may conflict with the basic requirements. For this reason, there cannot be a fixed list of controls for medical devices. The medical device&#39;s intended purpose as defined by the manufacturer is vital in each case.
14. For guidelines to have the intended positive effect on IT security, it is vital that they are easy to understand and implement. Therefore, these guidelines do not set any abstract or &quot;high level&quot; requirements, but give binary test criteria.
15. In order to make them easier to implement, the authors also avoid bringing together as many requirements as possible. Instead, they limit themselves to the requirements they consider them to be particularly relevant and feasible.
16. These guidelines should also be and remain available free of charge in order to encourage their distribution and increase awareness of them.
17. These guidelines deliberately do not require any specific technologies or processes. On the one hand, such technologies and processes are subject to too much change, and on the other hand, the authors of the guide do not presume to decide for manufacturers which technologies and processes are best for the specific application.
18. These guidelines should be available in German and English.
19. The focus is on the IT security of medical devices, not on IT security for organizations such as hospitals and medical device manufacturers. The authors of these guidelines are aware that attacks are increasingly affecting medical device manufacturers&#39; supply chains. Future versions of these guidelines will have to take this into account by establishing requirements for organizations.
