# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (Zero-Shot, Few-Shot, Chain-of-Thought, and Role-Based Prompting) across different AI platforms such as ChatGPT, Gemini, Claude, and Copilot for the task of technical text summarization.

---

## Scenario
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on **“The Basics of Blockchain Technology”** using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

# Algorithm

## Step 1: Select the Topic
Choose a technical article for summarization.

Selected Topic:
**“The Basics of Blockchain Technology”**

The article includes:
- Definition of blockchain
- Decentralized ledger concept
- Blocks and cryptographic hashing
- Consensus mechanisms
- Applications of blockchain
- Advantages and challenges

---

## Step 2: Choose AI Platforms
The following AI tools were selected for experimentation:

- ChatGPT
- Google Gemini
- Claude AI
- Microsoft Copilot

---

## Step 3: Prepare Prompting Techniques

Four prompting strategies were used:

### A. Zero-Shot Prompting
The AI is directly asked to summarize the article without examples.

**Example:**  
“Summarize the following blockchain article in simple language for undergraduate students.”

---

### B. Few-Shot Prompting
The AI is provided with sample summaries before the actual task.

**Example:**  
Providing 1–2 example technical summaries before asking for the blockchain summary.

---

### C. Chain-of-Thought Prompting
The AI is instructed to analyze the article step-by-step before generating the summary.

**Example:**  
“Identify the important concepts first and then generate a concise summary.”

---

### D. Role-Based Prompting
A role or persona is assigned to the AI.

**Example:**  
“Act as a university professor and summarize blockchain technology for students.”

---

## Step 4: Generate Responses
The same blockchain article was given to every AI platform.

Each prompting strategy was tested individually:
- Zero-Shot
- Few-Shot
- Chain-of-Thought
- Role-Based

The generated summaries were collected and analyzed.

---

## Step 5: Organize Results
The responses were compared based on:
- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

# Result

## ChatGPT + Zero-Shot Prompting

### Prompt Used
> “Summarize the following article on Blockchain Technology in simple language for undergraduate students.”

### Summary Generated
Blockchain is a decentralized digital system used to securely store information across multiple computers. Data is stored in blocks linked together using cryptographic techniques. Blockchain removes the need for a central authority and improves transparency and security. It is commonly used in cryptocurrencies like Bitcoin and also in banking, healthcare, and supply chains. Major challenges include energy consumption and scalability.

### Evaluation
- Accuracy: High
- Coherence: Good
- Simplicity: Excellent
- Speed: Very Fast
- User Experience: Excellent

---

## Gemini + Few-Shot Prompting

### Prompt Used
> “Here are two sample technical summaries. Now summarize the blockchain article similarly.”

### Summary Generated
Blockchain is a secure distributed database where records are stored in connected blocks. Every participant has access to the same data, making the system transparent and difficult to alter. Blockchain supports cryptocurrency systems and improves applications in finance, healthcare, and logistics. However, challenges such as high power usage and slower transaction speed still exist.

### Evaluation
- Accuracy: Very High
- Coherence: Excellent
- Simplicity: Moderate
- Speed: Fast
- User Experience: Good

---

## Claude AI + Chain-of-Thought Prompting

### Prompt Used
> “Analyze the article step-by-step, identify key concepts, and then generate a concise student-friendly summary.”

### Summary Generated
Blockchain technology is a decentralized ledger system that securely records transactions across computer networks. Transactions are grouped into blocks and connected using cryptographic hashes. Consensus methods such as Proof of Work and Proof of Stake validate transactions securely. Blockchain is widely used in cryptocurrencies and has applications in healthcare, banking, and supply chain management. Its major strengths are transparency and security, while scalability and energy consumption remain challenges.

### Evaluation
- Accuracy: Excellent
- Coherence: Excellent
- Simplicity: Good
- Speed: Moderate
- User Experience: Very Good

---

## Copilot + Role-Based Prompting

### Prompt Used
> “Act as a university tutor and explain blockchain technology briefly for undergraduate students.”

### Summary Generated
Blockchain is a technology that stores information in digital blocks connected together. Since the data is distributed across many systems, it becomes secure and difficult to modify. Blockchain removes dependence on centralized authorities and improves transparency. It is commonly used in cryptocurrencies and financial systems, but issues like electricity usage and processing speed remain concerns.

### Evaluation
- Accuracy: Good
- Coherence: Good
- Simplicity: Excellent
- Speed: Fast
- User Experience: Good

---

# Comparison Table

| Platform | Prompting Technique | Accuracy | Coherence | Simplicity | Speed | User Experience |
|---|---|---|---|---|---|---|
| ChatGPT | Zero-Shot | High | Good | Excellent | Very Fast | Excellent |
| Gemini | Few-Shot | Very High | Excellent | Moderate | Fast | Good |
| Claude AI | Chain-of-Thought | Excellent | Excellent | Good | Moderate | Very Good |
| Copilot | Role-Based | Good | Good | Excellent | Fast | Good |

---

# Final Result

Thus, different prompting strategies were tested across multiple AI platforms for summarizing a technical article on blockchain technology.

- **Claude AI + Chain-of-Thought Prompting** produced the most accurate and coherent summaries.
- **ChatGPT + Zero-Shot Prompting** provided the best balance between simplicity, speed, and readability.
- **Gemini + Few-Shot Prompting** generated structured and detailed summaries.
- **Copilot + Role-Based Prompting** created beginner-friendly and concise explanations.

Overall, **ChatGPT with Zero-Shot Prompting** was identified as the most suitable combination for undergraduate educational summaries because it offered clear, simple, fast, and user-friendly results.
