---
title: "Event 1"
date: 2026-05-23
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# EVENT REPORT: TASK AUTOMATION WITH AMAZON Q AI ASSISTANT AND MCP

### I. Objectives & General Context
Through the technology events (focusing on Amazon Q, the MCP protocol, and the FCAJ Community Conference), I had the opportunity to access a comprehensive overview of how AI is reshaping the corporate environment. The content went beyond the surface level of generative AI tools, delving into system architecture, product-driven mindset, and the stringent security barriers encountered during practical deployment.

### II. Technological & Technical Highlights

### 1. From Single Agent to Multi-Agent Architecture
Current LLMs are highly intelligent, but a single Agent is limited by its Context Window and is easily overwhelmed by complex problems.

The optimal solution is to build a Multi-Agent system (such as a Credit Council model), dividing it into specialized Agents (Financial Analysis, Risk Assessment, Orchestration, etc.). This division enables the system to process tasks in parallel and possess cross-validation capabilities.

### 2. MCP and Execution Capability (Action)
Core formula: Agent = LLM + Action/Function (MCP).

The Model Context Protocol (MCP) serves as the technical bridge that allows AI to transcend conventional Q&A boundaries, connecting directly with external applications (Jira, Gmail, Teams) to automate raw processes (such as data visualization and sending task assignment emails after meetings).

### 3. Context Engineering
"Injecting" knowledge into AI is not about cramming hundreds of raw PDF pages. Instead, it requires extracting business "essentials" from experts (Knowledge Transfer) to create standard contexts. This helps LLMs process information accurately and minimizes unpredictability (Hallucination/Inference optimization).

### III. Business Mindset & Enterprise Operations (Enterprise-grade AI)

### 1. Solving Problems with ROI (Return on Investment)
Technology is merely a tool. Any AI solution (even those costing billions of VND) must answer: Who does it serve? Why use it? And what is the return on investment?

"Numbers speak louder than words" - Every technological proposal presented to management must be proven by actual figures regarding the payback period rather than empty promises.

### 2. Security and Responsibility (Audit & Compliance)
In the corporate environment (especially in finance), security is paramount. The integration of peripheral tools must be strictly controlled.

The system needs to establish Guardrails to check Input/Output to prevent Prompt Injection and strictly manage the API Key lifecycle.

Humans are the ultimate gatekeepers: No matter how autonomous AI becomes, the engineer and the system approver remain legally responsible for the decisions made (such as approving loans).

### IV. Application Orientation and Personal Lessons
* **Solidifying the Software Engineering foundation:** AI cannot replace core knowledge (Backend, Database, Cloud Infrastructure, Security). This remains the deciding factor in taking a project from a "home demo" to a real Production environment in a bank or enterprise.
* **Understanding Stakeholders:** It is necessary to clearly grasp the KPIs of other departments (Business, Security) to communicate, request permissions, and coordinate teamwork more smoothly.
* **Practicing Automation:** Apply Amazon Q and customize MCP Servers to automate personal workflows. When designing systems, I will prioritize breaking down logic towards a Multi-Agent approach for complex tasks.

### V. Practical Experience & Perspectives at the Event
The practical sharing sessions from speakers (like Mr. Hai An, Ms. Cat Vy...) truly broadened my mindset regarding the gap between theory and the practical deployment of "Enterprise-grade AI". Witnessing firsthand the automated processing flow of Amazon Q or analyzing the credit assessment architecture for Startups helped me realize the strictness, discipline, and heavy responsibility of a modern software engineer. The event was also a fantastic opportunity to network and learn from experienced predecessors.

In general, the event series not only provided deep technical foundations but also completely shifted my mindset: from merely focusing on writing code to designing safe, reliable automated solutions that deliver truly measurable value to the enterprise.

![Event Participation Image](/images/4-EventParticipated/event_1.jpg)