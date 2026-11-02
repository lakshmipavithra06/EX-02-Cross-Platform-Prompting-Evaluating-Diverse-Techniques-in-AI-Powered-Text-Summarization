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

1.Article Selection: Select a 500-word technical article on "The Basics of Blockchain Technology" as the input.

2.Goal Definition: Identify the target audience as undergraduate students and define the objective of producing a simple and accurate summary.

3.Basic Prompt: Provide a simple instruction asking the AI to summarize the article.

4.Role Prompt: Assign a specific role, such as a technical content writer, to the AI.

5.Context Prompt: Provide background information about the target audience and purpose of the summary.

6.Constraint Prompt: Add restrictions such as word limits, simple language, and important points to include.

7.Output Format Prompt: Specify the required structure of the final summary using headings and bullet points.

8.Evaluation: Compare the generated outputs to understand how each prompt structure affects the summary.

## Input Article
## Title: The Basics of Blockchain Technology

Blockchain technology is a digital system used to store and share information securely across multiple computers. It is commonly known for supporting cryptocurrencies such as Bitcoin, but its applications extend to healthcare, banking, supply chain management, and many other industries.

A blockchain is a collection of digital records called blocks. Each block contains transaction details, a timestamp, and a unique code called a hash. It also contains the hash of the previous block, which connects the blocks together in a chain. This connection makes it difficult to modify stored information without affecting the entire chain.

Blockchain works through a distributed network of computers called nodes. Instead of storing information in one central location, copies of the blockchain are maintained across multiple computers. When a new transaction takes place, it is shared with the network. The participating nodes verify the transaction using a process called consensus. Once the transaction is approved, it is grouped into a new block and added to the existing blockchain.

One of the important features of blockchain is decentralization. It means that the system is not controlled by a single organization or authority. This reduces the need for intermediaries and allows participants to share information directly. Another important feature is transparency. Participants with permission can view recorded transactions, making the system easier to verify.

Blockchain also provides security through cryptographic techniques. Each block has a unique hash, and changing information in an earlier block affects the connected blocks. This helps protect the stored records from unauthorized modifications. However, blockchain is not completely free from security risks.

Blockchain has several real-world applications. In banking, it can support faster and more transparent financial transactions. In supply chain management, it helps track products from manufacturers to customers. In healthcare, it can help securely manage medical records. Smart contracts are another important application. These are digital programs that automatically execute agreements when predefined conditions are satisfied.

Despite its advantages, blockchain has some limitations. Some blockchain networks consume large amounts of energy. Transaction processing can also become slow when the network is busy. Implementation costs, technical complexity, and regulatory challenges are other concerns.

In conclusion, blockchain is an innovative technology that provides a secure, transparent, and decentralized way of storing information. Although it has certain limitations, it has the potential to improve data management and transactions across different industries.

## 1. Basic Prompt

A Basic Prompt is a simple instruction given to an AI model to perform a specific task without providing additional details or conditions.

## Prompt:
`
Summarize the given article "The Basics of Blockchain Technology" in a short and understandable manner.
`
## Output:
Blockchain is a digital technology used to store information securely across multiple computers. It consists of connected blocks containing transaction details. Its important features include decentralization, transparency, and security. Blockchain is used in banking, healthcare, supply chain management, and smart contracts. However, it also has limitations such as high energy consumption, slow transactions, and implementation costs

## 2. Role Prompt:

A Role Prompt assigns a specific role or identity to the AI model so that it can generate responses from that particular perspective.

## Prompt:
`
Act as an experienced technical content writer. Read the article "The Basics of Blockchain Technology" and prepare a clear summary by identifying its main concepts, working process, features, applications, and limitations. 
`
## Output:

Blockchain is a digital technology that stores information in connected blocks across a distributed network of computers.

Its working process involves:
- Recording transactions in digital blocks.
- Verifying transactions through network participants.
- Using consensus mechanisms to approve transactions.
- Adding approved blocks to the existing chain.
Its major features are decentralization, transparency, and security. It is used in banking, healthcare, supply chain management, and smart contracts. However, energy consumption, processing delays, and implementation costs remain important challenges.

## 3. Context Prompt:

A Context Prompt provides background information about the task, target audience, or purpose to help the AI model generate a more relevant and meaningful response.

## Prompt:
`
I am an undergraduate Information Technology student learning about blockchain technology. I need to understand this topic for my academic studies. Summarize the article "The Basics of Blockchain Technology" using simple English. Explain the important concepts in a way that a beginner can easily understand. 
`

## Output:

Blockchain is a technology that stores information securely using a network of computers.
- Blocks: Digital records that contain transaction information.
- Hash: A unique code used to identify and connect blocks.
- Nodes: Computers that participate in the blockchain network.
- Consensus: A process used to verify and approve transactions.
- Decentralization: Information is shared across multiple computers instead of being controlled by one authority.
Blockchain is used in banking, healthcare, product tracking, and smart contracts. It provides security and transparency but has challenges such as high energy usage, slow processing, and technical complexity.

## 4. Constraint Prompt:

A Constraint Prompt provides specific rules or limitations that the AI model must follow while generating the response, such as word limits, language, and content requirements.

## Prompt:

`Summarize the article "The Basics of Blockchain Technology" by following these conditions:`

`1. Use simple English.`

`2. Keep the summary between 80 and 100 words.`

`3. Include the meaning, working process, important features, and applications of blockchain.`

`4. Mention at least two limitations.`

`5. Avoid unnecessary explanations.`

`6. Do not include information that is not present in the original article.` 

## Output:

Blockchain is a digital technology that stores information securely across multiple computers. It uses connected blocks containing transaction details and unique hashes. Transactions are verified by network participants through consensus before being added to the chain. Its main features include decentralization, transparency, and security. Blockchain is used in banking, healthcare, supply chain management, and smart contracts. However, it has limitations such as high energy consumption, slow transaction processing, implementation costs, and technical complexity.

## 5. Output Format Prompt:

An Output Format Prompt specifies how the AI-generated response should be organized or presented, such as using headings, bullet points, tables, or paragraphs.

## Prompt:

`Act as a technical educator preparing study material for undergraduate students. Summarize the article "The Basics of Blockchain Technology" using simple English.`

`Follow these instructions:`

`1. Keep the summary between 100 and 120 words.`

`2. Include only important information from the article.`

`3. Explain the concepts in a beginner-friendly manner.`

`4. Do not add external information.`

`Present the output using the following format:`

`Title:`

`Introduction:`

`Working:`

`Key Features:`

`Applications:`

`Limitations:`

`Conclusion:`

## Output:

Title: The Basics of Blockchain Technology

Introduction:
Blockchain is a digital technology used to store information securely across multiple computers.

Working:
Transactions are verified by network participants and stored in connected blocks using a consensus process.

Key Features:
- Decentralization
- Transparency
- Security

Applications:
- Banking and financial transactions
- Healthcare records
- Supply chain management
- Smart contracts
Limitations:
- High energy consumption
- Slow transaction processing
- Implementation costs
Conclusion:
Blockchain provides a secure and transparent way of storing information and has the potential to improve different industries.

## AI Platform Evaluation:

## ChatGPT + Zero-Shot Prompting:

## Prompt:
`
Summarize the following Blockchain Technology article using simple language suitable for undergraduate students.
`
## output:
Blockchain is a distributed digital ledger that securely stores data across multiple computers instead of relying on a single authority. Information is organized into linked blocks protected through cryptography, ensuring security and transparency. The technology is widely used in cryptocurrencies such as Bitcoin and is also applied in sectors including banking, healthcare, and supply chain management. Although blockchain offers improved trust and security, it still faces issues related to scalability and high energy consumption.

## Evaluation:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/a61b132a-f8a0-4629-b3c8-b2450c191814" />|

## Gemini + Few-Shot Prompting:

## Prompt:
`
Review the following sample summaries and create a summary of the blockchain article in the same style.
`
## Output:
Blockchain is a decentralized digital ledger that stores records in interconnected blocks. Since every participant shares the same version of the data, the system becomes transparent and resistant to tampering. It is the foundation of cryptocurrency networks and also supports applications in finance, healthcare, and logistics. Despite its benefits, blockchain continues to face limitations such as slower processing speeds and increased energy requirements.

## Evaluation:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b878b211-0850-45a4-825f-cd5a97419de2" />

## Claude AI + Chain-of-Thought Prompting:

## Prompt:
`
Carefully analyze the article, identify the main concepts step by step, and then prepare a concise summary suitable for undergraduate students.
`
## Output:
Blockchain is a decentralized ledger technology that records transactions securely across a network of computers. Transactions are grouped into blocks, which are linked together using cryptographic hashes to maintain integrity. Consensus mechanisms such as Proof of Work and Proof of Stake ensure secure validation of transactions. Blockchain is extensively used in cryptocurrency systems and has growing applications in banking, healthcare, and supply chain management. Its primary strengths include transparency and security, while scalability and energy consumption remain significant challenges.

## Evaluation:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/33485f76-db54-41f0-b754-983174bae5e8" />

## Microsoft Copilot + Role-Based Prompting:

## Prompt:
`
Act as a university instructor and provide a brief explanation of blockchain technology for undergraduate students.
`
## output:
Blockchain is a digital technology that stores information in connected blocks across multiple computer systems. Because the information is shared among many participants, it is highly secure and difficult to alter. The technology reduces dependence on central authorities while improving transparency and trust. Blockchain is widely used in cryptocurrency and financial applications, although concerns such as energy usage and transaction speed continue to exist.

## Evaluation:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/db5fe72f-6ea8-47d4-bae0-e8dc8e0e441d" />

## Comparative Analysis:

<img width="907" height="267" alt="Screenshot 2026-11-02 110400" src="https://github.com/user-attachments/assets/b8660d25-e66f-45f9-8bd2-f3a737bbe706" />



<img width="880" height="238" alt="Screenshot 2026-11-02 110309" src="https://github.com/user-attachments/assets/4fcd7da0-05e6-4cb9-b688-aeb49befe97d" />

## Result:

The experiment compared different prompting techniques across various AI platforms for summarizing a Blockchain Technology article.

The results showed that:

- Claude AI produced the most accurate and well-organized summary.
- ChatGPT provided simple and clear summaries very quickly.
- Gemini generated accurate summaries with good organization.
- Microsoft Copilot produced short and beginner-friendly summaries.

Overall, each AI platform performed differently, and the choice of prompting technique helped improve the quality of the summaries.
















