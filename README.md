# LLM-fund-manager

A portfolio rebalancer in Uniswap based on research RAG and agent built in Galadriel

# Problem Statement:
Investing and dynamically re-balancing positions is a hard task. This project attempts to drive portfolio rebalancing through an agent that researches through curated content that is LLM trained, but set up as a domain specific research content built using RAG and agents in Galadriel.

# Solution
The Retrieval Augemeted Generation is built with Changelly reports that gives 
a) understanding of the digital asset class 
b) investment outlook for the asset class in 2024 
c) specifically honing in on the price predition for this month. ( July 2024) . 

The questions go from specific to generic.  

# Video
The video is available at : https://www.youtube.com/watch?v=Aio-fEitkPA

# Presentation deck
https://gitub.com/chainaim3003/LLM-fund-manager

# HOW TO RUN LLM-Fund-Manager ( devnet )
Follow the steps to install Galadriel, and set up the on chain contracts and agents.
#Agent deployed to 0x6F78f66ad057C4d429F153E33FeDF80b829A3b5b
 #deploying chatGptwithKB  
 #deploying chatGptwithKB  QmRW646Zabid4gJC5YmwpgF3q9iTCsUqymuXpp9iphQcis
#ChatGpt deployed to 0x1F8505B459B71920Da60fd625A629fE08a0e4399 with knowledge base "QmRW646Zabid4gJC5YmwpgF3q9iTCsUqymuXpp9iphQcis"

THe smart contract can be looked up at the following address in Galadriel devnet. 

The following commands run the chat , agent interface

\Galadriel\contracts\contracts> npm run agent

\Galadriel\contracts\contracts> npm run chat

The re-balancer balances portfolio of ETH/DAI based on the prediction reports that the LLM agent narrows down to action. 

Example snippet

SimpleSwap
WETH  balance amount Before :  BigNumber { value: "10000000000000000000" }
signer address   :  0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266
WETH  balance amount After :  BigNumber { value: "9900000000000000000" }
DAI Balance Before : 0
DAI Balance After  : 342.4783756098569
Portfolio reblanced by  342.4783756098569



# Whats next ?
Augment with cross-chain functionality and hooks.


