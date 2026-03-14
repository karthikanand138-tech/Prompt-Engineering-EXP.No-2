EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:


CHATGPT 1️⃣ Zero-Shot Prompt Summarize the following article about “The Basics of Blockchain Technology”? Article: Blockchain technology is a decentralized digital ledger that records transactions across many computers. Each record is stored in a block, and these blocks are linked together to form a chain. This structure makes the data secure and difficult to change. Blockchain does not rely on a central authority, which increases transparency and trust. It is widely used in cryptocurrencies such as Bitcoin, but it also has applications in finance, supply chain management, healthcare, and voting systems. The main advantages of blockchain include security, transparency, and immutability of data.

2️⃣ Few-Shot Prompt Example 1 Topic: Artificial Intelligence Summary: Artificial Intelligence is a technology that enables machines to simulate human intelligence, learn from data, and perform tasks such as problem-solving and decision-making.

Example 2 Topic: Cloud Computing Summary: Cloud computing allows users to store and access data and applications over the internet instead of local computers, providing flexibility, scalability, and lower costs.

Now write a summary for the topic “The Basics of Blockchain Technology? Blockchain technology is a modern digital system used to record and store information securely and transparently. It is called a blockchain because the data is stored in blocks, and these blocks are connected together in a chronological chain. This technology was first introduced as the underlying system for the cryptocurrency Bitcoin, but today it is used in many industries beyond digital currencies.

A blockchain works as a decentralized digital ledger. This means that the information is not stored in a single central server or controlled by one authority. Instead, the data is distributed across many computers in a network called nodes. Each node keeps a copy of the entire blockchain. Because the data is shared across multiple systems, it becomes very difficult for anyone to alter or manipulate the records. This decentralized nature improves transparency, security, and trust among users.

Each block in a blockchain contains several components. A block usually stores transaction data, a timestamp, and a unique cryptographic code called a hash. The hash links the block to the previous block in the chain. If someone tries to change the information in a block, the hash value will also change, which breaks the connection with the next block. This makes tampering extremely difficult and easily detectable.

Another important concept in blockchain is consensus. Before a new block is added to the chain, the network participants must agree that the transaction is valid. Different blockchain systems use different consensus mechanisms such as Proof of Work (PoW) or Proof of Stake (PoS). These mechanisms ensure that all participants follow the same rules and that only valid transactions are recorded.

One of the major advantages of blockchain technology is security. Because the data is encrypted and distributed across multiple nodes, it is very resistant to hacking and fraud. Another advantage is transparency, since all participants in the network can view the transaction history. Additionally, blockchain offers immutability, meaning that once data is recorded, it cannot easily be changed or deleted

3️⃣ Chain-of-Thought Prompt First identify the main ideas such as the definition of blockchain, how it works, key components (blocks, nodes, and hashing), and its advantages. Then think through these points step by step and organize them logically. Finally, write a clear 500-word summary explaining the basics of blockchain technology Blockchain technology is a decentralized digital system used to record and store information securely. The term “blockchain” comes from the way data is organized into blocks that are linked together in a chain. Each block contains information about transactions, and once the data is recorded, it becomes very difficult to change. This makes blockchain a reliable and trustworthy technology for storing and sharing data.

The definition of blockchain can be understood as a distributed digital ledger that records transactions across multiple computers. Unlike traditional databases that are controlled by a central authority, blockchain operates on a decentralized network. This means that no single organization or person has full control over the data. Instead, the information is shared and verified by many computers in the network. This system increases transparency and reduces the risk of fraud or manipulation.

Blockchain works through a process of recording transactions in blocks. Whenever a transaction occurs, it is grouped with other transactions and placed into a block. Each block contains several pieces of information, including transaction details, a timestamp, and a unique digital code known as a hash. Once the block is filled with data, it is linked to the previous block using this hash value. In this way, blocks are connected one after another, forming a chain called the blockchain.

There are several key components that make blockchain technology function effectively. The first component is blocks. Blocks are the storage units of the blockchain that hold transaction data and other information. Every block is connected to the previous one, which creates a secure and continuous chain of records.

The second important component is nodes. Nodes are computers that participate in the blockchain network. Each node maintains a copy of the entire blockchain and helps verify new transactions. When a new block is created, the nodes in the network check and confirm that the information is valid. This process ensures that all copies of the blockchain remain accurate and consistent.

Another essential component is hashing. Hashing is a cryptographic technique that converts data into a fixed-length code known as a hash. Each block has its own hash and also contains the hash of the previous block. If someone attempts to change the information inside a block, the hash value will also change, which breaks the chain and alerts the network. This feature makes blockchain highly secure and resistant to tampering.

Blockchain technology offers several advantages. One of the most important benefits is security. Because data is encrypted and distributed across many nodes, it is extremely difficult for hackers to alter the information. Another advantage is transparency, since all participants in the network can view the transaction records. Blockchain also provides immutability, meaning that once data is recorded, it cannot easily be changed or deleted. This increases trust among users.

##GEMINI 1️⃣ Zero-Shot Prompt Summarize the following article about “The Basics of Blockchain Technology”? At its core, blockchain is a distributed, immutable ledger that facilitates the process of recording transactions and tracking assets in a business network. While it gained mainstream fame as the engine behind Bitcoin, its implications stretch far beyond digital currency. To understand blockchain, one must look at its three defining characteristics: decentralization, transparency, and security through cryptography.How the Architecture WorksThe name "blockchain" is literal. Information is stored in blocks, and each block has a specific storage capacity. When a block is filled, it is closed and linked to the previously filled block, forming a chronological chain.Each block contains three essential elements:The Data: In a financial context, this includes the sender, receiver, and amount.The Hash: Think of this as a digital fingerprint. It is a unique alphanumeric string generated by a mathematical algorithm.The Hash of the Previous Block: This is the "glue" that creates the chain. Because each block references the one before it, any attempt to change a single bit of data in an old block would change its hash, causing a mismatch in all subsequent blocks and alerting the network to a security breach.The Power of DecentralizationIn traditional systems, we rely on centralized authorities—like a bank or a government—to verify transactions. If the bank’s database is hacked or corrupted, the system fails. Blockchain removes this "single point of failure" by using a Peer-to-Peer (P2P) network.Every participant (node) in the network has a copy of the entire ledger. For a new block to be added, the network must reach a consensus. This is often achieved through mechanisms like Proof of Work (PoW) or Proof of Stake (PoS), where nodes validate the data to ensure it is legitimate. This democratic process ensures that no single entity can control or manipulate the history of the data.Transparency vs. PrivacyOne of the most interesting paradoxes of blockchain is its balance of transparency and privacy. While the ledger is public (anyone can see the transaction history), the identities of the users are protected by public-key cryptography. Users are represented by "addresses" (complex strings of characters). This allows for a system where everyone can verify that a transaction occurred without necessarily knowing exactly who was behind it.Beyond CryptocurrencyWhile finance was the first "killer app" for blockchain, the technology is evolving into other sectors:Smart Contracts: These are self-executing contracts with the terms written directly into code, eliminating the need for intermediaries.Supply Chain: Companies can track products from the raw material stage to the shelf, ensuring authenticity and ethical sourcing.Healthcare: Securely sharing patient records between providers while maintaining strict privacy.ConclusionBlockchain is more than just a buzzword; it is a fundamental shift in how we handle trust in the digital age. By moving from "trust in institutions" to "trust in math and code," blockchain provides a framework for a more secure, transparent, and efficient global economy.

2️⃣ Few-Shot Prompt Example 1 Topic: Artificial Intelligence Summary: Artificial Intelligence is a technology that enables machines to simulate human intelligence, learn from data, and perform tasks such as problem-solving and decision-making.

Example 2 Topic: Cloud Computing Summary: Cloud computing allows users to store and access data and applications over the internet instead of local computers, providing flexibility, scalability, and lower costs.

The Mechanism of Connectivity At its most basic level, IoT is about giving "dumb" objects a digital voice. Whether it is a smart thermostat in a residential home or a pressure sensor in a massive industrial pipeline, these devices collect raw data from their environment. This data is then transmitted via the cloud to a central management system. This connectivity allows for real-time monitoring and remote control, turning isolated hardware into an integrated, interactive ecosystem.

Impact on Efficiency The true value of IoT lies in its ability to automate mundane tasks and provide insights that were previously invisible. In a "Smart City," IoT sensors can monitor traffic flow and adjust signal timing to reduce congestion. In healthcare, wearable devices can monitor a patient's heart rate and automatically alert a doctor if an anomaly is detected. By bridging the gap between the physical and digital worlds, IoT creates a more responsive and efficient environment.

🤖 Machine Learning (ML) Summary: Machine Learning is a subset of Artificial Intelligence that focuses on the development of algorithms that allow computers to learn from and make predictions based on data, improving their accuracy over time without being explicitly programmed.

The Learning Process Traditional programming relies on "if-then" logic provided by a human. In contrast, Machine Learning uses statistical models to find patterns in massive datasets. There are three primary types of learning:

Supervised Learning: The model is trained on labeled data (e.g., teaching an AI to recognize a "cat" by showing it thousands of photos labeled "cat").

Unsupervised Learning: The model looks for hidden patterns or clusters in data without pre-existing labels (e.g., grouping customers by purchasing habits).

Reinforcement Learning: The model learns through trial and error, receiving "rewards" for correct actions (e.g., an AI learning to play a video game).

The Feedback Loop The "Learning" in ML refers to the iterative optimization of the algorithm. As the system processes more data, it refines its internal parameters to reduce the margin of error. This is why your Netflix recommendations or Spotify playlists seem to get "smarter" the more you use the service; the algorithm is constantly updating its understanding of your preferences.

⛓️ How They Converge The most powerful technological shifts happen when these two fields collide. IoT provides the "senses" (the data), while Machine Learning provides the "brain" (the analysis). For example, an IoT-enabled factory might collect vibration data from a machine, and a Machine Learning model can analyze that data to predict exactly when the machine will fail—a concept known as Predictive Maintenance. Together, they transform raw data into actionable intelligence.

3️⃣ Chain-of-Thought Prompt First identify the main ideas such as the definition of blockchain, how it works, key components (blocks, nodes, and hashing), and its advantages. Then think through these points step by step and organize them logically. Finally, write a clear 500-word summary explaining the basics of blockchain technology?

The Basics of Blockchain Technology
At its most fundamental level, blockchain is a distributed ledger technology (DLT) that allows data to be stored globally on thousands of servers while letting anyone on the network see everyone else's entries in near real-time. This makes it difficult for one user to gain control over the network or to game the system. To understand blockchain, one must move away from the image of a "file" stored on a single computer and instead imagine a shared, digital record book that is constantly synchronized.

The Anatomy of a Block The "chain" is made up of individual blocks of data. Each block contains three things: the data (such as a transaction record), a unique identifier called a hash, and the hash of the previous block in the chain.

The hash is the most critical security component. Generated by complex mathematical algorithms, a hash acts like a digital fingerprint. If even a single character within a block is changed, the hash changes entirely. Because each block contains the hash of the previous one, changing a block would "break" the chain, as all subsequent blocks would now point to an invalid fingerprint. This creates an immutable record; once data is written, it is effectively permanent.

The Power of Nodes and Consensus A blockchain does not live on a central server owned by a bank or a government. Instead, it exists on nodes—individual computers spread across the globe that each hold a full copy of the ledger.

When a new transaction occurs, it is broadcast to these nodes. For the transaction to be added to the chain, the network must reach a consensus. This is a collective agreement among nodes that the transaction is valid. Unlike a traditional bank, where one entity decides which transactions are "real," blockchain uses math-based protocols (like Proof of Work) to ensure that every entry is legitimate. This decentralization ensures that the system remains functional even if several nodes go offline or are attacked.

Why Blockchain Matters The advantages of this architecture are transformative. First, it offers unparalleled transparency; because the ledger is public, any participant can audit the trail of transactions. Second, it provides enhanced security. To hack a blockchain, one would have to alter every block in the chain across more than 50% of the nodes simultaneously—a feat that is computationally and financially nearly impossible.

Finally, blockchain eliminates the "middleman." In traditional systems, we pay fees to banks or clearinghouses to act as the "trusted" third party. Blockchain replaces this human trust with cryptographic proof. This reduces costs, speeds up transaction times, and provides financial access to people who may not have access to traditional banking infrastructure.

In conclusion, blockchain is a foundational technology. While it began with Bitcoin, its ability to create a secure, transparent, and decentralized record of "the truth" makes it a revolutionary tool for everything from voting systems to global supply chains.

##Claude 1️⃣ Zero-Shot Prompt Summarize the following article about “The Basics of Blockchain Technology”? Blockchain is a distributed digital ledger technology that records transactions across a network of computers in a way that is secure, transparent, and tamper-resistant. Core Concepts Structure: Data is stored in "blocks" that are cryptographically linked together in a chronological "chain." Each block contains a set of transactions, a timestamp, and a unique hash that connects it to the previous block. Decentralization: Unlike traditional databases controlled by a central authority (like a bank), blockchain is maintained by a distributed network of nodes (computers). No single entity owns or controls it. Consensus Mechanisms: To validate new transactions, the network uses agreement protocols such as Proof of Work (PoW) or Proof of Stake (PoS), ensuring all participants agree on the state of the ledger. Immutability: Once a block is added to the chain, altering it would require changing all subsequent blocks — computationally nearly impossible — making the record permanent and trustworthy. Transparency & Privacy: All transactions are visible to participants on the network, yet identities can remain pseudonymous. Key Applications

Cryptocurrency (e.g., Bitcoin, Ethereum) Smart Contracts — self-executing agreements coded on the blockchain Supply Chain Management — tracking goods from origin to consumer Healthcare — secure sharing of patient records Voting Systems — tamper-proof digital elections

2️⃣ Few-Shot Prompt Example 1 Topic: Artificial Intelligence Summary: Artificial Intelligence is a technology that enables machines to simulate human intelligence, learn from data, and perform tasks such as problem-solving and decision-making.

Example 2 Topic: Cloud Computing Summary: Cloud computing allows users to store and access data and applications over the internet instead of local computers, providing flexibility, scalability, and lower costs?

🔷 Core Components1. 🧱 Block Each block contains:

Data — transaction details Hash — a unique cryptographic fingerprint Previous Hash — links it to the prior block Timestamp — when the block was created 2. ⛓️ Chain Blocks are linked sequentially. Altering one block breaks the entire chain, ensuring immutability.3. 🌐 Network (Nodes) A peer-to-peer network of computers that collectively validate and store the blockchain — no central authority needed.🔷 How Blockchain WorksStep 1: A transaction is initiated ↓ Step 2: Transaction is broadcast to the P2P network ↓ Step 3: Network nodes validate the transaction ↓ Step 4: Verified transaction is combined with others into a Block ↓ Step 5: Block is added to the existing chain (permanent record) ↓ Step 6: Transaction complete ✅🔷 Key PropertiesPropertyDescriptionDecentralizedNo single point of controlImmutableRecords cannot be altered or deletedTransparentVisible to all network participantsSecureCryptographic hashing protects dataTrustlessNo need for intermediaries🔷 Types of Blockchain🔓 Public Blockchain

Open to anyone Examples: Bitcoin, Ethereum Fully decentralized 🔒 Private Blockchain

Restricted access Controlled by an organization Examples: Hyperledger, Corda 🔐 Consortium Blockchain

Shared among a group of organizations Semi-decentralized Examples: R3, Energy Web Chain 🔁 Hybrid Blockchain

Combination of public and private Examples: Dragonchain, XinFin

3️⃣ Chain-of-Thought Prompt First identify the main ideas such as the definition of blockchain, how it works, key components (blocks, nodes, and hashing), and its advantages. Then think through these points step by step and organize them logically. Finally, write a clear 500-word summary explaining the basics of blockchain technology?

Chain-of-Thought: Blockchain Technology Summary

🧠 STEP 1: Identify the Main Ideas Before writing, let's extract the key concepts: #Main IdeaCore Point1DefinitionWhat blockchain is2How It WorksThe process of recording transactions3Key ComponentsBlocks, Nodes, Hashing4AdvantagesWhy it matters & its benefits

🔄 STEP 2: Think Through Each Point Logically → Definition first — establish what blockchain is before explaining how it works → Components second — understand the building blocks (blocks, nodes, hashing) before the process → How it works third — now that we know the parts, explain how they function together → Advantages last — conclude with why it matters in the real world

✍️ STEP 3: The 500-Word Summary

Blockchain Technology: The Basics Explained Definition Blockchain technology is a revolutionary form of digital record-keeping that has transformed how data is stored, shared, and secured. At its core, a blockchain is a distributed digital ledger — a continuously growing list of records, called blocks, that are linked together and secured using cryptography. Unlike traditional databases managed by a central authority such as a bank or government, blockchain operates across a decentralized peer-to-peer network, meaning no single entity owns or controls it. Every participant in the network holds an identical copy of the ledger, making the system inherently transparent and resistant to manipulation.

Key Components To understand blockchain, it is essential to grasp its three foundational components: 🧱 Blocks are the individual units of data in a blockchain. Each block contains a set of transaction records, a timestamp indicating when it was created, and two critical pieces of cryptographic data — its own unique hash and the hash of the previous block. This linkage is what forms the "chain" in blockchain. 🔑 Hashing is the cryptographic process that converts any input of data into a fixed-length string of characters, known as a hash or digital fingerprint. Even the smallest change in the original data produces an entirely different hash, making it virtually impossible to alter records without detection. This is the backbone of blockchain's security and immutability. 🌐 Nodes are the individual computers that participate in the blockchain network. Each node stores a full copy of the blockchain and plays a role in validating new transactions. When a new transaction is submitted, nodes work together through a consensus mechanism — such as Proof of Work or Proof of Stake — to verify its legitimacy before it is permanently added to the chain.

How It Works The blockchain process follows a clear and logical sequence. First, a user initiates a transaction, such as sending cryptocurrency or signing a digital contract. This transaction is then broadcast to the network, where thousands of nodes receive and evaluate it. Once the majority of nodes reach consensus and validate the transaction, it is bundled together with other verified transactions into a new block. That block is then cryptographically sealed with a unique hash and appended to the end of the existing chain, creating a permanent and unalterable record. Because each block contains the hash of the previous block, the entire chain is interconnected — tampering with any single block would instantly invalidate every block that follows it.

Advantages Blockchain offers a compelling set of advantages that explain its rapid adoption across industries: ✅ Decentralization eliminates the need for intermediaries like banks or brokers, reducing costs and increasing efficiency. ✅ Immutability ensures that once data is recorded, it cannot be altered or deleted, creating a reliable and permanent audit trail. ✅ Transparency allows all network participants to view transaction history, fostering trust between parties. ✅ Security through cryptographic hashing makes blockchain one of the most tamper-resistant data systems available today. ✅ Trustless Transactions enable two parties who have never met to exchange value or information confidently, without relying on a third party.

Conclusion Blockchain technology represents a fundamental shift in how the digital world records and shares information. By combining decentralization, cryptographic security, and transparent consensus, it creates a system where trust is built into the technology itself — not dependent on any single institution or authority. From finance and healthcare to supply chains and voting systems, blockchain's potential to reshape industries is only beginning to be realized.

<img width="1215" height="391" alt="Screenshot 2026-03-09 092335" src="https://github.com/user-attachments/assets/96c2bbca-2c0f-4db9-bf4e-2d7bd9164fb4" />

RESULT:
<img width="1215" height="391" alt="Screenshot 2026-03-09 092335" src="https://github.com/user-attachments/assets/9aec181f-51f2-44ec-b1a0-af9ea2366eef" />
