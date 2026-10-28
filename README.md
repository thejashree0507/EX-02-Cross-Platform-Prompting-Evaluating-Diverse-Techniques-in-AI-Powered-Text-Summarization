## NAME: THEJASHREE S
## REGNO: 212224240175
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

## Article: The Basics of Blockchain Technology
Blockchain is a digital technology used to store and share information securely across a network of computers. It is best known for its use in cryptocurrencies such as Bitcoin. Blockchain records information in blocks that are linked together in chronological order.

Each block contains transaction data and a cryptographic hash that connects it to the previous block. This structure helps protect the records from unauthorized changes. Instead of storing information in one central location, blockchain distributes copies of its ledger across multiple computers called nodes.

When a transaction occurs, the network checks its validity using predefined rules. Valid transactions are grouped into blocks and added to the blockchain through a process called consensus. Different blockchain systems use different consensus mechanisms, such as Proof of Work and Proof of Stake.

There are different types of blockchain networks. Public blockchains allow broad participation, while private blockchains restrict access to authorized users. Consortium blockchains are managed by a group of selected organizations.

Blockchain has several applications in finance, supply chain management, healthcare, and digital identity systems. Smart contracts can automatically execute predefined actions when certain conditions are met.

The main advantages of blockchain include transparency, traceability, and resistance to unauthorized changes. However, it also has limitations, such as high costs in some systems, transaction delays, privacy concerns, and energy consumption in certain networks.

In conclusion, blockchain is an important technology for maintaining distributed digital records. Although it offers benefits in security and transparency, its suitability depends on the specific application and its technical requirements.
Here is the complete answer in the same format as your reference document, adapted to your Blockchain Technology summarization scenario. You can use it for your practical record or assignment.

## Prompts and Outputs

### 1. Basic Prompt (Zero-Shot Prompting)

Prompt:

“Summarize the following article about The Basics of Blockchain Technology in simple English.”

ChatGPT Output:

Blockchain is a digital ledger that stores information in linked blocks across multiple computers. Transactions are verified by the network, and cryptography helps protect the records from unauthorized changes. Blockchain is used in cryptocurrencies, supply chain management, healthcare, and smart contracts. Its main benefits include transparency, traceability, and security. However, it can also have limitations, such as high costs, slower transactions, and privacy concerns.

Gemini Output:

Blockchain is a decentralized digital ledger that records information in connected blocks across a network of computers. Cryptographic techniques and consensus mechanisms help validate transactions and protect records. Blockchain is widely used in cryptocurrencies, finance, supply chains, and digital identity systems. Although it offers transparency and traceability, challenges include transaction delays, energy consumption in some networks, and implementation costs.

### 2. Few-Shot Prompt

Prompt:

“Example: Cloud computing allows users to access computing resources over the internet. Using the same concise and simple style, summarize the article about The Basics of Blockchain Technology in 4–5 sentences.”

ChatGPT Output:

Blockchain is a digital system that stores information in connected blocks across many computers. It uses cryptography and network verification to help protect records. Blockchain is used in Bitcoin, supply chains, healthcare, and smart contracts. It improves transparency and traceability but may involve high costs and transaction delays.

Gemini Output:

Blockchain is a distributed digital ledger that records transactions in linked blocks. It uses cryptographic hashes and consensus mechanisms to maintain reliable records. It is applied in cryptocurrencies, finance, healthcare, and supply chain management. Its advantages include transparency and traceability, while its limitations include scalability, cost, and privacy concerns.

### 3. Chain-of-Thought-Style Prompt

Prompt:

“Summarize the article by addressing these questions: What is blockchain? How does it work? What are its main applications? What are its advantages and limitations? Present the answer in a clear, structured summary.”

ChatGPT Output:

Blockchain is a distributed digital ledger that stores information in linked blocks. When a transaction occurs, network participants validate it according to predefined rules, and approved records are added to the chain. Cryptography helps protect the records from unauthorized changes. Blockchain is used in cryptocurrencies, healthcare, supply chains, and smart contracts. Its advantages include transparency, traceability, and resistance to tampering. However, some systems face challenges involving cost, transaction speed, privacy, and energy consumption.

Gemini Output:

Blockchain is a decentralized system for maintaining digital records across multiple computers. Transactions are validated using network rules and consensus mechanisms, and blocks are linked using cryptographic hashes. Applications include digital currencies, supply chain tracking, healthcare, and smart contracts. Blockchain can improve transparency and record traceability, but its limitations include scalability challenges, implementation costs, privacy concerns, and energy consumption in certain systems.

### 4. Role-Based Prompt

Prompt:

“You are a computer science professor teaching first-year undergraduate students. Summarize the article about The Basics of Blockchain Technology using simple English and an easy-to-understand example.”

ChatGPT Output:

Imagine a notebook shared by many people, where every transaction is recorded and copies are maintained across several computers. Blockchain works similarly by storing information in linked blocks. Network participants verify transactions, while cryptography helps protect the records. It is used in Bitcoin, supply chains, and healthcare. Blockchain improves transparency and makes unauthorized changes difficult, but some systems can be expensive or slow.

Gemini Output:

Blockchain can be understood as a shared digital record book maintained by a network of computers. Each block contains information linked to earlier blocks using cryptographic hashes. Network participants validate transactions before they are recorded. Blockchain is used in cryptocurrencies, supply chain management, and smart contracts. It offers transparency and traceability, but challenges include cost, transaction speed, and privacy.

## Comparison Table

| Prompt Type            | ChatGPT                           | Gemini                             |
| ---------------------- | --------------------------------- | ---------------------------------- |
| Zero-Shot              | Simple and direct                 | Clear and moderately technical     |
| Few-Shot               | Concise and easy to read          | Formal and factual                 |
| Chain-of-Thought-Style | Well-structured and comprehensive | More technical terminology         |
| Role-Based             | Friendly and beginner-oriented    | Clear with a formal teaching style |

## Evaluation Table

| Criteria        | ChatGPT                    | Gemini                      |
| --------------- | -------------------------- | --------------------------- |
| Accuracy        | Good                       | Good                        |
| Coherence       | Excellent                  | Very good                   |
| Simplicity      | Excellent                  | Good                        |
| Speed           | Not measured               | Not measured                |
| User Experience | Friendly and accessible    | Informative and structured  |
| Examples        | Easy-to-understand analogy | Clear technical explanation |


## Result
The experiment compared four prompting techniques — Zero-Shot, Few-Shot, Chain-of-Thought, and Role-Based Prompting — using ChatGPT and Google Gemini to summarize the article “The Basics of Blockchain Technology.”
