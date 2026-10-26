# Software Requirements: 100 Oral Exam & Discussion Questions

This question bank is structured across the core modules of your course: **Agentic Engineering & AI in Software Development**, **Spec-Driven Development & PRDs**, **Markdown Fundamentals**, **Usability Test Plans & Reports**, **Usability Testing Methods & Types**, and **UI Prototyping**. Each question is crafted to stimulate a focused 1-2 minute oral response.

---

## Module 1: Agentic Engineering & AI in Software Development (Questions 1–20)

1. According to JetBrains' 2026 survey, what percentage of professional developers regularly use AI coding tools at work?
2. What is the key functional difference between general-purpose chatbots (like ChatGPT) and specialized AI developer tools?
3. What are some of the primary reasons professional developers report adopting AI coding tools?
4. What did the METR study from early 2025 conclude regarding experienced open-source developers using AI tools?
5. How do company mandates—such as Meta's internal dashboard tracking daily AI usage—affect developer adoption?
6. What did Ryan Dahl (creator of NodeJS) mean when he asserted that "the era of humans writing code is over"?
7. Explain the significance of Stripe shipping over 1,000 AI-written pull requests per week into production.
8. Define "comprehension debt" and explain how it arises when using AI to produce software applications.
9. What is "verification debt," and why is it considered the technical debt of the AI era?
10. Why is industry consensus still lacking regarding the exact productivity impact of AI on software engineering?
11. Summarize the core takeaway from the Future of Software Engineering retreat regarding where engineering goes if AI handles the code.
12. How does the historical overhype of technologies (such as COBOL, SQL, and No-Code) compare to current AI tool adoption rates?
13. What psychological and emotional reactions (such as loss of identity) do developers experience during rapid technological shifts?
14. Why do acceptance criteria and unit tests become even more critical when AI generates code non-deterministically?
15. How can human-written acceptance criteria prevent AI from "cheating" when it writes its own unit tests?
16. Trace the evolution of AI coding tools from GitHub Copilot's initial inline autocomplete ("completions") to chat-based workflows.
17. Who coined the term "vibe coding," and what software development workflow does it describe?
18. What are the major criticisms, security risks, and failure modes associated with vibe coding?
19. Under what specific circumstances (e.g., MVPs or prototypes) can vibe coding be considered an effective approach?
20. Define "prompt engineering" and explain how requirements-writing principles apply to crafting effective AI prompts.

---

## Module 2: Spec-Driven Development (SDD), PRDs & Context Management (Questions 21–40)

21. What is "agentic engineering," and how does it differentiate itself from casual vibe coding through structure?
22. What is an AI agent in the context of modern software development tools like Claude Code or Cursor?
23. Compare Vibe Coding and Agentic Coding across approach, project type, and focus.
24. Explain the Total Cost of Ownership (TCO) economic comparison between vibe coding and agentic engineering regarding CapEx and OpEx.
25. What capabilities distinguish multi-file AI coding agents from basic conversational prompt interfaces?
26. What is Spec-Driven Development (SDD), and what serves as its primary software artifact?
27. Distinguish between spec-first development, spec-anchored development, and spec-as-source development.
28. How do SDD and Agentic Engineering complement each other in terms of "what/how" versus "who/where"?
29. What role do persistent Markdown files play in providing contextual instructions to AI agents?
30. What is a `CLAUDE.md` (or `AGENTS.md`) file, and what information does it typically contain for a project?
31. What is a Product Requirements Document (PRD), and who are its primary target stakeholders?
32. How does a PRD differ conceptually from a traditional Software Requirements Specification (SRS)?
33. What core sections are typically included in a comprehensive PRD for agentic development?
34. Why is it vital to keep ambiguity explicitly visible as "open questions" in a PRD when working with AI?
35. What is the role of Human-in-the-Loop authority versus Agent autonomy in executing development tasks?
36. Outline the six types of agent context in Addy Osmani's framework (instructions, knowledge, memory, examples, tools, guardrails).
37. Contrast static context (always loaded) with dynamic context (loaded on demand) in AI architectures.
38. What are the primary trade-offs associated with increasing the volume of context provided to an AI model?
39. What security threats, such as prompt injection, arise when AI agents dynamically read external online sources?
40. What is the purpose of the Model Context Protocol (MCP) introduced by Anthropic?

---

## Module 3: Markdown Fundamentals (Questions 41–55)

41. What is Markdown, and what is the fundamental difference between plaintext (UTF-8/ASCII) and binary files?
42. Why has Markdown become an industry standard for READMEs, user stories, ADRs, and AI inputs?
43. How do you create heading levels 1 through 6 in Markdown?
44. How do you properly format paragraphs and forced line breaks in Markdown?
45. How do you apply bold, italics, and combined bold-italics text formatting in Markdown?
46. How do you write a multi-paragraph blockquote in Markdown?
47. How do you construct ordered lists and unordered lists, and can list items be nested?
48. How do you insert an image with alternative text using standard Markdown syntax?
49. How do you write inline code snippets versus multi-line fenced code blocks in Markdown?
50. How do you create standard hyperlinks and hyperlinks with hover tooltips in Markdown?
51. How do you create simple clickable links using angle brackets in Markdown?
52. How do you construct structured data tables using pipe characters (`|`) in Markdown?
53. What is the purpose of the backslash (`\`) escape character in Markdown?
54. What is GitHub-Flavored Markdown (GFM), and how does it extend standard CommonMark?
55. Why is Markdown particularly well-suited as an instruction and context format for LLMs and AI coding tools?

---

## Module 4: Usability Test Plans & Reports (Questions 56–75)

56. What is a usability test plan, and why is documenting test procedures beforehand critical?
57. What key information should be documented under the "Scope" section of a test plan?
58. What is the difference between general goals and specific goals in usability testing?
59. How do schedule and location decisions influence the realism and logistics of a usability test?
60. What is the difference between moderated (synchronous) and unmoderated (asynchronous) testing formats?
61. Why is recruiting participants who accurately match your target user demographic essential?
62. What equipment and recording setup considerations must be specified in a test plan?
63. What distinct roles can team members (facilitator, notetaker, observer) play during a test session?
64. Describe the typical order of activities and overall duration of a usability test session.
65. What is the difference between exploratory tasks and specific tasks in usability scenarios?
66. Why are task scenarios better written with specific context (e.g., "find book X") rather than general commands?
67. What quantitative performance metrics are commonly measured during usability testing?
68. How can application event logging supplement stopwatch tracking and manual note-taking?
69. How do you measure subjective satisfaction and user thoughts that lack straightforward numerical quantification?
70. What is the System Usability Scale (SUS), and how are its 10 Likert-scale questions scored?
71. When should pre-test and post-test surveys be administered during a usability testing session?
72. What are the trade-offs between gathering data via anonymous surveys versus live interviews?
73. What guidelines should an interviewer follow to encourage open dialog without leading the participant?
74. What core sections should be included in a formal Usability Test Report?
75. How are usability issues categorized by severity (e.g., from cosmetic problems to usability catastrophes)?

---

## Module 5: Usability Testing Methods & Types (Questions 76–90)

76. Define usability testing and explain why having real users perform actual tasks is non-negotiable.
77. What are the main benefits of conducting usability testing throughout various software development stages?
78. How do sketch, wireframe, and mockup usability tests differ from testing a fully implemented application?
79. What is "discount usability testing," and why is testing with only 5 users widely accepted in industry?
80. What are the primary academic criticisms and counter-arguments regarding testing with only 5 users?
81. What is competitive usability testing, and what distinguishes within-subject from between-subject designs?
82. What is A/B testing, and how do large technology companies utilize it at scale?
83. What are the advantages and disadvantages of remote usability testing compared to in-person lab testing?
84. Describe field testing and explain when it is most appropriate for evaluating software.
85. What is "can-you-break-this" testing, and in which domains is it most frequently applied?
86. Contrast formal lab testing (with observation rooms and two-way mirrors) with guerilla testing in public spaces.
87. What is the difference between Concurrent Think-Aloud (CTA) and Retrospective Think-Aloud (RTA)?
88. What is the difference between concurrent and retrospective probing, and how does probing affect performance metrics?
89. How can eye-tracking software and thermal heat maps be utilized in usability analysis?
90. What are first-click testing and 5-second testing, and what specific insights do they provide?

---

## Module 6: UI Prototyping (Questions 91–100)

91. What are sketches in UI prototyping, and what are their primary advantages (e.g., zero barrier to entry)?
92. How can interactivity and screen transitions be simulated using low-fidelity sketches or whiteboards?
93. What is a wireframe, and how does it differ from a sketch in terms of precision, tools, and layout representation?
94. Why do low-fidelity prototypes often elicit more honest and critical feedback from users than polished high-fidelity ones?
95. What are mockups, and what visual elements do they include that wireframes typically omit?
96. Can mockups be clicked and interacted with like a working application? Explain their static nature.
97. What software tools are typically used to create wireframes and mockups?
98. Where do interactive prototypes sit on the fidelity and interactivity spectrum?
99. Map out the complete UI prototyping fidelity progression from initial sketches to production-ready prototypes.
100. How do iterative UI prototyping methods allow development teams to refine software requirements over time?

```eof

---

### Summary & Encouragement
I have successfully generated a comprehensive question bank of **100 oral exam and discussion questions** spanning all five modules of your software requirements course (Agentic Engineering, Markdown, Usability Test Plans, Usability Testing, and UI Prototyping). Each question is tailored for a quick 1-2 minute oral response. 

Good luck with your course review and preparation! You've got this!