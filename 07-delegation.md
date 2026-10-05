## Capabilities & Limitations

- Think of an LLM like **a new colleague**: knowing their **strengths and limitations** helps you collaborate more effectively.

### What LLMs Do Well
- **Language skills:** crafting emails in your voice, **summarizing** lengthy reports, **translating**, and **explaining complex topics** across many fields.
- **Versatility:** the same system can shift between tasks (*poetry, brainstorming, quantum computing, business analysis*) **without additional training**, all through simple conversation.
- **Conversation continuity:** can *maintain the thread* of a conversation, remember what you said earlier, and **build on it**.
- **External tools:** many modern LLMs can **search the web, process files, and use other applications**, which *dramatically expands what they can help with*.

### Limitations
- **Bounded by training data**
  - Every model has a **knowledge cutoff date**, after which it has *no innate knowledge* of the world (like someone on a **retreat without internet access**).
  - Tools like **web search** are needed for recent developments.
- **Hallucinations**
  - Training **doesn't verify every fact**, so models can reproduce inaccuracies or make mistakes piecing information together.
  - A **hallucination** is AI *confidently stating something plausible but incorrect*, like a friend telling a story with **absolute confidence but the details wrong**.
  - Unlike search engines that **retrieve** documents, LLMs **generate** responses from *statistical patterns*.
- **Context window**
  - There is a **maximum amount of information** the AI can consider in a single interaction.
  - If exceeded, information outside the window is forgotten, usually **first-in, first-out**.
  - This can limit **large documents** and **long conversations**.
- **Non-deterministic**
  - Unlike traditional software, the **same question can produce slightly different answers** each time, because the model makes **probabilistic decisions** about what comes next.
  - Great for **brainstorming and diverse ideas**, but needs awareness when **consistency or accuracy** matter.
  - Some interfaces offer a setting to control randomness, often called **temperature**.
- **Complex reasoning**
  - Historically weaker at **multi-step math and logic** problems.
  - Newer **reasoning / extended thinking models** that *think step by step* are showing strong progress.
- **Limited access to data and tools**
  - Like *a brilliant colleague who can't access your company's internal database*, a model **can't help with what it can't access**, no matter how smart it is.

### Where Things Are Heading
- Researchers are addressing limitations through **retrieval-augmented generation (RAG)** (connecting models to **external knowledge and data sources**), **expanded tool use**, and **improved reasoning**.
- Some limitations will likely **remain for the foreseeable future**, even if we don't know exactly which ones.

### Humans + AI: Complementary Strengths
- **Humans bring:** **critical thinking, judgment, creativity, and ethical oversight**.
- **AI brings:** **speed, scale, pattern recognition**, and the ability to **process vast amounts of information**.
- These strengths will **evolve with the technology**, so **continued learning and experimentation** matter for staying current and *discovering new possibilities*.
- Understanding what AI can and can't do is **essential for AI fluency**: it helps you decide **when and how** to bring AI into your work and daily life.

### Key Takeaways

- **Generative AI** creates **new content** (*text, images, code*) rather than just analyzing existing data
- Modern systems like **LLMs** were made possible by **three key developments**:
  - **Algorithmic and architectural breakthroughs** (especially the **transformer architecture**)
  - **Vast amounts of digital training data**
  - **Dramatic increases in computational power**
- Generative AI learns through **two stages**: **pre-training** (*analyzing patterns across billions of examples*) and **fine-tuning** (*learning to follow instructions and provide helpful responses*)
- **Current capabilities** include **versatility across tasks**, **conversational awareness**, and the ability to **connect with external tools**
- **Current limitations** include **knowledge cutoff dates**, potential for **hallucinations**, **context window constraints**, and challenges with **complex reasoning**
- The most effective applications **combine human and AI strengths**, with humans providing **critical thinking, judgment, creativity, and ethical oversight**

## Reflection

### How does understanding the technical foundations change how I work with these systems?
- **It changes my expectations.** Because the model *predicts what comes next* from patterns learned in training, I see it as a system that **generates plausible text**, not one that looks up **guaranteed facts**.
- **I verify more.** Since training doesn't check every fact, I **double-check important claims**, especially numbers, sources, and technical details.
- **I give better context.** Knowing about the **context window** and **in-context learning**, I put the *instructions, examples, and background* directly in my prompt.
- **I use tools when needed.** The **knowledge cutoff** reminds me to use **web search or uploaded documents** for recent or specialized information.
- **I expect variation.** Because outputs are **non-deterministic**, I treat the first answer as a **draft** and *iterate*.
- **I understand fine-tuning's role.** It explains why the AI follows instructions and tries to be **helpful, honest, and harmless**, but that doesn't make it *infallible*.

### What ethical considerations come to mind?
- **Accuracy and misinformation:** hallucinations can spread **confident but false information** if no one checks.
- **Bias:** models learn from **human-written data**, so they can *reflect and amplify existing biases*. This matters for **hiring, lending, and other decisions about people**.
- **Privacy:** anything I put in a prompt may be **sensitive**, so I should avoid sharing **personal or confidential data** unless I understand how it's handled.
- **Transparency:** I should be **open about AI's role** in my work rather than passing it off as entirely my own.
- **Accountability:** the **human stays responsible** for final decisions and outputs. *"The AI said so"* is not a defense.
- **Over-reliance:** leaning too heavily on AI can weaken my **own judgment and skills**, so I need to keep **thinking critically**.
- **Fair use of data:** the **training data** raises questions about *consent, copyright, and credit* for the original creators.
