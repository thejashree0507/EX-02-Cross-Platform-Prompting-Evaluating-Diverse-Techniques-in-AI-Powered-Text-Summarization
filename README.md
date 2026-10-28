# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

#### Step 1: Define Prompt Types

Identify and prepare four types of prompts:

1. **Zero-Shot Prompt** – Direct question without examples.
   *e.g., "Summarize the article on 'The Basics of Blockchain Technology' in simple terms."*

2. **Few-Shot Prompt** – Includes example outputs to guide the model's response style.
   *e.g., "Using the tech summaries as examples, briefly explain..."*

3. **Chain-of-Thought Prompt** – Uses stepwise reasoning cues.
   *e.g., "What is blockchain? How does it work? Where is it used?"*

4. **Role-Based Prompt** – Assigns a role or persona to the model.
   *e.g., "Explain as if you are a professor teaching first-year students."*

#### Step 2: Choose LLM Tools

Select the tools/models for evaluation:

* **Tool A:** ChatGPT (OpenAI)
* **Tool B:** Gemini (Google)

#### Step 3: Apply Prompts

For each prompt type:

1. Input the same prompt to both tools.
2. Record the output from **ChatGPT** and **Gemini**.

#### Step 4: Compare Outputs

Analyze responses based on:

* Simplicity
* Accuracy
* Style/Tone
* Use of examples
* Domain appropriateness


#### Step 5: Document Results

Organize results into a tabular or sectioned format with:

* Prompt Type
* Prompt Used
* Outputs from Tool A and Tool B

#### Step 6: Evaluate

Add a short analysis on which prompt type yielded:

* The most informative summary
* The clearest explanation
* The most human-like tone
## PROMPTS
### Prompt Type 1: Zero-Shot Prompt
### Prompt:
```
"Summarize the article on 'The Basics of Blockchain Technology' in simple terms."
```

#### Tool A: ChatGPT (OpenAI)

Output:
ChatGPT explained blockchain as a digital ledger where transactions are recorded in linked blocks, secured by cryptography, and used in cryptocurrencies like Bitcoin.

#### Tool B: Gemini (Google)

Output:
Gemini described blockchain as a decentralized network that stores data transparently across many computers, emphasizing its use in secure transactions.

### Prompt Type 2: Few-Shot Prompt
### Prompt:
```
"Using the tech summaries as examples, briefly explain 'The Basics of Blockchain Technology.'"
```

#### Tool A: ChatGPT (OpenAI)

Output:
ChatGPT explained blockchain as a secure digital system where data is stored in linked blocks across many computers, helping make transactions safe and transparent.

#### Tool B: Gemini (Google)

Output:
Gemini described blockchain as a public, decentralized ledger that records transactions securely and is widely used in cryptocurrencies like Bitcoin.

### Prompt Type 3: Chain-of-Thought Prompt
### Prompt:
```
"What is blockchain? How does it work? Where is it used? Summarize clearly."
```

#### Tool A: ChatGPT (OpenAI)

Output:
ChatGPT explained blockchain stepwise — a chain of blocks storing transactions, secured by cryptography, validated by a network, used in digital currencies and beyond.

#### Tool B: Gemini (Google)

Output:
Gemini broke down blockchain into components, describing its decentralized ledger, security features, and real-world uses like supply chain and finance.

### Prompt Type 4: Role-Based Prompt
### Prompt:
```
"Explain 'The Basics of Blockchain Technology' as if you are a professor teaching first-year students."
```

#### Tool A: ChatGPT (OpenAI)

Output:
ChatGPT used a friendly, teaching tone: described blockchain as a tamper-proof digital notebook shared across many computers, highlighting examples like Bitcoin.

#### Tool B: Gemini (Google)

Output:
Gemini took a formal educator approach, explaining blockchain’s cryptographic basis and network consensus, using terms suitable for an introductory lecture.

## SUMMARY TABLE:
![table](https://github.com/user-attachments/assets/771e1028-1446-4611-895f-f29239f60919)

## Result
The evaluation of different prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across AI platforms ChatGPT and Gemini showed varied strengths. ChatGPT excelled in simplicity, clarity, and emotional engagement, making it ideal for beginner-friendly and educational summaries. Gemini offered more formal, abstract, and detailed outputs, suitable for advanced users and deeper insights. Selecting the best prompting approach depends on the user’s needs for accuracy, coherence, simplicity, and context.
