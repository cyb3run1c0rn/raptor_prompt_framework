# 🦅 RAPTOR Prompt Engineering Framework

**Version:** 1.0
**Author:** RAPTOR TRUST
**Licence:** CC BY-NC 4.0  
**Last Updated:** 23/03/2025  

---

## 🚀 Executive Summary

The **RAPTOR Prompt Engineering Framework** provides a systematic yet flexible approach to crafting effective AI prompts. By offering clarity, structure, and consistency, it is suited to technical, professional, and high-stakes environments.  

**RAPTOR** stands for:  
- **Role** – Define the AI’s persona  
- **Aim** – Set a clear task  
- **Parameters** – Establish scope and constraints  
- **Tone** – Determine communication style  
- **Output** – Specify the response format  
- **Review** – Enable iteration or refinement  

Used either on its own or as a *meta prompt*, RAPTOR can help generate well-structured, focused prompts in any field.

Use (copy and paste) the meta prompt into your favourite chat LLM, then add your amazing idea, and detail what you want exactly, then run the AI.

Copy and paste its output as a new prompt to profit.

---

## 🧠 Role

Assigning a persona (and any relevant background or domain context) to the AI helps shape its knowledge, behaviour, and manner of response.

- **Recommended Detail**:  
  - Describe the AI’s specialised knowledge or function (e.g., “You are a market analyst specialising in fintech”).  
  - Add contextual references here if they inform how the AI should respond (e.g., relevant policies, organisational culture).

**Example:**  
> "You are a senior cybersecurity analyst with expertise in OT systems and incident response. Consider internal compliance policies when providing guidance."

---

## 🎯 Aim

Clearly define the *primary* goal or task for the AI. State what outcome you want it to achieve, without overloading this section with constraints.

- **Recommended Detail**:  
  - Keep the core objective concise (e.g., "Draft a threat report on emerging malware families").  
  - Additional conditions or resources belong under **Parameters**.

**Example:**  
> "Analyse the key threats to critical infrastructure posed by emerging OT malware families in 2024."

---

## 📐 Parameters

List constraints, resources, and contextual details that the AI must factor in. This includes references to data sources, regulatory requirements, or time frames.

- **Recommended Detail**:  
  - Specify what resources or boundaries apply (e.g., “Use official advisories only,” “Avoid generic ransomware”).  
  - Include relevant context that influences scope—such as target audience, domain restrictions, or relevant standards.

**Example:**  
> "Focus on advisories from government agencies and known vendors since January 2024. Exclude generic ransomware. Comply with any internal reporting templates."

---

## 🎙️ Tone

Determine how the AI should communicate. Indicate the style, formality, or any language requirements.

- **Recommended Detail**:  
  - Choose whether the tone should be formal, casual, persuasive, or instructional.  
  - Specify language conventions (e.g., British English) or level of technicality.

**Example:**  
> "Use a formal and concise tone suitable for executive-level reporting. Write in British English."

---

## 🗂️ Output

Instruct the AI about the exact structure or format you expect. Mention any specific deliverables or output style.

- **Recommended Detail**:  
  - State whether you want bullet points, code, diagrams, or a specific file format.  
  - If multiple outputs are needed, list each clearly.

**Example:**  
> "Provide the analysis in four sections: (1) Key Vulnerabilities, (2) Attack Vectors, (3) Impact Assessment, (4) Mitigation Strategies."

---

## 🔍 Review

Reserve space to refine and iterate on your prompt. Encourage the AI (and yourself) to check assumptions, fill information gaps, or adjust based on feedback.

- **Checklist Guidance**:
  1. **Clarity**: Is the Aim clearly stated?  
  2. **Consistency**: Do Parameters align with the Aim?  
  3. **Compliance**: Have any legal or policy constraints been respected?  
  4. **Completeness**: Is there enough context for the AI to proceed confidently?  
  5. **Feasibility**: Are the requested outputs realistic within the stated scope?

**Example:**  
> "If you require any assumptions, state them. Ask for clarification if data sources or constraints are missing. Double-check all sections before finalising."

---

## 🧩 Use Cases

- Executive briefings  
- Technical risk assessments  
- Educational resources  
- Strategic planning with LLMs  
- Prompt libraries for consulting or SaaS  

---

## 📊 Comparison with Other Methods

| Feature               | RAPTOR ✅ | Chain-of-Thought ❌ | ReAct ❌ | APE ✅ |
|-----------------------|-----------|----------------------|----------|--------|
| Role Definition       | ✅        | ❌                   | ❌       | ✅     |
| Goal Clarification    | ✅        | ❌                   | ✅       | ✅     |
| Scope/Constraints     | ✅        | ❌                   | ✅       | ✅     |
| Tone & Style Control  | ✅        | ❌                   | ❌       | ❌     |
| Output Formatting     | ✅        | ❌                   | ❌       | ❌     |
| Encourages Review     | ✅        | ❌                   | ✅       | ❌     |

---

## 🛠️ Use the RAPTOR Meta Prompt Generator

Looking to go from **idea → prompt** to **idea → working product**?

Use the **RAPTOR Meta Prompt Generator** to get a fully scoped, well-structured, and production-ready prompt.

### 🧾 Meta Prompt Template:

> Help me generate a complete and production-ready AI prompt using the RAPTOR framework:
> - Role – Define the AI’s persona.
> - Aim – Set a clear task.
> - Parameters – Establish scope and constraints.
> - Tone – Determine communication style.
> - Output – Specify the response format.
> - Review – Enable iteration or refinement.
>
> I’ll describe my goal briefly—please expand it into a full RAPTOR prompt that will guide the AI to build the actual end product (e.g. a functional application, tool, or system).  
>
> My idea or task: **[INSERT YOUR IDEA HERE]**

---

### 💡 **Example Input 1.** (Technical Application)

> My idea or task:  
> **Build a fully working web app that tracks Cardano blockchain activity and visualises key indicators to aid gaming-based trading decisions. The final output should include source code, HTML/CSS/JS or Python (Flask), and setup instructions. The solution must be deployable by a non-technical user.**

### 🔄 **Example Output Prompt (Generated by the Meta Prompt)**

> **Role:** You are a full-stack blockchain web developer with experience in creating crypto dashboards.  
>
> **Aim:** Build a fully functional web application that visualises real-time Cardano blockchain metrics to support strategy decisions in gaming-related trading.  
>
> **Parameters:** Use publicly available data or mock data where API access is not feasible. The app should include a dashboard interface, charts for key metrics (wallet activity, volume, NFT trades), and be deployable locally via Flask or Node.js. A database is not required. The front end must be user-friendly.  
>
> **Tone:** Developer-friendly, with commented code and language accessible to a junior developer or tech-savvy trader.  
>
> **Output:** Provide fully working code for a Flask-based (or Node.js-based) web app, including:  
> 1. Setup instructions  
> 2. Front-end code (HTML/CSS/JS or React)  
> 3. Back-end logic for data retrieval/processing  
> 4. Visualisation elements (e.g., Chart.js, D3)  
> 5. Notes on future API integration  
>
> **Review:** If assumptions are unclear (e.g., specific Cardano metrics, UI design), ask before proceeding. Check if a database or a particular deployment platform (Heroku, Docker, etc.) is needed.

🔥 **Result:**  
A clear, reproducible prompt that guides an AI assistant to produce a functioning MVP, complete with code.

---

### 💡 **Example Input 2.** (Non-Technical, Monetised Product)

> My idea or task:  
> **Create a complete downloadable product called “The Freelancer’s Proposal Pack” — a toolkit for freelance designers, writers, and developers that includes templates, pricing strategies, objection-handling scripts, and email outreach sequences. The final output should be prepared for sale on Gumroad or a similar platform.**

### 🔄 **Example Output Prompt (Generated by the Meta Prompt)**

> **Role:** You are a creative business consultant and digital product strategist experienced in helping freelancers package their services.  
>
> **Aim:** Develop a monetisable digital product called “The Freelancer’s Proposal Pack” that provides ready-to-use templates and guidance for pitching, pricing, and closing deals.  
>
> **Parameters:** The pack should cater to freelance creatives (designers, writers, developers). Avoid large-agency strategies; focus on individuals or new freelancers. The content must be editable (Google Docs or Notion). Ensure it’s comprehensive enough to sell standalone or bundle with a course.  
>
> **Tone:** Practical, friendly, and encouraging. Address freelancers who aim to appear professional and protect their time without sounding too corporate.  
>
> **Output:** Produce the complete digital product, including:  
> 1. 3–5 proposal templates with sample pricing  
> 2. Email scripts for cold outreach, warm leads, and project follow-up  
> 3. A concise pricing guide with value-based strategies  
> 4. An objection-handling cheat sheet (FAQ style)  
> 5. A branded proposal document (editable in Google Docs or Notion)  
> 6. A short PDF explaining how to use the pack  
>
> **Review:** Confirm if the pack targets a specific niche (e.g. design, tech, writing). Ask whether a simple style guide is required. Check if a lead magnet for email list building is desired.

🛍️ **Result:**  
A comprehensive prompt that directs an AI assistant to generate a ready-to-sell digital toolkit, ideal for platforms like Gumroad or Etsy.

---

## 📄 Licence

This work is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.  
For commercial usage, please contact the author to arrange a commercial licence.

---

## 🤝 Contributions & Community

Community input is warmly encouraged. Submit issues or pull requests to help refine and expand the framework.

**GitHub:** [https://github.com/cyb3run1c0rn/raptor_prompt_framework/](https://github.com/cyb3run1c0rn/raptor_prompt_framework/)  
**Contact:** TBC
