## Effective Prompting Techniques

- **Prompting** is how we **apply the Description competency in practice**: clearly communicating *what we want, how we want it done, and how we want to interact* with the AI throughout the process.
- Think of it like **explaining a task to a helpful new colleague** who is eager to assist but needs **clear directions and expectations**.
- **Prompt engineering** is the practice of **designing effective instructions** for AI systems.
  - It blends **familiar human communication skills** (*being clear, giving context, using concrete examples*) with **AI-specific considerations**.
  - Differences: be **more explicit** about things humans would infer, **accommodate the limited context window**, and sometimes use **specific formatting** machines process easily.
  - Best practices **evolve with the technology**, so **experimentation is key**.

### Six Foundational Prompting Techniques

#### 1. Give Context
- Be specific about **what you want, why you want it, and who you are**.
- Vague: *"Tell me about climate change."* Better: *"Explain three major impacts of climate change on agriculture in tropical regions, with examples from the past decade."*
- Add **why you're asking and how you'll use the answer**, such as preparing for a *job interview at an agricultural research lab*, with *your background and knowledge level*.
- We naturally give background in human conversations but **forget to include it with AI**.

#### 2. Show Examples
- **Few-shot / n-shot prompting:** show the AI examples to emulate (*n* = number of examples).
- **Try without examples first.** Use them when a **specific style is easier to show than explain**.
- Cover the **full diversity** of cases or styles so the AI understands the *range of the pattern*.

#### 3. Specify Output Constraints
- Define the **format, length, language, and design details** of what you want.
- Example: a portfolio website with **named sections, a sticky responsive menu, a sunset color palette, and a dark/light toggle**.
- Clear guidance helps the AI **structure its response to match your expectations**.

#### 4. Break Complex Tasks into Steps
- **Chain-of-thought prompting:** list the steps so the AI **follows the process you want**.
- Example: instead of *"analyze this quarterly sales data,"* ask it to **find top products, compare to last quarter, highlight unusual trends, then suggest reasons**.
- Often **not needed for straightforward tasks**, and **reasoning models** can do this on their own.
- The more **variance in how to do the task well**, or the more it depends on **your domain expertise**, the more worth it it is to *translate that knowledge to the AI*.

#### 5. Ask the AI to Think First
- Give the AI **space to work through its process before executing** the task.
- Example: *"Before answering, think through this carefully. Consider the factors, constraints, and approaches before recommending the best solution."*
- Thinking must come **before the task, not after**, to improve the work.
- Side benefit: you can **see where the AI is going astray** and *refine your description*.
- **Reasoning / extended thinking models** do this by default.

#### 6. Define the AI's Role, Style, or Tone
- Specify the **level of expertise, perspective, or communication style**: *who should the AI act as?*
- Examples: an **experienced science teacher** explaining to a **bright 10-year-old**, or a **UX design expert** reviewing a wireframe.
- Useful for **brainstorming and getting feedback**.

### The "Secret Weapon"
- **Ask the AI to help improve your prompt**, or to write it for you.
- Describe your goal and say you're *not sure how to phrase it*.
- AI assistants **vary most here**, so *experiment with different models* as part of practicing delegation.

### Iterate and Refine
- Prompting is **iterative and experimental**. Your first attempt won't always be perfect, and that's expected.
- If a response misses, try:
  - Adding **more specificity or context**
  - Providing **examples** of the desired output
  - **Breaking the task** into smaller steps
  - Trying a **different technique or combination**
  - Asking for **variations** (*"give me three versions"*)
  - Requesting **different formats** (*e.g., an interactive artifact*)
  - **Checking confidence:** *"How confident are you about this answer?"*
  - **Starting a fresh conversation** if it has gone off track
- Use **each interaction as feedback** to build intuition over time.

### Patterns and Mistakes
- **Patterns that work:**
  - A clear **task overview statement**
  - **Format specifications and examples**
  - **Explicit constraints or requirements**
  - **Rich, relevant background information**
- **Mistakes to avoid:**
  - **Assuming the AI can read your mind**
  - **Overloading** one prompt or conversation with *multiple unrelated tasks*
  - Being **too vague about what success looks like**
  - **Not giving feedback** on previous responses

### Recap
- Effective prompting combines **timeless human communication principles** with **AI-specific techniques** that transfer across AI systems.
- Techniques may become **less necessary as models improve**, but the **principles of good communication still apply**.
- Stay **experimental** and adapt based on results.

### Key Takeaways

- Effective prompting combines **clear communication principles** with **AI-specific techniques**.
- **Six foundational techniques:**
  - **Give context:** be specific about *what you want, why, and relevant background*
  - **Show examples:** demonstrate the *output style or format*
  - **Specify constraints:** define *format, length, and other requirements*
  - **Break complex tasks into steps:** guide *multi-step reasoning*
  - **Ask the AI to think first:** give *space to work through its process*
  - **Define the AI's role or tone:** specify *how it should communicate*
- The **"secret weapon":** *ask the AI itself* to help improve your prompt.
- Successful prompting is **iterative** (and perhaps also **collaborative with the AI**). Expect to refine based on results.
- Common successful patterns: **clear task overviews, format specifications, explicit constraints, and relevant background**.

## Reflection

### Which of the six techniques would most enhance my current AI interactions?
- **Give context.** I often state the task but skip **why I need it, who the audience is, and my own background**. Adding those would cut down on *guessing* and *correction rounds*.
- **Specify constraints** is a close second. Stating the **format, length, and tools or language** up front saves time, especially on *code and documentation*.
- **Ask the AI to improve my prompt** is an easy habit to add whenever I'm unsure how to phrase something.

### Which techniques might have improved a recent interaction that missed my needs?
- The output didn't fit because the AI had to **guess** at details I never gave it.
- **Context** would have told it *who I am, why I needed it, and how I'd use the result*.
- **Constraints** would have set the *format and length*.
- **Examples** would have shown the *style* I had in mind.
- **Breaking the task into steps** would have kept it from going off in a different direction.
- Next time I'd also **give feedback** on the first response instead of starting over.

### How does this connect to the Description competency?
- Prompting is **Description put into practice**.
- **Context, examples, and constraints** map to **product description** (*what I want*).
- **Breaking tasks into steps** and **asking the AI to think first** map to **process description** (*how the AI should approach it*).
- **Defining role, style, or tone** maps to **performance description** (*how the AI should behave*).
- The **iteration and feedback** loop is how Description improves over time.
