# IT Security Guideline

## **A) Meta information**

### **1. Guideline objectives**

The objective of these guidelines is to provide medical device manufacturers and notified bodies with instructions and a specific checklist in order to:

- Explain what notified bodies&#39; expectations are
- Encourage the step-by-step implementation of IT security for medical devices
- Compensate for the absence of a harmonized standard (until there is one) as well as possible

Unlike a lot of other guidelines on IT security, these guidelines only relate to medical devices and focus on patient safety.

These guidelines are **not** intended to act as a textbook or guidelines for implementing IT security. Instead, they are intended as a guide for reviewing IT security.

The annex details the considerations that led to the creation of these guidelines.

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

The structure of these guidelines is based on these ideas: In Chapter B) it starts off with the general requirements, in Chapter C) it establishes the process requirements (including documentation), and in Chapter D) it establishes the product requirements (including documentation). Within these &quot;main chapters&quot;, the requirements are structured along software life cycle process lines:

1. **Process requirements**
    ​    1. **Requirements for the development process**
    ​           1. Intended purpose and stakeholder requirements
    ​           2. System and software requirements
    ​           3. System and software architecture
    ​           4. Implementation and development of the software
    ​           5. Evaluation of software units
    ​           6. System and software tests
    ​           7. Product release
    ​    2. **Requirements for the post-development phase**
    ​           1. Production, distribution, installation
    ​           2. Market surveillance
    ​           3. Incident response plan
2. **Product requirements**
    ​    1. Preliminary remarks and general requirements
    ​    2. System requirements
    ​    3. System and software architecture
    ​    4. Support materials

The risk management requirements are woven into the requirements throughout the product life cycle.

#### **b) Applicable chapters and requirements**

Manufacturers should first use the guidelines to check the completeness of the specifications documents (procedural and work instructions, checklists, etc.). For this, they should look at sections B) to D).

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
- Dr. Christian Johner ([Johner Institute](https://www.johner-institut.de))

Dr. Georg Heidenreich ([Siemens Healthcare GmbH](https://www.healthcare.siemens.com/)) has made a significant contribution as a reviewer.

These guidelines are published under a [BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)[Creative Commons license](https://creativecommons.org/licenses/?lang=de). This requires the naming of the authors (&quot;TÜV SÜD, Johner Institute and Dr. Georg Heidenreich&quot;) and allows third parties to build on this work, e.g. to improve, but only for non-commercial purposes.

The license permits commercial use of the product for consulting purposes, including audits. However, it prohibits the commercial use of this work itself, either unchanged or amended, e.g. as brochure for sales purposes.

### **5. Document control, document identification**

This document is managed via the version control system Git or the platform GitHub. Only the documents named in this repository are valid.

The version history including the respective authors can be found in the document history.

The released versions are identified as such in the repository using a tag. Versions without a tag are documents in the draft stage.

## **B) General requirements**

### **1. Process**

Manufacturers should cover all the aspects mentioned below either in the procedural instructions or in the corresponding plans in order to ensure that IT security is systematically ensured. Usually the following procedural instructions and plans are affected:

- Development
- Risk management
- Verification and validation (if not part of development)
- Post-market surveillance and vigilance
- Service, installation, decommissioning
- Customer communication
- Management evaluation (ISO 13485 requires &quot;applicable new or revised regulatory requirements&quot; to be taken into account).

If the manufacturer uses outsourced processes, the requirements apply accordingly. For example, a (software) development service provider would have to observe the sections of these guidelines that are relevant for it.

### **2. Expertise**

Manufacturers must ensure and demonstrate that they have sufficient expertise to ensure IT security in line with the state of the art. This evidence is often most easily obtained through internal or external training.

In this way, manufacturers can also access the expertise of external resources.

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| B.2.1 | The manufacturer has created a list of all roles that are directly or indirectly involved with IT security.[1](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn1) | 1 |   |
| B.2.2 | The manufacturer has provided evidence of the IT-security expertise for each role.[2](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn2) | 1 |   |
| B.2.3 | The manufacturer has records (e.g. training documents) that lead to the conclusion that the people in question actually have this expertise. | 1 |   |
| B.2.4 | The (software) development plans define the (additional or deviating) expertise on a product-specific basis. | 2 | Requirement since ISO 13485:2016. |

### **3. Documentation**

The manufacturer should be able to provide evidence that it has complied with the relevant requirements of these guidelines. There are no specific requirements for the documentation and &quot;objective evidence&quot;.

In Europe (unlike in the USA), there is also no obligation to create a specific document on IT security. Instead, manufacturers can integrate these aspects into existing documents, such as the QM system specification documents and the technical documentation (e.g. software files, risk management files).

## **C) Process requirements**

### **1. Product development requirements**

#### **a) Intended purpose and stakeholder requirements**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.a.1 | The manufacturer has identified all neighboring systems (medical devices, IT systems) that may be connected to the product. | 0 |   |
| C.1.a.2 | The manufacturer has created a list of roles (people, neighboring systems) that may interact with the product. | 0 | Ask for the list of roles to be shown. |
| C.1.a.3 | The manufacturer has identified all markets and all the regulatory requirements that are relevant in these markets. | 0 | Ask for the list of IT security regulatory requirements to shown. |
| C.1.a.4 | The manufacturer has identified the intended primary and secondary users with their IT expertise.[3](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn3) | 1 |   |
| C.1.a.5 | The manufacturer has defined the intended user environment.[4](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn4) | 1 |   |
| C.1.a.6 | The manufacturer has analyzed the risks (hazards) that result if the system is used in the specified user environment by someone who is not a specified user.[5](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn5) | 1 |   |
| C.1.a.7 | The manufacturer has described in the risk management documentation what the IT security threats are and what the consequences would be for patients, users and third parties. | 1 |   |
| C.1.a.8 | The manufacturer has traceably generated the risk acceptance criteria based on the product&#39;s use and the state-of-the-art. | 1 |   |
| C.1.a.9 | The manufacturer has developed a system it can use to evaluate IT security-related risks.[6](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn6) | 2 |   |

#### **b) System and software requirements**

##### **i) Authentication and authorization**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.b.i.1 | The manufacturer has identified all data interfaces. | 0 | Ask for the list of data interfaces (wired, WLAN, USB, etc.) to be shown. |
| C.1.b.i.2 | The manufacturer has specified the protocols and standards used for each data interface.[7](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn7) | 1 |   |
| C.1.b.i.3 | For each data interface, the manufacturer has specified the functions offered via the interface. | 0 | Ask for the list of functions to be shown. |
| C.1.b.i.4 | The manufacturer has analyzed each function&#39;s security relevance (in terms of hazards). | 0 |   |
| C.1.b.i.5 | The manufacturer has documented the effects of the safety-relevant (in terms of hazards) functions in the risk management documentation. | 0 |   |
| C.1.b.i.6 | The manufacturer has tested all usage scenarios[8](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn8) in which risks are generated due to a display of information that has not been specified (e.g. no display, incorrect display or display is too late). | 1 | Ask for this to be shown in the risk management or usability file. |
| C.1.b.i.7 | For each role and neighboring system, the manufacturer has defined the product functions that they may have access to via the corresponding interface. | 1 | Ask for the &quot;mapping&quot; of roles to functions to be shown, e.g. as a table. |
| C.1.b.i.8 | The manufacturer has justified its choice of authentication procedure (user name/password, biometric procedure, token, e.g. card) for all roles and all neighboring systems. | 1 | The justification should be risk-based. |
| C.1.b.i.9 | Where necessary, the manufacturer has requested additional mechanisms to minimize the probability of unauthorized access.[9](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn9) | 2 |   |
| C.1.b.i.10 | The manufacturer has analyzed, in the risk management process, the effects on patient safety if a person cannot access patient or device data (e.g. no authorization, they forget their password), and defined appropriate measures.[10](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn10) | 1 | This is about balancing the protection goals of &quot;confidentiality&quot; and &quot;safety&quot;. |

##### **ii) Data, communication**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.b.ii.1 | The manufacturer has created a list of all data managed by the system.[11](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn11) | 1 |   |
| C.1.b.ii.2 | The manufacturer has assessed how worthy of protection these data are in relation to confidentiality and their impact on patient safety. | 1 |   |
| C.1.b.ii.3 | The manufacturer has evaluated, in the context of risk management process, the effect if particularly sensitive data is no longer protected. | 1 |   |
| C.1.b.ii.4 | The manufacturer has investigated, in the context of risk management, the consequences of overloading the system with too many requests (e.g. DoS) or requests with volumes that are too large, and has defined actions if necessary. | 2 |   |
| C.1.b.ii.5 | The manufacturer has, in the context of risk management, analyzed the consequences of the network no longer being available or no longer being available in the expected quality. | 2 |   |
| C.1.b.ii.6 | The manufacturer has, in the context of risk management, analyzed the consequences of the loss of data and establishes actions, such as making a backup, if necessary. | 2 |   |
| C.1.b.ii.7 | The manufacturer has established, in general or for specific products, the criteria[12](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn12) for the checking of external data before they are processed further.[13](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn13) | 2 |   |

##### **iii) Patches**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.b.iii.1 | The manufacturer has a documented plan of how patches are applied and removed again. This plan includes the development, distribution, installation and review of patches. | 1 | This plan can be part of the incident response plan (see below). |
| C.1.b.iii.2 | The manufacturer has a list of all SOUP/OTS components. | 1 | This requirement belongs more to the &quot;System and software architecture&quot; section. |
| C.1.b.iii.3 | The manufacturer has assessed how often patches are required and how they should be installed. | 2 |   |

##### ** iv) Other**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.b.iv.1 | The manufacturer has established how the medical device informs the users in the event that cybersecurity is compromised. | 2 |   |
| C.1.b.iv.2 | The manufacturer has assessed what functionality the medical device must guarantee in the event that cybersecurity is compromised.  |   |   |

#### **c) System and software architecture**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.c.1 | The manufacturer has documented all SOUP/OTS components (incl. version, manufacturer, reference to information on updates, release notes). | 1 | Ask for the list/table to be shown. The FDA requires a &quot;Cybersecurity Bill of Materials (CBOM)&quot;. |
| C.1.c.2 | The manufacturer has analyzed the specific risks resulting from the choice of technologies (in particular programming language, SOUP/OTS components). | 2 |   |
| C.1.c.3 | The manufacturer has taken measures to ensure that the tools used (e.g., development environment, compiler) as well as the platforms and SOUP/OTS components are free of malicious code.[14](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn14) | 2 |   |
| C.1.c.4 | The manufacturer has created a list of all services[15](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn15) that the product offers or uses &quot;externally&quot; (e.g. through its operating system). | 1 | Ask for this list to be shown. |
| C.1.c.5 | For each service, the manufacturer has justified why it has to be visible externally (no time limitation). | 2 | Have the manufacturer explain how/where it is required and tested that services that are not required (no time limit) are not offered (no time limit). The aim of this is &quot;attack surface reduction&quot;. |
| C.1.c.6 | If the product provides an interface, the manufacturer has described how attacks via this interface are controlled in the context of risk management. | 1 | Complete control of these risks is generally not really possible with USB interfaces, but also not necessary in all cases. |
| C.1.c.7 | The manufacturer has identified the process offering/running this service for each externally visible service. | 2 |   |
| C.1.c.8 | For each process, the manufacturer has identified the user (at the operating system level) and, if this user does not run with minimal rights (&quot;worst case&quot; as root), justified this. | 2 |   |
| C.1.c.9 | The manufacturer has systematically identified the risks that would be caused by deficient IT security using threat modeling. | 2 | Have the model show that at least the external actors and/or threats and the threatened objects have to be identified. |
| C.1.c.10 | The manufacturer has analyzed the risks that result from the (auto-)update of anti-malware software. | 1 |   |
| C.1.c.11 | The manufacturer has established how the product detects compromised IT security, document (log) this and react to it quickly. |   |   |
| C.1.c.12 | With regard to the audit log, the manufacturer has determined where its data is stored, how it is protected and updated and how this can be automatically analyzed. |   |   |
| C.1.c.13 | For all software components[16](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn16), services and processes, and data and software components, the manufacturer has analyzed which risks arise if they do not behave in accordance with the specifications due to a problem with IT security. | 1 | Corresponds to an FMEA approach. |
| C.1.c.14 | The manufacturer has taken the software requirements into account in the software architecture. | 1 | For example, for the above software requirements, ask for the component(s) or technologies in the architecture that implement the requirements to be shown. |

#### **d) Implementation and development of the software**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.d.1 | The manufacturer has created coding guidelines that establish specific requirements for IT security.[17](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn17) | 1 | Ask the manufacturer to show the coding guidelines and corresponding requirements. |
| C.1.d.2 | The manufacturer only plays code where reverse engineering and RAM readout cannot lead to unacceptable risks.[18](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn18) | 3 |   |
| C.1.d.3 | The manufacturer either tests the software (source code and binaries) for malicious code before delivery and/or has protected all computers involved in the development and &quot;production&quot; of the software against malware. | 0 |   |
| C.1.d.4 | The manufacturer has defined measures that can find and eliminate buffer overflows. | 2 |   |

#### **e) Evaluation of software units**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.e.1 | The manufacturer has defined at least one method that is used to check compliance with the coding guidelines. | 1 | The manufacturer will achieve this if it uses tools for static code analysis and/or establishes specifications for the code reviews. |
| C.1.e.2 | The manufacturer requires code reviews for all components that map (IT) security-relevant functions. | 2 |   |
| C.1.e.3 | The manufacturer has concrete test criteria[19](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn19) in its specification documents for the code reviews. | 1 |   |
| C.1.e.4 | The code reviews are carried out according to the four-eye principle and only by people who have the necessary expertise. The manufacturer has documented this expertise.[20](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn20) |    2 |   |
| C.1.e.5 | The manufacturer has established which tests (e.g. unit tests) are necessary with which test cases[21](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn21) and which degrees of coverage are necessary. | 1 |   |
| C.1.e.6 | The manufacturer has described how all SOUP and OTS components have to be verified. | 1 |   |

#### **f) System and software tests**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.f.1 | The manufacture includes port scans at all relevant network interfaces in the test plan[22](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn22) and also performs them. | 1 |   |
| C.1.f.2 | The manufacturer includes penetration tests at all relevant data interfaces and/or for all known vulnerabilities of the OTS components used[23](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn23) in the test plan and also performs them. | 2 | For a known OTS component in the [NIST Common / National Vulnerability Database](https://nvd.nist.gov/), investigate a vulnerability and have the manufacturer explain how it ensures that it cannot be exploited or why it is not relevant. |
| C.1.f.3 | The manufacturer includes the use of &quot;vulnerability scanners&quot; in the test plan. |   |   |
| C.1.f.4 | The manufacturer includes fuzz tests at all relevant data interfaces with at least one tool in the test plan and also performs them.[24](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn24) | 2 |   |
| C.1.f.5 | The manufacturer includes a security check against the usual attack vectors in the test plan.[25](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn25) | 2 |   |
| C.1.f.6 | The manufacturer includes the testing of robustness and performance in the test plan. |   |   |
| C.1.f.7 | The manufacturer includes the testing of all system/software requirements (see above) in the test plan. | 1 |   |
| C.1.f.8 | The manufacturer also has its software checked by IT security experts with regard to the above measures. | 3 | To reach level 3, this testing must include fuzz and penetration testing as well as analysis of the system/software architecture and the source code. |
| C.1.f.9 | The manufacturer includes third-party test reports (e.g. from SOUP manufacturers) in the system test (if available). |   |   |

#### **g) Product release**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.1.g.1 | The manufacturer has addressed the most common errors[26](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn26) and the resulting hazards in the risk analysis or can at least explain how these risks are controlled. | 1 | Select an example from one of the linked lists of the most common errors and ask the manufacturer for a justification. |
| C.1.g.2 | The manufacturer discusses the risks posed by all relevant attack vectors (see above) in the risk analysis and shows how these risks are controlled. | 1 |   |
| C.1.g.3 | The manufacturer has checked the effectiveness of all risk-control measures. | 1 | E.g. ask for references to corresponding tests to be shown. |
| C.1.g.4 | The manufacturer has created a traceability matrix it uses to document that there are measures that control all risks related to IT security. | 2 |   |
| C.1.g.5 | The manufacturer has prepared the risk management report and the IT security report. | 2 | In Europe but not in the USA, the IT security report can be part of the risk management report. |
| C.1.g.6 | The manufacturer has drawn up the necessary plans for the post-development phase (e.g. post-market surveillance and incident response plan). | 1 | Details below. |
| C.1.g.7 | The manufacturer has tested the completeness of the tests using a traceability matrix that links the tests to the requirements. | 2 |   |

### **2. Requirements for the post-development phases**

#### **a) Production, distribution, installation**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.2.a.1 | The manufacturer has described how it ensures that only the exact intended artifacts (files) in exactly the intended version are delivered in the product or as a product. | 1 | This is about configuration management. Also relevant for downloads or app stores. |
| C.2.a.2 | The manufacturer has described how the people responsible for the installation know which is the latest version and how confusion during installation can be prevented. | 2 | This is only relevant for stand-alone software. A procedural or work instruction would be expected here. |
| C.2.a.3 | The manufacturer has described how it ensures during the installation that the requirements specified in the support materials (see above) are actually met. | 1 | A procedural or work instruction would be expected here. |
| C.2.a.4 | The manufacturer has established procedures that ensure that it can communicate quickly with operators and users of its products. | 1 | Level 2 is acceptable for non-critical products. |

#### **b) Market surveillance**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.2.b.1 | The manufacturer has created a post-market surveillance plan. | 0 |   |
| C.2.b.2 | The manufacturer has described which information is collected from the downstream phase.[27](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn27) | 1 |   |
| C.2.b.3 | The manufacturer has described how and through which channels information is collected from the downstream phase. | 1 |   |
| C.2.b.4 | The manufacturer has described what information is analyzed and evaluated from the downstream phase. [^D2-02] | 2 | Ask the manufacturer to explain how it recognizes and defines a trend reversal and the threshold values it has set.[28](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn28) |
| C.2.b.5 | The manufacturer has described the resulting measures.[29](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn29) | 2 | Ask for the connection to the corrective and preventive actions in the process descriptions to be shown. |
| C.2.b.6 | For each OTS component, the manufacturer has defined at least one source through which it is informed of IT security problems and how often it is monitored[30](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn30) and described the role this analysis performs with which tools. | 2 | These sources should include the websites of the OTS manufacturer and the [NIST Vulnerability Database](https://nvd.nist.gov/). |
| C.2.b.7 | The manufacturer has described how it monitors that the technologies and procedures used (e.g. cryptology) are still secure. | 2 |   |

#### **c) Incident response plan**

(incl. recalls, patches, customer communication)

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| C.2.c.1 | The manufacturer has created an incident response plan.[31](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn31) | 2 |   |
| C.2.c.2 | The incident response plan governs the criteria the manufacturer uses to evaluate information from the market and when it implements the emergency plan... | 2 |   |
| C.2.c.3 | Who develops and releases the patches and how and within what deadlines. | 2 |   |
| C.2.c.4 | How the customer obtains the patches. | 2 |   |
| C.2.c.5 | How the manufacturer ensures that the patches are also installed. | 2 |   |
| C.2.c.6 | Who informs the customers, how and within what deadlines. | 2 |   |
| C.2.c.7 | In which cases decommissioning or other product recalls is ordered and how. | 2 |   |

## **D) Product requirements**

### **1. Preliminary remarks and general requirements**

This section describes the product&#39;s technical functions that support IT security. They must be introduced via the requirement specification (system/software requirements) and implemented as requirements.

The following technical product measures for IT security (&quot;security controls&quot;) must, in principle, be appropriate for ensuring the intended purpose, taking into account the intended operating environment: In order to maintain the basic requirements for safety and function, the manufacturer may waive the implementation of individual product measures in justified and documented individual cases. Therefore, for each of the following requirements, instead of implementation, the manufacturer may also include a note in the documentation (e.g. performance specifications) explaining why the requirement has not been implemented with regard to the intended purpose and taking into account the operational environment, and explaining the residual risk.

Manufacturers must check each of the measures described below to see whether they introduce new risks which themselves need to be controlled.

### **2. System/software requirements**

#### **a) Authentication**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.2.a.1 | The product only allows users to use it if they have authenticated themselves to the product. | 0 | Ask for the associated test cases to be shown. |
| D.2.a.2 | The product allows the neighboring systems (e.g. other medical devices, IT systems) connected at each data interface to exchange data only if they have been authenticated by the product. | 0 | Ditto The requirement that data may only be transmitted in encrypted form is set out below. |
| D.2.a.3 | The product allows password authentication only if this has a defined minimum length of which at least one is a non-alphanumeric character and it contains at least one uppercase and one lowercase character. [^C2a-02] | 1 | The choice of the authentication mechanism has been justified by the manufacturer (see above). |
| D.2.a.4 | The product does not have a default password or requires that a password be changed during the first use. | 0 |   |
| D.2.a.5 | The product blocks users and neighboring systems for m minutes after n attempts, with the manufacturer able to define the n and m values or their lower limits. The manufacturer has analyzed the &quot;safety-related&quot; risks resulting from such a blocking and, if necessary, has implemented measures to minimize these risks.[32](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn32) | 1 |   |
| D.2.a.6 | In the event of an unsuccessful login, the product only displays information that does not allow the user to identify the exact cause of the blocking, e.g. incorrect user name or password. | 2 |   |
| D.2.a.7 | The product terminates user and neighboring system sessions after n minutes of inactivity, with the manufacturer setting the value for n or its upper limit. | 2 |   |
| D.2.a.8 | The product assigns a role to each user and each neighboring system for authentication. | 1 | Ask for an explanation of which software component(s)/components this functionality will be implemented in and how this is tested. The FDA even requires a hierarchical role strategy |
| D.2.a.9 | The product allows each role to access only the functions it is authorized for. This applies in particular for product updates/upgrades. | 1 | Ditto. |
| D.2.a.10 | The product allows authorized users to block other users and neighboring systems. [^C2a-04] | 1 |   |
| D.2.a.11 | The product allows authorized users to reset the authentication of any required elements (passwords, cryptographic keys, certificates) of other users and neighboring systems. | 1 |   |
| D.2.a.12 | The product allows authorized users to delete other users and neighboring systems. | 1 |   |
| D.2.a.13 | The product does not allow users to change their own permissions. | 2 |   |
| D.2.a.14 | The product allows permissions to be canceled (&quot;breaking the glass&quot;), and identifies/documents the person and the reasons. [^C2a-05] | 2 |   |
| D.2.a.15 | In a client-server architecture, all cybersecurity measures are determined and checked on the server side. | 2 |   |
| D.2.a.16 | In a client-server architecture, all client inputs are checked on the server side. | 2 |   |

#### **b) Communication and storage**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.2.b.1 | The product allows users to permanently delete all patient-specific data. The product allows you to restrict permissions to do this (e.g. to roles). | 2 |   |
| D.2.b.2 | The product protects data from accidental deletion. [^C2b-01] | 2 | Manufacturers must check that there is no higher value security objective that prevents this, e.g. the above requirement. |
| D.2.b.3 | The product only transmits data (or at least security-related data) via its data interfaces in encrypted form. This also applies to storage on external data carrier. | 1 | Ask which encryption is used and how the initial key exchange is done. |
| D.2.b.4 | The product protects the integrity of the data against unwanted modification, e.g. through cryptographic procedures. | 2 | This applies in particular to security-relevant data, such as those mentioned in [^C2b-01]. |
| D.2.b.5 | By default, the product rejects all incoming connections (e.g. USB, TCP, Bluetooth). | 1 | FDA requirement. |
| D.2.b.6 | The product checks all user inputs and all incoming data on the basis of verification criteria defined by the manufacturer (see above) before further processing. [^C2b-02] | | 1 |
| D.2.b.7 | The product does not use wireless transmission for the transmission of time-critical data relevant to patient safety. | 2 |   |
| D.2.b.8 | The product stores passwords as &quot;salted hash&quot; only. | 2 | E.g. ask about the hash procedure and, if necessary, ask for it to be shown. |
| D.2.b.9 | The product stores characteristics that could be used to identify a person in encrypted form only. | 2 | Ask for an explanation as to what the manufacturer defines as characteristics that could be used to identify a person and which encryption mechanism it uses. |
| D.2.b.10 | The product protects critical data against accidental change and loss. | 2 |   |
| D.2.b.11 | Every time the program is restarted, it checks whether the mechanisms used to protect the data against loss and modification are in sync. |   |   |
| D.2.b.12 | The product allows users to deactivate data interfaces (e.g. USB, remote access). | 2 |   |
| D.2.b.13 | The product checks the integrity of the program code every time it is restarted. | 2 |   |
| D.2.b.14 | In the event of that security is compromised, the product provides an emergency mode for functions that have an effect on patient safety. | 2 |   |

#### **c) Patches**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.2.c.1 | The product allows patches (own code, SOUP/OTS components) to be applied. | 1 | Manufacturers should be able to justify exceptions and to explain whether patching may or must be done remotely. |
| D.2.c.2 | The product allows you to remove defective patches again (&quot;roll-back&quot;). | 2 |   |
| D.2.c.3 | The product limits the ability to apply or remove patches to users with the corresponding permissions (authenticated and authorized). [^C3c-01] | 2 |   |
| D.2.c.4 | The product checks changed program code (patches) for integrity before first use and when restarted.[33](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn33) | 2 | These checks are usually carried out using signatures, which themselves must be protected against forgery. |

#### **d) Other**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.2.d.1 | The product logs all essential actions[34](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn34) on/in the system in an audit log, including day and time and actor (user, system). | 2 |   |
| D.2.d.2 | The product ensures that it has the correct system time. | 3 | Have the mechanism explained. And how it is ensured that the user cannot unintentionally changed the time without noticing. |
| D.2.d.3 | The product protects the audit log against change. | 2 | Have the manufacturer explain how the protection is ensured and how a change to the audit log is identified by the system. If necessary, even ask for the responsible software components to be shown. |
| D.2.d.4 | The product implements mechanisms that can detect penetration or an attack[35](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn35) and react to them.[36](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn36) | 3 |   |
| D.2.d.5 | The product allows the exchange of certificates. | 2 |   |

### **3. System/software architecture**

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.3.1 | The software only uses tried and tested libraries/components (no self-implementation) for all cryptographic functions (e.g. encryption, signing). [^C3-01]  | 1 | The library must be included in the list of SOUP/OTS components. Ask the manufacturer to explain the selection (criteria) to you. |
| D.3.2 | The software uses different technologies or keys for different functions (e.g. encryption of communication, encryption of data). | 3 |   |
| D.3.3 | The software is protected against malware (viruses, worms etc.) as far as is technically possible. | 1 | Ask for an explanation of how the system is protected against malware and how this protection is maintained. |
| D.3.4 | The software is based on versions of the SOUP/OTS components that do not contain any security vulnerabilities. Exceptions are justified. | 1 | Pick an example from the SOUP list and research which version the manufacturer has and check which vulnerabilities have been patched in subsequent versions. |

### **4. Accompanying materials**

The accompanying materials refer primarily to the instructions for use and installation. If necessary, the manufacturers must also provide training materials.

| **ID** | **Requirement** | **Level** | **Comments** |
| --- | --- | --- | --- |
| D.4.1 | The instructions for use establish the intended IT environment for operation.[37](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn37) | 1 |   |
| D.4.2 | The instructions for use specify which activities[38](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn38) the operator must perform, as well as how and how often they should be performed. | 1 |   |
| D.4.3 | The installation and service instructions establish which other roles (operator, service technician) are responsible for which activities[39](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn39) and how often they have to be performed. | 1 |   |
| D.4.4 | The support materials describe how to deal with lost or stolen authentication elements (e.g. cards, certificates, cryptographic keys) and forgotten passwords. | 1 |   |
| D.4.5 | The support materials describe how users can recognize an IT security problem with the product and what to do in this case. | 2 | This means that the product implements this detection. |
| D.4.6 | The support materials describe which anti-malware software has been approved for the product and where (e.g. link) it can be obtained and who is responsible for updating it. | 2 | Only to the extent applicable. |
| D.4.7 | The support materials contain the manufacturer&#39;s contact details, which can be used to contact the manufacturer, for example, in the event of problems with IT security.[^D4-04]  |    1 |   |
| D.4.8 | The support materials also give a technical description of the product. [^D4-05] |    2 | This is an FDA requirement in particular. |

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

Depending on the risk posed by a product, an auditor or test may require a certain level from the outset[40](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fn40).

### **2. Further reading**

#### **a) Laws**

- MDR
- IVDR
- GDPR
- 21 CFR Part 11

#### **b) Standards and best practice guides**

- AAMI/TIR57
- EN IEC 60601-1
- IEC 62443-2-1
- IEC 62443-4-1
- IEC 62443-4-2
- IEC 82304-1
- IEC 80001-1
- IEC/TR 80001-2-2
- IEC/TR 80001-2-8
- UL 2900-1
- UL 2900-2-1
- BSI-CS 132
- ISO/IEC 29147: Information technology ó Security techniques ó Vulnerability disclosure
- FDA Guidance Documents
  - &quot;Content of Premarket Submissions for Management of Cybersecurity in Medical Devices&quot;
  - &quot;Postmarket Management of Cybersecurity in Medical Devices&quot;
  - &quot;Design Considerations and Premarket Submissions - Recommendations for Interoperable Medical Devices&quot;
  - &quot;Wireless Medical Telemetry Risks and Recommendations&quot;
- [BSI Cyber-Sicherheitsanforderungen an netzwerkf‰hige Medizinprodukte [Cyber Security Requirements for Network-Compatible Medical Devices]](https://www.allianz-fuer-cybersicherheit.de/ACS/DE/_/downloads/BSI-CS_132.pdf?__blob=publicationFile&amp;v=6)

#### **b) Specialist literature, text books**

- Eckert: [IT-Sicherheit:](https://www.amazon.de/Sicherheit-Konzepte-Verfahren-Protokolle-Gruyter/dp/3110551586/)[Konzepte - Verfahren - Protokolle (De Gruyter Studium](https://www.amazon.de/Sicherheit-Konzepte-Verfahren-Protokolle-Gruyter/dp/3110551586/)
- Johner Institute: [Video trainings on the IT security of medical devices](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5Cwww.auditgarant.de)
- Current trends in [Bruce Schneier&#39;s blog](https://www.schneier.com/)

### **3. Considerations**

1. Manufacturers are developing more and more networked medical devices. As a result, the risks resulting from inadequate IT security (e.g. against cyberattacks) have increased. Customers are not informed about the state of the art during the procurement process and are responsible for the costs of security - before or after IT incidents. The number of IT incidents is increasing as the professionalism of attackers is rapidly increasing. Many manufacturers do not take sufficient account of this.
2. The EU regulations (MDR, IVDR) explicitly demand IT security. The EU directives demand it indirectly. These requirements can be found in the respective Annex I with the basic (safety and performance) requirements. The IT security risk analysis goes beyond the analysis of intended usage scenarios. IT security should cover scenarios outside the intended use. Therefore, the concept of foreseeable misuse must be analyzed more precisely, because the manufacturer now has to take all technical possibilities of invasion into the networked medical device into account.
3. In contrast to most other basic requirements, there are no harmonized standards on IT security. Therefore, there is no canonical catalog of requirements that is recognized as reflecting the required state of the art.
4. The FDA has published several guidance documents as well as standards such as UL 2900-2-1. These specifications are inconsistent in terms of granularity, completeness and conceptual integrity. They only meet the requirements that are usually placed on the quality of a standard to a limited extent.
5. A lot of standards are subject to charges (despite some questionable quality). In the authors&#39; opinion, manufacturers should have free access to regulatory requirements.
6. Because most medical device manufacturers do not deal with IT security at all or only deal with it inadequately, they only meet the basic requirements. There is no consensus in Europe with regard to which technical and procedural obligations concern the manufacturer.
7. For most manufacturers, it would not be feasible in terms of time or in terms of finance to a reach an IT security level in one fell swoop, as required by UL 2900, for example. Therefore, manufacturers should gradually strive for and reach the state-of-the-art level with regard to IT security. The aim of these guidelines is to have the initial improvements implemented quickly rather than to do nothing due to excessive demands.
8. IT security has to be taken into account in all phases of the product life cycle process. Limiting it to testing is not enough. Together with technical product measures (&quot;controls&quot;) and documentation, the guideline aims to refer to the three pillars of IT security: Requirements, process, documentation. The structure of these guidelines reflects these pillars and will continue to apply even after the foreseeable technological adjustments.
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

1. Examples are: Developers, testers, regulatory affairs department, quality managers, employees in service and support, product managers, medical device consultants. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref1)
2. Competences should be specified (comprehension, capabilities), rather than primarily topics. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref2)
3. Primary users are those who use the product for the intended medical purpose. Secondary users are all other people who use the product as intended, e.g. during installation, configuration, update/upgrade. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref3)
4. Examples can be found in the section on labeling. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref4)
5. Examples: The operator has not installed virus protection. Users share a password. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref5)
6. Examples of such classification systems are [DREAD](https://en.wikipedia.org/wiki/DREAD_(risk_assessment_model)) and [CVSS](https://nvd.nist.gov/vuln-metrics/cvss). However, these have no relation to safety. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref6)
7. The standards can be divided into the structural interoperability level (e.g. TCP/IP, HTTPs, SFTP, CAN, RS232, USB), the syntactic level (e.g. csv, JSON, XML, HL7), the semantic level (e.g. nomenclatures and coding systems such as LOINC (e.g. laboratory values), ATC (drugs), ICD (diagnoses), UCUM (units) and the organizational level (IHE)). [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref7)
8. As an alternative to the usage scenarios, each group of UI elements (for example, screen pages, panels) offered within this usage scenario can be examined. This activity is part of the general analysis of the risk caused by the implementation of product measures concerning IT security. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref8)
9. g. restriction of permitted IP and MAC addresses, physical access protection. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref9)
10. Unlike the aspects described above, these are risks that arise even though the system behaves as specified. This activity is part of the general analysis of the risk caused by the implementation of product measures concerning IT security. It is therefore not a question of risks due to a lack of IT security, but of risks (in the sense of freedom from danger, availability and performance) resulting from measures to increase IT security. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref10)
11. Examples of such data are patient data (e.g. demographic data, case histories, diagnoses), examination data (e.g. laboratory values, radiological and pathological images) and treatment data (prescriptions, medical device settings), configuration data for the devices, user data (in particular access data), keys, software certificates, program code (including SOUP/OTS). [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref11)
12. Examples of checks: Check for incorrect length, completeness, incorrect character set, unexpected characters, data sent multiple times, outdated/late data, unexpected or incorrect formats (e.g. no escaping of characters with special meaning like separators, no well-formed XML, invalid JSON files, incorrect data types, XML that does not correspond to the specified schema), other character sets, keywords contained in the input and (invalid) commands, Big-Endian instead of Little-Endian, values that are not included in the intended value range (e.g. in the classification or encoding system), wrong time zone, wrong number format, impossible data (e.g. birthday in the future), contradictory data, etc. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref12)
13. If possible and useful, lists of permitted values (whitelisting) are recommended. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref13)
14. The measures include the requirement that development tools, development environments and libraries (SOUP, OTS components) may only be loaded from approved sources that have been classified as secure, that the IT infrastructure is protected by appropriate measures such as virus protection and firewalls, and that libraries are checked for malware before use (e.g. with virus scanners). These requirements may also affect the purchasing process. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref14)
15. Example of services typically offered by operating systems: Webserver, RPC, cloud services, drives (e.g. USB), database, DICOM, services via socket connections. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref15)
16. At least the top-level components. These components also correspond to the objects. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref16)
17. Examples are code metrics (e.g. McCabe measure), specifications for the documentation of/commenting on the code and for its formatting, as well as the prohibition of insecure functions (in C &quot;gets&quot;, &quot;strcopy&quot; and [ther functions](https://msdn.microsoft.com/library/bb288454.aspx)), and the obligation to use annotations (e.g. [SAL](https://msdn.microsoft.com/en-us/library/ms235402.aspx)) to avoid buffer overflows, the obligation to check the transfer parameters for internal interfaces, etc. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref17)
18. Examples would be a physical access protection, obfuscation of code, operating system with address space layout randomization. This protection is usually provided by the operating systems. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref18)
19. Examples: No use of insecure functions, &quot;input sanitization&quot; for all external interfaces at least. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref19)
20. Documented should be understood as having a double meaning: 1. The manufacturer has defined the necessary competences (see ISO 13485:2016 chapter 7.3.2 f). 2. The manufacturer has documented that the specific people have the competences. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref20)
21. When working out the test cases, you can use the above list of check criteria as a guide. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref21)
22. This plan may be part of the development plan, a V&amp;V plan, or another plan. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref22)
23. Vulnerabilities are, for example, recorded in the[NIST National Vulnerability Database](https://nvd.nist.gov/) (NVD). In general, scanners such as Nessus or OpenVAS are used. The requirement is not for penetration testing to necessarily test for all known vulnerabilities. The FDA explicitly requires this cross referencing between the CBOMs and the NVS. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref23)
24. Fuzz testing should focus more on your own code and less so on the OTS software. The use of several scanners usually leads to a larger range of input values. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref24)
25. g. DoS, SQL injection, cross-site scripting, directory transversal, buffer overflow, syntactically or semantically incorrect queries. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref25)
26. g. according to [OWSAP Top 10](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project) or [CWE/SANS Top 25](http://cwe.mitre.org/top25/). [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref26)
27. Examples: Audit logs, vulnerability databases, customer complaints, calls to the hotline, observations (e.g. user behavior), government databases (FDA MAUDE, BfArM, SwissMedic etc.), social media, Google searches, laws, standards etc. As well as everything on similar products or technologies. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref27)
28. The MDR requires this in the Annex on post-market surveillance. The manufacturers must establish when (e.g. incident/near incident), the measures (see below) have to be implemented. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref28)
29. Measures may include: Recalls, notifications from the regulatory authorities, CAPA, product improvement, process improvement, training (user, internal), customer information, changes to the support materials, limitation of intended purpose. The definition must therefore include the definition of who (e.g. user, notified body, authority) should be informed and how (e.g. field safety note). [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref29)
30. The frequency must be at least once a year, for critical components it must be more than once a month. UL 2900-2-1 talks about two-week update cycles. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref30)
31. The incident response plan can be part of other plans or documents, such as the post-market surveillance plan or the vigilance requirements. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref31)
32. For example, the manufacturer implements a &quot;break glass&quot;, i.e. an option to bypass the authorization strategy in order to be able to access important data immediately. These workaround must be recorded and later justified. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref32)
33. This is a special case of the requirement that every program code must be checked for integrity in the event of a restart. The programcode includes the software and the firmware. The check must use cryptographic methods. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref33)
34. g. successful and unsuccessful login attempts, calling up of basic functions (including changing configuration settings), identifying security problems (e.g. independent self-testing by devices, detection of malware, etc.), installing and removing patches, creating, changing and deleting users, passwords and permissions, adding or removing storage media, connecting or removing neighboring systems. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref34)
35. Don&#39;t formulate so generally, but specify specific system requirements, e.g. the system detects a CPU load greater than x%, a data traffic greater than y MB/s, a storage medium that is using than z% of its capacity, more than n login attempts within m minutes, and so on. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref35)
36. Again, formulate very specifically, ideally via a behavior observable at the interfaces such as &quot;turns off&quot;, &quot;deactivates the data connection&quot;, &quot;shows the following warning&quot;, etc. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref36)
37. Examples: Network/interfaces (bandwidth, availability, ports, IP ranges, latencies, encryption, firewalls etc.), virus protection, operating systems, physical access permissions, other software that may or may not run on the system at the same time (games?, firewall, database, web server). The FDA also requires details of the direction of communication at the interfaces. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref37)
38. Examples: User training (e.g. how to handle passwords), virus protection updates, manufacturer information on incidents, updates and patches, monitoring, backup (and restore). [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref38)
39. Examples: Installation, connection to network, evaluation of audit logs, deletion of unneeded users, exchange of keys or certificates, deletion of temporary files. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref39)
40. Patient safety takes priority, even if this approach contradicts the basic idea behind these guidelines, it is better to increase IT security step-by-step rather than to not take any action at all. [?](../../C:%5CUsers%5Cchristianjohner%5CDocuments%5C99_Temp%5Crepo%5Cit-security-guideline%5CGuideline-IT-Security-DE.md#fnref40)

[^C2b-02]: The check should be done at all levels of interoperability. For example, the protocols and formats would also have to checked, e.g. whether XML -files are well-formed.

[^C3-01]: The FDA insists on [https://csrc.nist.gov/Projects/Cryptographic-Module-Validation- Program/Standards] (https://csrc.nist.gov/Projects/Cryptographic- Module-Validation-Program/Standards) and [NIST FIPS 140-2 Suite B] (https://csrc.nist.gov/CSRC/media/projects/cryptographic-module- validation-program/documents/security-policies/140sp2851.pdf).

[^D4-04]: If necessary, the manufacturer must also specify how long it intends to offer support for.

[^D4-05]: Network, architecture, flow and state diagrams.  Interfaces, components, communication paths, authentication mechanisms for each communicating component, such as websites, servers, cloud storage and interoperable systems. Design features that permit the validated software updates and patches. List of all components, such as 3rd party software (see FDA CBOM)