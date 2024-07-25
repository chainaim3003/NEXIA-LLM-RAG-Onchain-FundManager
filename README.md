# NEXIA (Networked Expertise and Contextual Intelligent Assistant)

Usecase:
A portfolio rebalancer in Uniswap based on research RAG and agent built in Galadriel

# Problem Statement:
LLMs and other SLMs have created 
	Workable Models for Natural Language Processing
	Trained on public domain data
	Have gone through Enough testing
	Have Baselines for latencies and AI inference costs
	Looks compelling to use
	
BUT,  they are still NOT very useful for Enterprises / Private companies 
Because
	Enterprises are hesitant to use public-domain data
	Prefer private databases and knowledgebases because
		the know-how might be proprietary

They need the best of both worlds to use the natural language training done on public domain data but have a way to 
	-  Query for private data
	- NOT re-incur the full total training costs.
	-  supply context-specific research to public systems 
	         Network smart contracts 
	                  (for example, private research for public digital asset prices) 

# Usecase:

Private Research RAG : A knowledge base using LLM but context-defined through private indexed knowledge base.

Rebalancing : Investing and dynamically re-balancing positions is a hard task. This project attempts to drive portfolio rebalancing through an agent that researches through curated content that is LLM trained, but set up as a domain specific research content built using RAG and agents in Galadriel.

# Solution

Retrieval Augmented Generation 
	Private knowledge bases – spliced and Indexed
	Indexed data used to set up the context against the LLM model
	Best of both worlds – public data training with private context.
	Conserves AI training costs  and baselined performance


Private Domain Data to Network systems,
	Inject  query responses  from private research data 
	To Network systems
	            Including permissionless systems
                                         Through Oracles to integrate private Enterprise Data	
	             	
# Usecase

Implementation in Galadriel Web 3 AI 
	- Knowledge base created 
	- Integrated to Galadriel Network through an Oracle

PRIVATE RESEARCH DATA  to Smart Contracts through  Oracles
          example..  On-chain LLM Fund Manager.
         voting systems for domain arbitration.

The Retrieval Augemeted Generation is built with Changelly reports that gives 
a) understanding of the digital asset class 
b) investment outlook for the asset class in 2024 
c) specifically honing in on the price predition for this month. ( July 2024) . 

The questions go from specific to generic.  

# Video
The video is available at : https://youtu.be/y-GOJWzqANs

# Presentation deck


## How to Run NEXIA (Devnet)

### Installation and Setup
* Follow the steps to install Galadriel.
* Set up the on-chain contracts and agents.

### Deployment
* **Agent Deployment:**
  * Agent deployed to: 0x6F78f66ad057C4d429F153E33FeDF80b829A3b5b
* **ChatGPT with Knowledge Base Deployment:**
  * Knowledge base: QmRW646Zabid4gJC5YmwpgF3q9iTCsUqymuXpp9iphQcis
  * ChatGPT deployed to: 0x1F8505B459B71920Da60fd625A629fE08a0e4399

### Smart Contract
* The smart contract can be found at the following address in the Galadriel devnet: [Smart Contract Address]

### Running the Chat and Agent Interface
* Navigate to the `\Galadriel\contracts\contracts` directory.
* Run the following commands:
  * `npm run chat`
  * `npm run agent`

### Rebalancer Functionality
* The rebalancer adjusts the ETH/DAI portfolio based on LLM agent predictions.
* **Example:**
  * Initial WETH balance: 1 ETH
  * Final WETH balance: 0.99 ETH
  * Initial DAI balance: 0 DAI
  * Final DAI balance: 342.4783756098569 DAI

### Next Steps
* Incorporate cross-chain capabilities.
* Implement webhooks for integration.

**Note:** Replace placeholders like "[Smart Contract Address]" with actual values.
 
**Would you like me to elaborate on any specific section or provide additional details?**


