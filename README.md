EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization.

AI TOOLS USED IN THE EXPERIMENT ARE: 
                                 • CHATGPT 
                                        • PERPLEXITY 
                                        • CLAUDE 
PROMPTS USED TO COMPARE THESE AI TOOLS ARE: 
                                 • ZERO SHOT PROMPT 
                                        • FEW SHOT PROMPT 
                                        • CHAIN OF THOUGHTS 
                                        • ROLE BASED
PARAGRAPH PROVIDED:
 “Blockchain technology is a digital system used to record and store information in a secure, transparent, and decentralized way. Unlike traditional databases that are controlled by a central authority such as a bank or organization, blockchain operates on a distributed network of computers. These computers, often called nodes, work together to maintain and verify a shared record of transactions. Because the data is distributed across many systems rather than stored in a single location, blockchain reduces the risk of data tampering and increases trust among users. The technology first became widely known through cryptocurrencies, especially Bitcoin, but today it is being explored for many other applications beyond digital currency. A blockchain is made up of a series of digital blocks that are connected together in chronological order to form a chain. Each block contains transaction data, a timestamp, and a unique cryptographic code called a hash. This hash links the current block to the previous one, creating a secure chain of records. If someone attempts to change the data in a block, the hash will also change, alerting the network that tampering has occurred. Because every block is connected to the one before it, altering a single block would require changing all subsequent blocks across the network, which is extremely difficult. One key feature of blockchain technology is decentralization. Instead of a central authority verifying transactions, network participants collectively verify them using a process called consensus. Mechanisms such as proof of work or proof of stake help confirm that transactions are valid before they are added permanently to the blockchain. Blockchain also oars transparency and immutability. All participants can view recorded transactions, which increases trust. Once information is added to the blockchain, it cannot easily be changed or deleted. This makes the technology useful for applications like supply chain tracking, digital identity management, and document verification. Another important concept is smart contracts. These are self-executing programs stored on the blockchain that automatically perform actions when certain conditions are met, such as transferring payment after a service is completed. Today, blockchain is being explored in industries such as finance, healthcare, logistics, and government services. Although it still faces challenges like scalability and energy consumption, many experts believe blockchain will play a major role in the future of digital systems and data management.”

CHATGPT:
                                                   1). ZERO-SHOT PROMPT:
         PROMPT PROVIDED:
          “Summarize the above paragraph into 100 words using zero-shot prompting”
          OUTPUT:
            Blockchain technology is a secure and decentralized digital system used to record and store information across a network of computers called nodes. Unlike traditional databases controlled by a central authority, blockchain distributes data across many systems, reducing the risk of tampering and increasing trust. It consists of connected blocks containing transaction data, timestamps, and cryptographic hashes that ensure data integrity. Transactions are verified through consensus mechanisms such as proof of work or proof of stake. Blockchain provides transparency and immutability, making records difficult to change. Beyond cryptocurrencies like Bitcoin, it is used in areas such as supply chain tracking, digital identity, healthcare, logistics, and smart contracts.



                                                      2). FEW-SHOT PROMPT:
               PROMPT PROVIDED:
                 “Summarize the above paragraph int 100 words using few-shot prompting”
                 OUTPUT:
                   Example 1:
                       Input: Artificial Intelligence helps machines perform tasks that                          normally require human intelligence.
                      Output: Artificial Intelligence enables machines to perform tasks like learning, reasoning, and decision-making similar to humans.
                    Example 2:
                        Input: Cloud computing allows users to store and access data over the internet instead of local computers.
                        Output: Cloud computing enables users to store, manage, and access data online instead of using local storage.
Now applying the same pattern to the given paragraph:
Blockchain technology is a decentralized system used to securely record and store digital transactions across a network of computers. Instead of relying on a central authority, multiple nodes verify and maintain shared records, increasing transparency and trust. Each block contains transaction data, a timestamp, and a cryptographic hash linking it to the previous block, making tampering extremely difficult. Consensus mechanisms such as proof of work or proof of stake validate transactions. Blockchain also supports smart contracts that automatically execute agreements when conditions are met. Initially popular through cryptocurrencies like Bitcoin, blockchain is now used in industries such as finance, healthcare, logistics, digital identity, and document verification.
                                                           3). CHAIN OF THOUGHTS:
                   PROMPT PROVIDED:
                    “Summarize the above paragraph into 100 words using chain of thoughts prompting”
                   OUTPUT:
                   Short approach:
                       Identify the main ideas (blockchain definition, structure of blocks,                       decentralization, security, consensus, and applications) and combine them into a concise 100-word summary.
                      Summary (100 words):
Blockchain technology is a decentralized digital system used to securely record and store information across a network of computers called nodes. Instead of relying on a central authority, transactions are verified collectively through consensus mechanisms such as proof of work or proof of stake. Data is stored in blocks that contain transaction details, timestamps, and cryptographic hashes linking them to previous blocks, forming a secure chain. This structure makes altering information extremely difficult, ensuring transparency and immutability. Initially known for supporting cryptocurrencies like Bitcoin, blockchain is now applied in many fields, including finance, healthcare, logistics, digital identity, document verification, and automated smart contracts.
                                                      4). ROLE BASED:
               PROMPT PROVIDED:
               “Summarize the above paragraph into 100 words by role-based prompting”
              OUTPUT:
              Role:  college Student
Blockchain technology is a digital system used to securely record and store information in a decentralized way. Instead of being controlled by a single authority like a bank, it works through a network of computers called nodes that verify and share transaction records. Information is stored in blocks that contain transaction details, timestamps, and a cryptographic hash linking each block to the previous one, forming a chain. This structure makes the data transparent and difficult to change. Blockchain became popular through cryptocurrencies like Bitcoin, but it is also used in areas such as finance, healthcare, logistics, digital identity, document verification, and smart contracts.
PERPLEXITY:
                                                   1). ZERO-SHOT PROMPT:
               PROMPT PROVIDED:
              “Summarize the above paragraph into 100 words using zero-shot prompting”
                 OUTPUT:
                 Blockchain technology records and stores data securely, transparently, and decentral across a network of computers (nodes), unlike centralized databases. It gained fame via Bitcoin but extends to diverse applications. Blocks form a chronological chain, each holding transactions, timestamps, and a unique hash linking to the prior block—making tampering evident and nearly impossible without altering the entire chain.
Key features include decentralization (consensus via proof-of-work/stake verifies transactions), transparency, and immutability. Smart contracts automate actions on predefined conditions. Used in finance, healthcare, logistics, and more, it faces scalability and energy hurdles but promises to transform digital systems.
(98 words)
                                                           2). FEW-SHOT PROMPT:
               PROMPT PROVIDED:      
                 “Summarize this paragraph into 100 words using few-shot prompting”
                 OUTPUT:
Example 1: Summarizing Climate Change
Input: "Climate change refers to long-term shifts in temperatures and weather patterns... caused mainly by human activities..." (long para).
Output: Climate change involves rising global temperatures from greenhouse gases due to fossil fuels, deforestation. Impacts include extreme weather, sea rise, biodiversity loss. Mitigation needs emission cuts, renewables. (45 words)
Example 2: Summarizing AI Ethics
Input: "AI ethics addresses moral issues in artificial intelligence development... bias, privacy, job displacement..."
Output: AI ethics tackles bias in algorithms, data privacy, accountability, and societal impacts like unemployment. Guidelines promote fairness, transparency, human oversight. (32 words)
Example 3: Summarizing Quantum Computing
Input: "Quantum computing uses qubits for massive parallelism unlike classical bits... applications in cryptography, drug discovery..."
Output: Quantum computing leverages qubits for exponential speed in complex problems like optimization and simulation, threatening current encryption but advancing medicine. Scalability challenges remain. (28 words)




OUTPUT:
Blockchain is a decentralized ledger recording transactions across nodes in linked blocks with hashes, ensuring security and tamper-proofing via consensus (proof-of-work/stake). Transparent and immutable, it supports smart contracts for automation. Beyond crypto like Bitcoin, it's applied in supply chains, identity, healthcare; challenges include scalability, energy use. (68 words)
                                                     	3). CHAIN OF THOUGHTS:
PROMPT PROVIDED:
“Summarize the above paragraph using few-shot prompting”
OUTPUT:
1.	Identify core topic: The paragraph explains blockchain basics—decentralized, secure data storage via distributed nodes, blocks chained by hashes.
2.	Key components: Structure (blocks, hashes, timestamps); security (tamper-evident chain); features (decentralization, consensus like PoW/Pos, transparency, immutability, smart contracts).
3.	History/applications: Originated with Bitcoin/crypto; now in supply chain, identity, finance, healthcare; challenges (scalability, energy).
4.	Condense to essentials: Focus on definition, how it works, benefits, uses, limitations—aim for ~100 words, clear language.
5.	Structure output: Start with definition, mechanics, features, apps, challenges for flow.
    OUTPUT:
Blockchain technology enables secure, transparent, decentralized data recording across computer networks (nodes), unlike central databases. Transactions form chronological blocks linked by cryptographic hashes and timestamps—altering one invalidates the chain, preventing tampering. Consensus mechanisms (e.g., proof-of-work, proof-of-stake) validate additions collectively. Immutable and viewable by all, it fosters trust via smart contracts that auto-execute on conditions. Popularized by Bitcoin, it's expanding to supply chains, digital IDs, healthcare, finance. Despite scalability and energy drawbacks, blockchain promises to revolutionize data management.
	
                                                         

                                                           4). ROLE BASED:
PROMPT PROVIDED:
“Summarize the above paragraph into 100 words using role based”
OUTPUT:
 Role: College Student
Hey, so blockchain is basically this super-secure digital ledger that spreads info across tons of computers instead of one boss like a bank. No single point of failure—nodes all check each other. Each "block" has transactions, time stamp, and a hash code that chains to the last one; mess with it, and everyone knows cause the hash breaks.
It's decentralized, so we use stuff like proof-of-work to agree on what's real. Transparent, can't delete stuff once added, and smart contracts auto-do things like pay up when conditions hit. Bitcoin made it famous, but now it's for tracking shipments, IDs, health records. Scalability and power use are issues, but future's bright! (99 words)
COPILOT:
	1). ZERO-SHOT PROMPT:
PROMPT PROVIDED:
“Summarize the above paragraph into 100 words using zero shot prompting”
OUTPUT:
Blockchain is a decentralized digital system that securely records and stores information across a network of computers, reducing risks of tampering and increasing trust. Unlike traditional databases controlled by central authorities, blockchain uses nodes to verify transactions through consensus mechanisms like proof of work or proof of stake. Data is stored in linked blocks containing transaction details, timestamps, and cryptographic hashes, making records immutable and transparent. Smart contracts enable automated actions when conditions are met. Beyond cryptocurrencies, blockchain is applied in supply chains, healthcare, finance, and government, though challenges like scalability and energy use remain.
	

                                                    2). FEW-SHOT PROMPT:
PROMPT PROVIDED:
“Summarize the above paragraph into 100 words using few shot prompting”
OUTPUT:
Example 1:
Cloud computing allows data storage and processing over the internet instead of local servers. It offers scalability, flexibility, and cost efficiency, enabling businesses to access resources on demand.
Example 2:
Artificial intelligence simulates human intelligence in machines. It powers applications like speech recognition, recommendation systems, and autonomous vehicles, transforming industries through automation and data analysis.
Final Output (Blockchain):
Blockchain is a decentralized system that records data securely across a network of nodes. Transactions are verified through consensus mechanisms and stored in linked blocks with cryptographic hashes, ensuring transparency and immutability. Smart contracts automate actions when conditions are met. Beyond cryptocurrencies, blockchain supports supply chain tracking, digital identity, and government services. Despite challenges like scalability and energy use, it promises transformative applications in finance, healthcare, and logistics.
	3). CHAIN OF THOUGHTS:
PROMPT PROVIDED:
“Summarize the above paragraph into 100 words using chain of thoughts”
OUTPUT:
1.	Identify core ideas: Blockchain is decentralized, secure, transparent, immutable, and uses consensus mechanisms.
2.	Key components: Blocks contain data, timestamps, and hashes linking them together. Tampering is difficult because altering one block requires changing all subsequent ones.
3.	Features: Decentralization, transparency, immutability, and smart contracts.
4.	Applications: Cryptocurrencies, supply chain, identity management, finance, healthcare, logistics, government.
5.	Challenges: Scalability and energy consumption.
6.	Goal: Condense all of this into ~100 words.
Final Summary (100 words):
Blockchain is a decentralized digital system that securely records transactions across a distributed network of nodes. Each block contains data, a timestamp, and a cryptographic hash linking it to the previous block, making tampering extremely difficult. Consensus mechanisms like proof of work or proof of stake validate transactions collectively, ensuring transparency and immutability. Smart contracts enable automated execution when conditions are met. Initially popularized by cryptocurrencies, blockchain now supports supply chain tracking, digital identity, healthcare, finance, and government services. Despite challenges such as scalability and energy use, it is seen as a transformative technology for future data management.

	4). ROLE BASED:
PROMPT PROVIDED:
“Summarize the above paragraph into 100 words by role-based prompting”
OUTPUT:
Role: College Student
Blockchain is a decentralized technology that records and secures data across a network of computers, called nodes, instead of relying on a central authority. Each block stores transaction details, timestamps, and cryptographic hashes that link it to the previous block, making tampering nearly impossible. Transactions are verified collectively through consensus mechanisms like proof of work or proof of stake, ensuring transparency and immutability. Smart contracts allow automatic execution of agreements when conditions are met. While blockchain gained fame through Bitcoin, it now supports supply chains, healthcare, finance, and government services, though challenges like scalability and energy consumption remain.




RESULT:
```
Criteria	ChatGPT	  Perplexity 	Microsoft Copilot
Accuracy	9/10	    9/10	     8/10
Coherence	9/10	    8/10  	     8/10
Simplicity	9/10	    8/10	     8/10
Speed	        8/10	    9/10	     8/10
User Experience	9/10	    8/10	     8/10
```



