# 

# 

# 

# **A SCHOOL DISTRICT LEADER’S GUIDE TO EVIDENCE-BASED AI PROCUREMENT**

## **TOOLKIT**

## 

## 

## **Quick Procurement Screener**

The Quick Red-Flag Procurement Screener focuses on a small set of high-consequence questions drawn from the full framework, such as whether the vendor can demonstrate appropriate protection of student data, meaningful human oversight, adequate safety protections, equitable performance, and reliable system performance.

The screener is not intended to replace the full evaluation. Rather, it provides an early signal of whether a vendor should proceed to deeper review. This allows districts to identify potentially disqualifying concerns early while preserving the more comprehensive framework for vendors that advance beyond the initial screen.

**Purpose**: Use this three-minute screening tool to quickly identify high-risk vendors that should be disqualified from further consideration or flagged for deeper investigation. This screener can be used at the earliest stage of vendor evaluation, before the full Trustworthiness Checklist is administered.

### **Flag Screener**

#### **Critical Red Flags**

If any of the following are true, procurement should be halted until the issue is resolved:

* The vendor refuses to disclose which AI model powers the product.

* The demo model differs from the production model with no explanation provided.

* Student data is used to train the vendor’s models without explicit opt-in consent.

* No bias or subgroup fairness testing has been conducted.

* No safety filters are implemented specifically for minors.

* AI makes autonomous decisions with no human override mechanism.

* No data deletion or retention policy exists.

* The system is easily jailbroken by students.

* No incident response plan exists for harmful AI behavior.

#### **Caution Indicators Requiring Further Investigation**

These are not automatic disqualifiers, but they signal that the vendor may not be fully mature in their approach to trustworthy AI:

* Only generic benchmarks are provided (not education-specific).

* Explanations are filled with technical jargon that teachers cannot interpret.

* No documentation describes how model changes are communicated or managed.

* The vendor uses vague descriptions like “proprietary model blend” without elaboration.

#### **Positive Signals of Vendor Maturity**

The following indicators suggest a vendor that takes AI trustworthiness seriously:

* Fully transparent about model type, configuration, and version history.

* Clear boundaries around student data (no training on student data unless explicit opt-in).

* Detailed safety documentation with student-focused protections.

* Has conducted subgroup fairness analysis and can provide reports.

* Provides district-specific demos using real curriculum content.

* Offers advance notification windows (7 to 30+ days) before model changes take effect.

* Provides well-designed explanations that teachers can readily understand.

## 

## **Vendor AI Model Disclosure Form**

**Vendor Instructions**: This form collects information about the AI system proposed for use by the district, including its intended use, performance, data practices, safeguards, and governance. The district will use these responses, along with supporting evidence, to identify relevant Requirements, evaluate the available evidence, and determine whether additional documentation, testing, validation, or clarification is needed.

Complete all applicable fields and provide supporting documentation where requested. Responses should describe the specific product and configuration proposed for district use. If an item does not apply, indicate *N/A (Not Applicable)* and briefly explain why. If an item applies but you are unable to provide the requested information, indicate *Unable to Provide* and briefly explain why. Do not leave applicable fields blank. The district may follow up on responses that are incomplete, unclear, or unsupported. Provide complete responses and identify or attach relevant supporting documentation where available.

| Vendor AI Model Disclosure Form |  |
| ----- | :---- |
| **Vendor Name** |  |
| **Product Name** |  |
| **Product Version** |  |
| **Underlying AI Model / Provider** |  |
| **Date Completed** |  |
| **Grade Levels** | ☐ K–5 ☐ 6–8 ☐ 9–12 ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **Subject Areas** | ☐ ELA ☐ Math ☐ Science ☐ Social Studies ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **Deployment Environment**  | ☐ Vendor-Hosted ☐ District-Hosted ☐ Embedded in District Platform |
| **Primary Users** | ☐ Students ☐ Teachers ☐ Administrators ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **AI Role** | ☐ Generates Content ☐ Recommends ☐ Classifies ☐ Summarizes ☐ Predicts ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |

### **A. System & Change Management**

| A1. Underlying Model & Components: Identify the underlying model(s), provider(s), version/release date, and other components that materially shape outputs (e.g., system prompts, retrieval sources, guardrails, external tools, or APIs). |
| :---- |
| Model / Provider / Version: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Other Components: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **A2. Production Consistency**: Is the system used in demonstrations and evaluations identical to the proposed production system? |
| ☐ Yes ☐ No – Explain: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **A3. Material Changes**: Describe the types of material changes that may affect system behavior, including model/provider changes, version updates, or material changes to prompts, retrieval, or guardrails. |
| ☐ Model / Provider ☐ Model Version ☐ System Prompts ☐ Retrieval Sources ☐ Guardrails / Safety Systems ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **A3. Advance Notice for Material Changes:** How much advance notice will you commit to providing before material changes identified above? |
| ☐ \<24 hrs ☐ 1–7 days ☐ 7–30 days ☐ \>30 days ☐ No committed notice period |
| **A4. Customer Control of Material Changes:** Describe whether and how the district can test, approve, defer, or roll back material changes, and whether results of pre-deployment testing are shared with the district. |
| ☐ Test ☐ Approve / Defer ☐ Roll Back ☐ None |
| **A5. Version Tracking:** Describe how the district can identify the model/system version that produced a specific output. |
|  |

### **B. Validity, Reliability & Robustness**

| B1. Performance Evidence: Provide evidence for the intended educational tasks, including the tasks/use cases evaluated, populations tested, methodology, performance measures, and results. |
| :---- |
| Evaluation: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_Population(s): \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_Methodology: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_Metrics: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_Results: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_Limitations: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date(s) of evaluation: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **B2. Testing Performed:** What types of testing have been conducted? |
| ☐ Repeated Runs ☐ Imperfect / Incomplete Student Inputs ☐ Adversarial Inputs ☐ Sycophancy ☐ None ☐ Other Testing: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **B3. Post Deployment Monitoring:** Is performance monitored after deployment, including for changes or drift? |
| ☐ No ☐ Yes – Identify Metrics and Monitoring Frequency: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **B4. Known Limitations & Failure Modes:** Describe known limitations, recurring failure modes, conditions under which performance may degrade, and any important situations in which the system should not be relied upon. |
|  |

### **C. Safety**

| C1. Safety Protections: Describe safeguards for minors, including filters, safety layers, age-specific protections, and examples of blocked or restricted content. |
| :---- |
|  |
| **C2. Harmful-Output Testing Methods:** Indicate testing conducted to identify harmful or inappropriate outputs under realistic student-use conditions. |
| ☐ Red teaming ☐ Adversarial testing ☐ Student-use simulation ☐ Scenario-based testing ☐ No testing conducted ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  |
| **C3. Harmful-Output Testing Areas:** Indicate content and risk areas that were tested through the above methods. |
| ☐ Sexual Content ☐ Violence ☐ Harassment ☐ Self-Harm ☐ Dangerous Instructions ☐ Age-Inappropriate Content ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **C4. High-Risk Student Situations:** When a student discloses a high-risk situation (e.g., self-harm or abuse), how does the system detect and respond, including escalation to a human? |
|  |
| **C5. Safety Incident Response & Notification:** Describe how the system responds when a student discloses a high-risk situation (e.g., self-harm or abuse), including detection, escalation, human intervention, and any limitations. |
|  |

### **D. Security & Resilience**

| D1. Security Assessments: Identify relevant independent security assessments or certifications (e.g., SOC 2, ISO/IEC 27001, penetration testing), including date and scope |
| :---- |
|  |
| **D2. AI-Specific Security Testing**: What AI-specific threats have been tested? |
| ☐ Prompt injection ☐ Jailbreaks ☐ Data Exfiltration ☐ None ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **D3. Security Incident Notification:** What notification commitment will the vendor provide to the district for security incidents, breaches, or material vulnerabilities? |
| ☐ \<24 hrs ☐ 24–72 hrs ☐ \>72 hrs ☐ Not Committed |

### **E. Privacy & Data Governance**

| E1. Data Collected: What categories of data does the system collect, process, or generate? |
| :---- |
| ☐ Prompts ☐ Outputs ☐ Student Records ☐ Usage / Behavioral Data ☐ Metadata ☐ Audio / Visual ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **E2. Training & Evaluation Use**: Is student or district data used to (a) train or fine-tune models by the vendor, (b) train models operated by model providers or other third parties, or (c) evaluate or test the product? For each “Yes,” describe the data, purpose, safeguards, and authorization. |
| **(a)** ☐ No ☐ Yes \- explain: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ **(b)** ☐ No ☐ Yes \- explain:  \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ **(c)** ☐ No ☐ Yes \- explain:  \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **E3. Third Parties & Data Flow:** Identify subprocessors and their purposes, and provide a data-flow diagram showing relevant data movement. |
| ☐ Attached ☐ Unable \- explain:  \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **E4. Prohibited Data Uses:** Is student data used for advertising, profiling, or sale? |
| ☐ No ☐ Yes \- explain:  \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **E5. Legal & Contractual Compliance**: Is the product compliant with FERPA, COPPA, and applicable state student-privacy requirements, and will the vendor sign the district’s data privacy agreement? |
| ☐ No ☐ Yes \-  explain: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |

### **F. Accountability & Transparency**

| F1. System Documentation: What documentation is available describing the system, its intended and prohibited uses, limitations, and known failure modes? |
| :---- |
| ☐ Attached ☐ Unable \- explain:  \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **F2. Product Incident History:** Describe material safety, security, privacy, or performance incidents involving the product in the past 24 months and how they were addressed. |
| ☐ None ☐ Yes \-  explain: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **F3. Roles & Responsibilities:** Identify the vendor's and district's respective responsibilities for AI errors, harmful outputs, privacy incidents, security incidents, and other material system failures. |
|  |
| **F4. District Oversight:** Will the vendor provide relevant log or evaluation-data access and permit audit or independent third-party review, including where information is proprietary? |
| ☐ Yes ☐ No ☐ Limited \-  explain: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |

### **G. Explainability & Interpretability**

| G1. Educator Understanding: Identify what information educators can access to understand AI outputs and recommendations. |
| :---- |
| ☐ Plain-Language Explanations ☐ Sources or Inputs Behind Recommendations ☐ Confidence or Uncertainty Indicators ☐ None ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **G2. Explanation Limitations**: Identify situations in which explanations may be incomplete, misleading, unavailable, or otherwise unreliable. |
|  |

### **H. Fairness & Bias Mitigation**

| H1. Subgroup Performance Testing: Identify the student populations across which performance has been evaluated and attach available reports. |
| :---- |
| ☐ Race / Ethnicity ☐ English Learners ☐ Disability ☐ Gender ☐ Income ☐ Grade Level ☐ No Subgroup Testing Conducted ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **H2. Disparities & Mitigation**: What disparities were identified, how were they addressed, and how are they monitored after deployment? |
|  |
| **H3. Accessibility & Language Access:** What support is provided for multilingual learners and students with disabilities? |
| ☐ Multilingual ☐ Assistive technology ☐ None ☐ Other:\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |

**I. Human Oversight & Agency**

| I1. Human Control: Can educators and administrators review, edit, override, or reject AI outputs? Describe how. |
| :---- |
| ☐ No ☐ Yes \- explain: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  |
| **I2. Unreviewed Outputs**: Identify any circumstances in which AI outputs reach students or trigger actions without educator review. |
| ☐ No ☐ Yes \- explain: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| **I3. District Controls:** Identify the controls available to the district to configure, restrict, disable, or otherwise enforce boundaries on AI features. |
| ☐ Configure ☐ Restrict ☐ Disable ☐ Set User / Role Permissions ☐ None ☐ Other: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |

### **J. Independent Validation & Improvement**

| J1. Independent Validation: List relevant independent evaluations, audits, or efficacy studies, including the conducting party, date, scope, and results. Attach reports where available. |
| :---- |
|  |
| **J2. Improvement**: Describe material improvements made in response to evaluation findings, incidents, monitoring, or educator feedback in the past 12–24 months. |
|  |

### **Certification**

I certify that the information provided is accurate, complete, and current to the best of my knowledge as of the date signed, and that material changes after submission will be reported in accordance with Section A.

| Name / Title |  |
| :---- | :---- |
| **Signature** |  |
| **Date** |  |

## 

## 

## **Vendor AI Trustworthiness Checklist**

**Purpose**: This checklist is designed for district procurement officers, technology directors, curriculum leaders, and other decision-makers to evaluate AI-enabled edtech products before procurement. It is aligned with the Eight Trustworthiness Dimensions and contextualized for K–12 education. The checklist provides a structured way to document the Requirements that apply to a district's intended use and the evidence supporting each Requirement-level determination.

**Instructions**: For each checklist item, first consult the corresponding Appendix section for that Dimension. The Appendix explains what the Requirement means, what evidence to consider, what questions to ask the vendor, and what adequate evidence may look like. Use evidence gathered from the vendor, product testing, documentation, independent sources, and other relevant sources to evaluate each Requirement.

Before recording a final determination, address any Evidence Gaps identified during the evaluation. Districts may seek additional documentation, clarification, testing, validation, or other evidence as appropriate to the importance and potential consequences of the Requirement. Once reasonable efforts to resolve material Evidence Gaps have been completed, record one of the following:

* **Yes** — available evidence establishes that the Requirement is satisfied for the district's intended use and context.

* **No** — available evidence establishes that the Requirement is not satisfied for the district's intended use and context.

* **Insufficient Evidence** — after reasonable efforts to obtain additional evidence, the district cannot reliably establish whether the Requirement is satisfied.

Districts should document the evidence supporting each determination and any material limitations or remaining uncertainty.

| A. Validity, Reliability, & Robustness | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The system performs its intended functions accurately using tasks, benchmarks, or evaluation methods relevant to the district’s intended educational use. | ☐ | ☐ | ☐ |
| The system has been evaluated across student populations, users, and operating conditions relevant to the district’s intended use. | ☐ | ☐ | ☐ |
| The system produces consistent results across repeated or comparable inputs under similar conditions. | ☐ | ☐ | ☐ |
| The system maintains reliable performance when given varied, ambiguous, incomplete, or unexpected inputs and under relevant failure conditions. | ☐ | ☐ | ☐ |

| B. Safety | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The system has safeguards designed to prevent harmful or inappropriate outputs, including sexual content, violence, harassment, and other age-inappropriate material. | ☐ | ☐ | ☐ |
| The system provides safeguards appropriate for use by minors and the ages of students who will use it. | ☐ | ☐ | ☐ |
| The vendor evaluates foreseeable risks of physical, psychological, social, and educational harm associated with the intended use. | ☐ | ☐ | ☐ |
| The vendor has tested the system for harmful or inappropriate outputs under realistic student-use conditions. | ☐ | ☐ | ☐ |
| The vendor provides a defined process for identifying, reporting, investigating, and responding to unsafe outputs or incidents. | ☐ | ☐ | ☐ |
| The vendor monitors safety performance after deployment and communicates significant safety issues or newly identified risks to the district. | ☐ | ☐ | ☐ |

| C. Security & Resilliency | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The system uses appropriate authentication and access controls to prevent unauthorized access to the system and its data. | ☐ | ☐ | ☐ |
| Access to student, educator, administrative, and other sensitive information is appropriately limited according to user roles and permissions. | ☐ | ☐ | ☐ |
| The vendor regularly assesses the system for security vulnerabilities and documents how identified vulnerabilities are addressed. | ☐ | ☐ | ☐ |
| The vendor tests the system against relevant attacks or manipulation techniques, including prompt injection, jailbreaks, or other adversarial inputs where applicable. | ☐ | ☐ | ☐ |
| The system has safeguards to detect and respond to unauthorized access, manipulation, or other security incidents. | ☐ | ☐ | ☐ |
| The vendor maintains a documented incident response process for security breaches or other significant system compromises. | ☐ | ☐ | ☐ |
| The system has appropriate continuity, backup, and recovery measures to maintain or restore essential functionality following failures or disruptions. | ☐ | ☐ | ☐ |
| The vendor communicates significant security vulnerabilities, incidents, or service disruptions to the district within defined timeframes. | ☐ | ☐ | ☐ |

| D. Privacy & Data Governance | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The vendor clearly identifies the student and educator data collected by the system. | ☐ | ☐ | ☐ |
| The system collects only the data reasonably necessary to provide the intended service. | ☐ | ☐ | ☐ |
| The vendor clearly documents how student and educator data are used, including whether data are used for model training or product improvement. | ☐ | ☐ | ☐ |
| The vendor maintains controls ensuring that student data are not used to train foundational models unless the district has explicitly authorized such use and it is legally and contractually permitted. | ☐ | ☐ | ☐ |
| The vendor provides a clear data-flow description or diagram showing how data move through the system and to third parties or subprocessors. | ☐ | ☐ | ☐ |
| The vendor clearly documents where and for how long student and educator data are stored and retained. | ☐ | ☐ | ☐ |
| The vendor provides a mechanism for authorized district data to be deleted when retention is no longer necessary or when required by law or contract. | ☐ | ☐ | ☐ |
| Student and educator data are protected through appropriate encryption, access controls, and other security measures. | ☐ | ☐ | ☐ |
| Third-party sharing and subprocessor practices are clearly documented and consistent with district requirements. | ☐ | ☐ | ☐ |
| The vendor’s data practices comply with applicable legal, regulatory, contractual, and district requirements. | ☐ | ☐ | ☐ |

| E. Accountability & Transparency | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The vendor clearly identifies the model, system, or AI technology powering the relevant student or educator experience, including version information where appropriate. | ☐ | ☐ | ☐ |
| The vendor clearly documents the system’s intended uses, limitations, and known failure modes relevant to the district’s use case. | ☐ | ☐ | ☐ |
| The vendor provides sufficient information about how the system behaves to enable meaningful district oversight. | ☐ | ☐ | ☐ |
| The system used during demonstrations or evaluations is representative of the production system, or material differences are clearly disclosed. | ☐ | ☐ | ☐ |
| The vendor provides advance notice of significant model, system, or functionality changes that could affect performance, safety, privacy, or other evaluation criteria. | ☐ | ☐ | ☐ |
| The district can determine which model or system version produced an output when versioning is relevant to oversight or incident investigation. | ☐ | ☐ | ☐ |
| The vendor clearly identifies roles and responsibilities for addressing system errors, harmful outputs, privacy incidents, and other significant failures. | ☐ | ☐ | ☐ |
| The vendor provides a documented process for reporting concerns and obtaining remediation or support when significant problems occur. | ☐ | ☐ | ☐ |
| Relevant system changes, incidents, and evaluation information are documented sufficiently to support district audit and oversight. | ☐ | ☐ | ☐ |
| Material vendor commitments concerning system changes, data practices, incident response, and district oversight are documented in enforceable agreements where appropriate. | ☐ | ☐ | ☐ |

| F. Explainability & Interpretability | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The system provides explanations of outputs or recommendations that are understandable and useful to educators and administrators. | ☐ | ☐ | ☐ |
| Educators can identify the relevant information, inputs, or factors that informed an AI-generated recommendation, classification, or decision. | ☐ | ☐ | ☐ |
| Explanations provide sufficient context for educators to evaluate whether an output is appropriate for the student or instructional situation. | ☐ | ☐ | ☐ |
| The system communicates relevant limitations, uncertainty, or confidence information when needed to interpret an output appropriately. | ☐ | ☐ | ☐ |
| The vendor documents known situations in which the system’s explanations or outputs may be incomplete, misleading, or unreliable. | ☐ | ☐ | ☐ |
| The level of explanation provided is appropriate to the potential consequences of the AI-supported decision or recommendation. | ☐ | ☐ | ☐ |

| G. Fairness & Bias Mitigation | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The vendor has evaluated system performance across student populations relevant to the district’s intended use. | ☐ | ☐ | ☐ |
| The vendor has tested for disparities in accuracy, error rates, recommendations, classifications, or other relevant outcomes across relevant student populations. | ☐ | ☐ | ☐ |
| The vendor evaluates potential differences associated with relevant characteristics such as race/ethnicity, ELL status, disability, age, or other contextually relevant factors. | ☐ | ☐ | ☐ |
| The vendor can explain how potential sources of bias are identified, evaluated, and mitigated. | ☐ | ☐ | ☐ |
| The vendor documents identified disparities or limitations and the steps taken to address them. | ☐ | ☐ | ☐ |
| The system has been evaluated for its potential to introduce, reinforce, or amplify existing inequities in the intended educational context. | ☐ | ☐ | ☐ |
| Fairness evaluations are based on evidence from populations and use cases that are relevant to the district’s intended deployment. | ☐ | ☐ | ☐ |

| H. Human Oversight & Agency | Yes | No | Insufficient Evidence |
| :---- | :---: | :---: | :---: |
| The system provides appropriate human review before AI outputs are used to make high-stakes decisions. | ☐ | ☐ | ☐ |
| Educators or administrators can review AI-generated outputs before acting on them when human judgment is necessary. | ☐ | ☐ | ☐ |
| Educators can question, override, modify, or reject AI recommendations when appropriate. | ☐ | ☐ | ☐ |
| Human overrides can be made without unreasonable technical or procedural barriers. | ☐ | ☐ | ☐ |
| The system clearly distinguishes AI-generated recommendations or outputs from decisions made by educators or administrators. | ☐ | ☐ | ☐ |
| Educators receive guidance on appropriate and inappropriate uses of the system, including situations in which AI outputs should not be relied upon. | ☐ | ☐ | ☐ |
| Educators have access to sufficient information about an AI output to exercise meaningful judgment rather than simply accepting the system’s recommendation. | ☐ | ☐ | ☐ |
| The district can establish and enforce appropriate boundaries for when and how the AI system may be used. | ☐ | ☐ | ☐ |

# 