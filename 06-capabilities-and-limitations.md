## How Generative AI Works

### What Is Generative AI?
- **Generative AI** is AI that **creates new content** rather than just analyzing existing data.
  - Traditional AI: *analyzes and categorizes* (e.g., classifies an email as spam or not).
  - Generative AI: *creates something new* (e.g., writes a completely new email).
- **Large language models (LLMs)**, like Anthropic's **Claude**, are a prominent type of generative AI.
  - **Language:** trained to *predict and generate human language*.
  - **Large:** contain **billions of parameters**, mathematical values that determine how the model processes information (*somewhat like synaptic connections in the brain*).

### Three Developments That Made It Possible
- **Algorithmic and architectural breakthroughs:** the **transformer architecture (2017)** was a game changer. It processes **sequences of text** while keeping **relationships between words across long passages**, which is critical for understanding *language in context*.
- **Explosion of digital data:** the raw material for training, drawn from **websites, code repositories, and other texts**, giving models a *broad and nuanced understanding* of language and concepts.
- **Massive increases in computing power:** **GPUs**, **TPUs**, and **distributed computing clusters** made training possible that *would have been impossible just a few years earlier*.

### Scaling Laws and Emergent Capabilities
- **Scaling laws:** as models get **larger** and train on **more data with more computing power**, performance improves in **predictable ways**.
- **Emergent capabilities:** new abilities appear at scale that *no one explicitly programmed*, like **reasoning step by step** or **adapting to new tasks with minimal instruction**.

### How These Systems Work
- **Pre-training:** the model analyzes patterns across **billions of text examples**, building a *complex map of language and knowledge*.
  - It is shown text and asked to **predict what comes next**, then gradually refines its predictions.
- **Fine-tuning:** the model learns to **follow instructions**, give **helpful responses**, and **avoid harmful content**.
  - Uses **human feedback** and **reinforcement learning** (*rewards and penalties*).
  - Anthropic's goal: models that are **helpful, honest, and harmless**.
- **Deployment and prompts:** you give the model a **prompt**, and it *continues from it based on learned patterns*.
  - It is **not retrieving pre-written answers** from a database. It *generates new text that statistically follows from what you've written*.
- **Context window:** the limit on how much information the AI can consider at once, like its **working memory**.
  - Includes **your prompts, AI responses, and any other information shared** in the conversation.
  - The AI **cannot use content beyond its context window** without specialized tools like **web search**.

### Why Modern Generative AI Is Powerful
- **Learning from vast amounts of information** during training, which captures *complex and nuanced patterns*.
- **In-context learning:** adapts to new tasks from **instructions or examples in your prompt**, *without additional training*.
- **Emergent capabilities** that arise from scale, *sometimes surprising even their creators*.
