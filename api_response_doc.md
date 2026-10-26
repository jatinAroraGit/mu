# Software Requirements Engineering: 100 Oral Examination Questions & Answers

---

## Module 1: Introduction & Fundamentals of Requirements Engineering (Questions 1–15)

#### Q1: What is Software Requirements Engineering, and why is it critical in the software development lifecycle?
**Answer:**  
Requirements Engineering is the systematic process of discovering, analyzing, documenting, and maintaining the services a system must provide and the constraints under which it must operate. It is critical because errors identified during the requirements phase cost significantly less to fix than those discovered during testing or deployment, preventing project failure and scope creep.

---

#### Q2: What is the difference between Functional Requirements and Non-Functional Requirements?
**Answer:**  
Functional requirements describe **what** the system should do (specific behaviors, features, and calculations, e.g., "The system shall process credit card payments"). Non-functional requirements specify **how well** the system performs its function, defining quality attributes, constraints, and performance targets (e.g., "Payment processing must complete within 2 seconds").

---

#### Q3: Distinguish between User Requirements and System Requirements.
**Answer:**  
User requirements are high-level statements written in natural language with diagrams, meant for end-users and business stakeholders to understand system services. System requirements are detailed operational descriptions specifying the target system's functions, operational constraints, and interfaces for developers and testers.

---

#### Q4: Define the terms "Domain Requirements" and give an example.
**Answer:**  
Domain requirements are derived from the domain of application rather than specific user needs. They reflect the environment, regulatory rules, or physical laws of that field. For instance, in medical device software, a domain requirement might mandate adherence to HIPAA compliance or specific safety margins for radiation dosage.

---

#### Q5: What is the primary difference between a software requirement and a design specification?
**Answer:**  
A requirement focuses on the problem space (**what** needs to be built and **why**), while a design specification focuses on the solution space (**how** the software architecture, database schemas, and components will implement those requirements).

---

#### Q6: What are the main sub-processes involved in Requirements Engineering?
**Answer:**  
The main sub-processes are:
1. **Requirements Elicitation** (gathering needs)
2. **Requirements Analysis and Negotiation** (checking feasibility and resolving conflicts)
3. **Requirements Specification** (documenting requirements formally)
4. **Requirements Validation** (ensuring accuracy and completeness)
5. **Requirements Management** (handling changes throughout the software lifecycle)

---

#### Q7: What are business requirements, and how do they differ from functional requirements?
**Answer:**  
Business requirements articulate the overarching objectives, target ROI, and business vision of the organization ordering the system (e.g., "Increase market share by 15%"). Functional requirements define the specific features and technical behaviors the software must exhibit to achieve those business objectives.

---

#### Q8: What is "Scope Creep," and how does effective requirements engineering help prevent it?
**Answer:**  
Scope creep refers to uncontrolled, continuous growth or changes in a project's scope without adjustments to time, budget, or resources. Effective requirements engineering establishes a baseline of validated, prioritized requirements and institutes formal change management procedures to evaluate and approve modifications.

---

#### Q9: What role do constraints play in requirements specification?
**Answer:**  
Constraints restrict the space of acceptable solutions. They impose boundaries on implementation options, such as requiring specific hardware platforms, compliance with legal/regulatory standards, programming languages, or legacy integration parameters.

---

#### Q10: Why are ambiguous requirements dangerous in software projects?
**Answer:**  
Ambiguous requirements lead to conflicting interpretations by developers, testers, and clients. This results in software features built contrary to user expectations, leading to costly rework, delayed schedules, and failed acceptance testing.

---

#### Q11: What is a Software Requirements Specification (SRS) document?
**Answer:**  
An SRS is an official document that comprehensively describes what the software system must do. It contains functional, non-functional, interface, and design constraints, serving as a binding contract between customers and development teams.

---

#### Q12: Explain the term "Requirements Traceability."
**Answer:**  
Requirements Traceability is the ability to track a requirement throughout its lifecycle—backward to its origin/source stakeholder and forward to the corresponding design components, source code, test cases, and deployment artifacts.

---

#### Q13: Why is stakeholder identification crucial in the early stages of a project?
**Answer:**  
Identifying all relevant stakeholders ensures that all critical perspectives, operational needs, regulatory constraints, and usability demands are gathered. Missing key stakeholders early can lead to omitted requirements and costly design overhauls late in development.

---

#### Q14: What is the role of a Business Analyst (BA) in Requirements Engineering?
**Answer:**  
A Business Analyst acts as a bridge between business stakeholders and the technical team. They elicit user needs, translate business goals into clear technical requirements, facilitate trade-off discussions, and document specification artifacts.

---

#### Q15: What is the difference between a product constraint and an organizational constraint?
**Answer:**  
A product constraint specifies constraints on the delivered product's runtime behavior or properties (e.g., maximum memory consumption). An organizational constraint stems from company policies, standards, or process choices (e.g., mandatory use of Agile methodologies or specific internal coding standards).

---

## Module 2: Requirements Elicitation & Analysis Techniques (Questions 16–30)

#### Q16: What is Requirements Elicitation, and why is it challenging?
**Answer:**  
Requirements Elicitation is the process of seeking, discovering, and understanding user and system needs. It is challenging because stakeholders often find it difficult to articulate their requirements, possess tacit knowledge, ask for unrealistic features, or have conflicting priorities.

---

#### Q17: Compare open-ended vs. closed-ended questions in requirements interviews.
**Answer:**  
Open-ended questions encourage stakeholders to talk freely and explain processes in depth (e.g., "How do you handle order processing?"). Closed-ended questions seek specific, concise facts or confirmations (e.g., "How many orders do you process daily?"), useful for verifying concrete data points.

---

#### Q18: What is a Workshop / JAD (Joint Application Development) session?
**Answer:**  
A JAD session is a structured, collaborative workshop bringing together business users, analysts, systems architects, and software engineers to discuss, negotiate, and define system requirements rapidly in a shared decision-making environment.

---

#### Q19: Explain the concept of "Ethnography" or observation in elicitation.
**Answer:**  
Ethnography involves observing users directly in their actual work environment as they perform tasks. It is effective for discovering implicit, unstated requirements and workflow nuances that users often forget to explain during interviews.

---

#### Q20: What is a Personas model in user-centered design?
**Answer:**  
A Persona is a fictional representation of an ideal user segment based on empirical user research. It encapsulates goals, behaviors, pain points, and technical proficiencies to keep product teams focused on user-centric design choices.

---

#### Q21: What is a Use Case, and what are its key components?
**Answer:**  
A Use Case describes an interaction sequence between an external actor (user or system) and the target system to achieve a measurable goal. Key components include: Actor, Preconditions, Trigger, Main Success Scenario, Alternative Flow, and Postconditions.

---

#### Q22: How does a User Story differ from a traditional Use Case?
**Answer:**  
A User Story is a lightweight, short description of a feature from an end-user perspective, structured as: *"As a [user], I want [goal] so that [benefit]"*. Use Cases are more detailed specifications outlining step-by-step system interactions and exception paths.

---

#### Q23: Explain the concept of "MoSCoW" prioritization.
**Answer:**  
MoSCoW is a prioritization technique categorizing requirements into four levels:
- **M**ust have (critical for delivery)
- **S**hould have (important, but non-essential for initial launch)
- **C**ould have (desirable enhancements)
- **W**on't have (agreed items excluded for the current release)

---

#### Q24: What is a Context Diagram, and how does it help define project boundaries?
**Answer:**  
A Context Diagram is a high-level data flow diagram representing the system as a single central box interacting with external entities (users, external hardware, external software systems). It visually defines system scope and operational boundaries.

---

#### Q25: What is the purpose of a Requirements Feasibility Study?
**Answer:**  
A feasibility study evaluates whether the proposed system is technically buildable within current technology limits, financially viable within budget constraints, legally compliant, and operational within the target environment.

---

#### Q26: What are "Tacit Knowledge" challenges in elicitation?
**Answer:**  
Tacit knowledge refers to implicit expertise that users hold naturally and perform routinely without conscious thought. Users struggle to express this knowledge during interviews, risking missing operational steps unless observed directly.

---

#### Q27: How do mind maps assist during the requirements elicitation phase?
**Answer:**  
Mind maps provide a visual method for structuring ideas, brainstorming user needs, and organizing complex relationships non-linearly during initial discovery workshops.

---

#### Q28: Describe the concept of "Interface Elicitation."
**Answer:**  
Interface elicitation focuses on discovering requirements related to interactions between the new system and existing external hardware, third-party services, databases, or legacy software applications.

---

#### Q29: What is the Kano Model, and how does it categorize customer requirements?
**Answer:**  
The Kano Model classifies requirements into three distinct categories based on user satisfaction impact:
1. **Basic Needs** (expected standard features)
2. **Performance Needs** (linear satisfaction based on delivery quality)
3. **Excitement Needs** (delighters that exceed expectations)

---

#### Q30: Why is resolving conflicting requirements essential during the analysis stage?
**Answer:**  
Different stakeholders have opposing priorities (e.g., security teams wanting multi-factor authentication vs. users wanting single-click access). Resolving these early prevents building contradictory features that fail stakeholder acceptance.

---

## Module 3: Software Requirements Specification (SRS) & Standards (Questions 31–45)

#### Q31: What is the IEEE 830 / ISO/IEC/IEEE 29148 standard?
**Answer:**  
These standards define internationally accepted guidelines and structural templates for writing high-quality Software Requirements Specifications (SRS), promoting clear categorization of system, functional, non-functional, and interface details.

---

#### Q32: What are the key characteristics of a "Good" requirement?
**Answer:**  
A well-defined requirement must be:
- **Clear/Unambiguous**
- **Complete**
- **Consistent**
- **Verifiable/Testable**
- **Feasible**
- **Traceable**
- **Necessary**

---

#### Q33: How do you write a verifiable (testable) requirement?
**Answer:**  
A requirement is verifiable if a cost-effective test, inspection, or demonstration can prove the finished system meets it. Avoid vague words like "fast," "user-friendly," or "robust," and use concrete metrics (e.g., "The search page must load within 1.5 seconds").

---

#### Q34: What is the purpose of the "System Overview" section in an SRS?
**Answer:**  
The System Overview section provides a high-level narrative describing the broad background, business goals, target user groups, operational context, and core system architectural assumptions before diving into technical requirement lists.

---

#### Q35: How are external interface requirements documented in an SRS?
**Answer:**  
They specify inputs, outputs, data formats, protocol requirements, error codes, and hardware linkages governing interaction with users (GUI), external hardware, third-party software, and network communication channels.

---

#### Q36: What is the difference between functional requirements written as natural language vs. structured specifications?
**Answer:**  
Natural language uses everyday prose, which can lead to misinterpretation. Structured specifications enforce standard templates (e.g., input/action/output tables or domain-specific languages) to improve clarity and standardization.

---

#### Q37: What is the role of the Data Dictionary in requirements specification?
**Answer:**  
A Data Dictionary defines all data structures, data attributes, field types, validation constraints, and allowed values across the system to maintain consistent data terms for developers and analysts.

---

#### Q38: Explain the term "Requirements Baseline."
**Answer:**  
A Requirements Baseline is an officially agreed-upon, reviewed set of requirements for a specific release version. Once baselined, any modification requires formal approval through a change control process.

---

#### Q39: Why should implementation details be avoided in an SRS document?
**Answer:**  
Including implementation details prematurely restricts system architects and developers from choosing optimal design patterns, database solutions, or programming frameworks, conflating the problem statement with solution choices.

---

#### Q40: What are "Non-Functional Quality Attributes" in an SRS?
**Answer:**  
Quality attributes define system performance operational boundaries, including:
- Reliability
- Availability
- Usability
- Maintainability
- Scalability
- Security
- Portability

---

#### Q41: Explain "Availability" as a non-functional requirement.
**Answer:**  
Availability measures the percentage of time a system remains operational and accessible during specified operational hours (e.g., "99.9% uptime per calendar month, excluding scheduled maintenance").

---

#### Q42: What is the significance of unique identifiers for requirements in an SRS?
**Answer:**  
Unique IDs (e.g., `REQ-SYS-001`) allow precise cross-referencing, mapping to test cases, tracking changes in issue logs, and establishing bidirectional traceability matrixes.

---

#### Q43: How do business rules differ from functional requirements?
**Answer:**  
Business rules state persistent organizational constraints or policies (e.g., "Discount rate cannot exceed 15% for new accounts"), whereas functional requirements specify how the software system enforces that rule in practice.

---

#### Q44: What is a System Requirements Document (SRD) compared to an SRS?
**Answer:**  
An SRD defines requirements for an entire system composed of hardware, software, and human operational procedures. An SRS focuses specifically on software components within that broader system.

---

#### Q45: Why is requirement completeness difficult to prove?
**Answer:**  
Completeness requires capturing all potential operational conditions, edge cases, system failure scenarios, and user paths. Proving that no omitted requirements remain is challenging until real-world testing and deployment occur.

---

## Module 4: Requirements Validation, Verification, & Management (Questions 46–60)

#### Q46: What is the difference between Requirements Validation and Requirements Verification?
**Answer:**  
- **Validation:** "Are we building the right system?" (Ensuring requirements meet real customer goals).
- **Verification:** "Are we building the system right?" (Ensuring the requirement document complies with standards and is clear, consistent, and well-structured).

---

#### Q47: Describe the Requirements Inspection / Review process.
**Answer:**  
Requirements Inspection is a structured review where a team of authors, domain experts, developers, and testers systematically read requirements documents line-by-line to find errors, ambiguities, inconsistencies, and omissions.

---

#### Q48: What is a Requirements Traceability Matrix (RTM)?
**Answer:**  
An RTM is a grid table mapping every requirement to its original business objective, design component, source code class, and verification test case, ensuring full lifecycle tracking and impact analysis.

---

#### Q49: What is Impact Analysis in requirements management?
**Answer:**  
Impact Analysis evaluates a proposed requirement change to determine affected system components, cost, schedule adjustments, technical risks, and regression testing effort before approval.

---

#### Q50: How does a Change Control Board (CCB) function?
**Answer:**  
A CCB is a formal group of stakeholders (project management, business analyst, technical leads, client reps) tasked with reviewing, evaluating, and approving or rejecting proposed changes to baselined requirements.

---

#### Q51: What is a "Requirement Anomaly" or conflict?
**Answer:**  
A requirement anomaly occurs when two or more requirements state contradictory system actions or expectations (e.g., REQ-1 mandates automated logoff in 5 minutes, while REQ-2 mandates continuous polling sessions without interruption).

---

#### Q52: What role do acceptance test cases play during requirements validation?
**Answer:**  
Drafting acceptance test cases directly from requirements helps validate whether a requirement is clear and testable. If a requirement cannot be translated into a test case, it is likely ambiguous or incomplete.

---

#### Q53: Explain "Requirements Churn."
**Answer:**  
Requirements Churn measures the rate at which requirements are added, modified, or deleted over time. High churn late in a project indicates unstable scope and risks delivery delays.

---

#### Q54: What is version control for requirements documents?
**Answer:**  
Version control tracks modifications, revision histories, author details, and change rationale for requirement documents, ensuring teams work from the current baselined release version.

---

#### Q55: How does a requirements management tool (e.g., Jira, DOORS) improve engineering workflows?
**Answer:**  
Requirements management tools centralize requirement storage, facilitate dynamic impact analysis, maintain automated traceability matrices, manage change requests, and provide real-time updates across development teams.

---

#### Q56: Why is prototyping considered a validation tool?
**Answer:**  
Prototypes allow stakeholders to visually experience and interact with proposed screen flows and workflows, helping them identify missing features, unworkable designs, or flawed logic before development.

---

#### Q57: What is a "Requirement Defect"?
**Answer:**  
A requirement defect is an error, omission, inconsistency, or ambiguity in a requirement specification that leads to incorrect software implementation if uncorrected.

---

#### Q58: Explain the term "Requirements Baseline Re-opening."
**Answer:**  
Re-opening a baseline occurs when critical business changes or technical blockers force stakeholders to revise previously locked requirements, triggering formal re-negotiation and timeline adjustments.

---

#### Q59: How do automated requirements checkers assist in requirements engineering?
**Answer:**  
Automated tools use natural language processing (NLP) to scan requirement text for ambiguous terms (e.g., "suitable," "appropriate," "fast"), passive voice, and unformatted entries, improving specification quality.

---

#### Q60: What is the relationship between requirements engineering and system testing?
**Answer:**  
Requirements serve as the baseline input for system and acceptance testing. Each requirement must correspond to test cases that verify whether the delivered software meets specified functional and non-functional targets.

---

## Module 5: Requirements Modeling & Agile Practices (Questions 61–75)

#### Q61: What is the role of UML (Unified Modeling Language) in requirements analysis?
**Answer:**  
UML provides standardized graphical notation (Use Case diagrams, Sequence diagrams, Activity diagrams, Class diagrams) to visualize, specify, construct, and document system workflows, data flows, and structural relationships.

---

#### Q62: What is an Activity Diagram, and when is it useful?
**Answer:**  
An Activity Diagram is a UML flowchart showing data flows and operational state transitions across a system. It is useful for modeling business processes, parallel processing, and conditional logic.

---

#### Q63: What does a UML Sequence Diagram illustrate?
**Answer:**  
A Sequence Diagram illustrates interaction objects arranged in time sequence, showing messaging exchanges between users, system components, and database objects to achieve a specific use case goal.

---

#### Q64: How are requirements handled differently in Agile vs. Waterfall methodologies?
**Answer:**  
- **Waterfall:** Requirements are fully documented, analyzed, and baselined before design and development begin.
- **Agile:** Requirements are captured iteratively as high-level user stories, prioritized within a dynamic Product Backlog, and refined continuously across short delivery sprints.

---

#### Q65: Explain the structure of a User Story and the concept of "INVEST."
**Answer:**  
A User Story follows: *"As a [role], I want [action] so that [benefit]"*.  
**INVEST** defines high-quality user story criteria:
- **I**ndependent
- **N**egotiable
- **V**aluable
- **E**stimable
- **S**mall
- **T**estable

---

#### Q66: What are Acceptance Criteria in user stories?
**Answer:**  
Acceptance Criteria are explicit conditions that a user story must satisfy to be considered complete ("Done"). They define functional conditions, boundary behaviors, and error paths verified during testing.

---

#### Q67: What is the "Product Backlog" in Scrum?
**Answer:**  
The Product Backlog is an ordered, prioritized list of desired user stories, functional enhancements, bug fixes, and non-functional requirements maintained by the Product Owner to guide development sprints.

---

#### Q68: What is "Backlog Refinement" or "Grooming"?
**Answer:**  
Backlog Refinement is a recurring Agile meeting where the Product Owner and development team review, clarify, split, estimate, and re-prioritize user stories to prepare them for upcoming sprint planning sessions.

---

#### Q69: Explain the concept of "Behavior-Driven Development" (BDD) in writing requirements.
**Answer:**  
BDD uses human-readable domain text using the **Given-When-Then** format (e.g., Gherkin language) to define system behavior:
- **Given** an initial context,
- **When** an event occurs,
- **Then** expect a specific outcome.

---

#### Q70: What is a "Spike" in Agile requirements management?
**Answer:**  
A Spike is a short, time-boxed research or technical exploration task undertaken by engineers to investigate unknown requirements, technical feasibility, or architecture choices before estimating a user story.

---

#### Q71: What is a Data Flow Diagram (DFD), and what are its key elements?
**Answer:**  
A DFD visually represents how data flows through a system. Its four primary elements are:
1. **External Entities** (sources/sinks)
2. **Processes** (data transformations)
3. **Data Stores** (databases/files)
4. **Data Flows** (arrows indicating data movement)

---

#### Q72: Explain the "3 Cs" of User Stories.
**Answer:**  
- **Card:** A brief written description of the story.
- **Conversation:** Ongoing discussion between users, product owners, and developers to clarify details.
- **Confirmation:** Acceptance criteria defining how the story will be tested and verified.

---

#### Q73: What is a Domain Model, and why is it created?
**Answer:**  
A Domain Model is a conceptual diagram depicting key real-world entities, attributes, and relationships within a problem domain, helping set unified domain language for technical and non-technical stakeholders.

---

#### Q74: What is the role of the Product Owner regarding software requirements?
**Answer:**  
The Product Owner owns the vision for the product, manages and prioritizes the product backlog, defines acceptance criteria, clarifies developer questions, and accepts or rejects completed user stories during sprints.

---

#### Q75: How do "Epic" user stories differ from regular user stories?
**Answer:**  
An **Epic** is a large, high-level user story representing a broad functional area that is too complex to complete in a single sprint. Epics are broken down into smaller, actionable user stories before planning.

---

## Module 6: UI Prototyping & Usability Engineering (Questions 76–85)

#### Q76: What is the purpose of prototyping in user interface (UI) requirements engineering?
**Answer:**  
Prototyping translates abstract user requirements into tangible, visual mockups, helping users clarify workflow expectations, identify missing functionality, and evaluate usability early in the design phase.

---

#### Q77: Compare Low-Fidelity (Lo-Fi) vs. High-Fidelity (Hi-Fi) prototypes.
**Answer:**  
- **Low-Fidelity:** Quick, low-cost paper sketches or wireframes focusing on structural layout and navigation flow without visual detail.
- **High-Fidelity:** Interactive, polished screen designs that closely mirror the final product's visual look, animations, and interaction behaviors.

---

#### Q78: What is Usability Testing, and how does it inform requirement changes?
**Answer:**  
Usability Testing evaluates a system prototype by observing representative users completing real tasks. Usability issues discovered (e.g., confused navigation, hidden actions) reveal flawed or missing usability requirements.

---

#### Q79: Explain Jakob Nielsen's 10 Usability Heuristics for UI design.
**Answer:**  
Nielsen's heuristics are principles for interaction design. Examples include:
- **Visibility of system status**
- **Match between system and real world**
- **User control and freedom**
- **Consistency and standards**
- **Error prevention**
- **Flexibility and efficiency of use**

---

#### Q80: What is a Wireframe?
**Answer:**  
A wireframe is a two-dimensional visual guide that outlines the page structure, layout, information hierarchy, and interface elements of a screen, deliberately omitting detailed colors, typography, and visual styling.

---

#### Q81: What is "Information Architecture" (IA) in UI requirements?
**Answer:**  
Information Architecture is the structural organization, labeling, and categorization of information within a digital system, ensuring users can navigate logically and find information efficiently.

---

#### Q82: How does accessibility (e.g., WCAG guidelines) influence non-functional UI requirements?
**Answer:**  
Accessibility standards dictate requirements ensuring systems are usable by individuals with vision, hearing, motor, or cognitive impairments. Examples include color contrast ratios, screen reader support, and full keyboard navigation.

---

#### Q83: What is "Paper Prototyping," and what are its advantages?
**Answer:**  
Paper prototyping involves sketching screen designs on paper and manually manipulating elements during user tests. It is fast, inexpensive, highly flexible, and encourages candid user feedback before writing code.

---

#### Q84: Distinguish between UI design and UX design.
**Answer:**  
- **UI (User Interface):** Focuses on visual touchpoints, visual hierarchy, components, screen layouts, and typography.
- **UX (User Experience):** Encompasses the overall feeling, usability, journey, efficiency, and satisfaction a user experiences when interacting with the system.

---

#### Q85: What is the "A/B Testing" technique in user requirement analysis?
**Answer:**  
A/B testing presents two variations of a feature or UI element (Option A vs. Option B) to live user groups simultaneously to collect empirical performance data, revealing which variant best achieves desired metrics.

---

## Module 7: Agentic AI Systems & Emerging RE Trends (Questions 86–100)

#### Q86: What is an "Agentic AI System," and how does it impact software requirements?
**Answer:**  
An Agentic AI System possesses autonomy to reason, plan, select tools, execute multi-step tasks, and adapt to changing environments without constant direct human intervention. Requirements for agentic systems must account for non-deterministic behaviors, safety boundaries, and dynamic task planning.

---

#### Q87: How do functional requirements for deterministic systems differ from non-deterministic agentic systems?
**Answer:**  
Deterministic software produces identical outputs for given inputs based on explicit code paths. Agentic software uses probabilistic reasoning, meaning requirements must define output quality bounds, acceptable confidence thresholds, and decision guardrails rather than static execution steps.

---

#### Q88: What is "Human-in-the-Loop" (HITL), and how is it specified as a requirement?
**Answer:**  
HITL is a requirement mechanism specifying that an AI agent must pause autonomous execution and seek human validation, review, or authorization before executing high-risk, irreversible, or high-value decisions.

---

#### Q89: What are "Guardrails" in AI requirements engineering?
**Answer:**  
Guardrails are safety constraints, operational boundaries, and validation checks embedded into an agentic system to prevent hazardous, unauthorized, off-topic, or unethical AI actions and responses.

---

#### Q90: How does AI prompt engineering relate to requirements engineering?
**Answer:**  
System prompts act as executable requirements specifications for AI agents, defining their core role, context, available tools, procedural constraints, and output formatting rules.

---

#### Q91: What is "Tool-Use / Function Calling" in AI agent requirements?
**Answer:**  
Tool-use requirements specify external APIs, database lookup routines, calculator modules, or file systems an agentic model is authorized to call autonomously to complete its objectives.

---

#### Q92: What are the main non-functional requirement challenges unique to AI agent systems?
**Answer:**  
Key non-functional challenges include:
- **Explainability/Interpretability** (understanding agent decisions)
- **Latency** (LLM inference delays)
- **Hallucination limits** (factual accuracy)
- **Cost control** (API token expenditure limits)
- **Safety/Alignment**

---

#### Q93: Define "Explainability" (XAI) as a requirement for autonomous software.
**Answer:**  
Explainability requires that an autonomous system provide human-understandable audit trails or rationales for its predictions, choices, and automated actions, especially in regulated fields like health, finance, and legal domains.

---

#### Q94: What is LLM-driven requirements generation, and what is its primary risk?
**Answer:**  
LLM-driven requirements generation uses Large Language Models to convert raw user feedback or business goals into structured SRS drafts or user stories. The primary risk is hallucinated, incomplete, or subtly contradictory requirements that pass initial inspection without expert validation.

---

#### Q95: How do software requirements address data privacy in AI agent workflows?
**Answer:**  
Privacy requirements mandate strict rules on personal identifiable information (PII) masking, data sanitization before third-party API calls, local data processing bounds, and user consent management under regulations like GDPR.

---

#### Q96: What is a "Fallback Mechanism" in an AI agent context?
**Answer:**  
A fallback mechanism is a functional requirement detailing recovery procedures (e.g., routing to a human customer service agent or defaulting to a conservative rule-based script) when an AI agent experiences low confidence, service timeouts, or repeated tool call failures.

---

#### Q97: What is "Multi-Agent System Specification"?
**Answer:**  
Multi-agent specifications define roles, task-handoff contracts, coordination protocols, shared state stores, and conflict-resolution rules across multiple autonomous AI agents working collaboratively to solve complex workflows.

---

#### Q98: How do you write testable requirements for non-deterministic AI outputs?
**Answer:**  
Testable requirements for non-deterministic AI define statistical acceptance criteria, performance benchmark metrics, target precision/recall rates, and maximum error thresholds across defined benchmark datasets (e.g., "Fact recall accuracy must exceed 95% on evaluation set X").

---

#### Q99: What is "Context Window Management" in agentic software engineering?
**Answer:**  
Context window management specifies functional logic for truncating, summarizing, or prioritizing history, tool schemas, and external memory artifacts passed to an LLM, ensuring reasoning stays within context boundaries and token budgets.

---

#### Q100: How does the role of a Requirements Engineer evolve with AI-driven development tools?
**Answer:**  
The Requirements Engineer transitions from manually authoring static text to curating domain models, defining evaluation benchmarks, refining AI prompt specifications, establishing safety guardrails, and verifying AI-generated specifications with stakeholders.