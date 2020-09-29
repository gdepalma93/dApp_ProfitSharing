# Profit Sharing dApp
---

This decentralized application was built using
    - Solidity: Solidity is a smart contract programming language that runs on many blockchains, namely, Ethereum (EVM) compatible chains. It is heavily inspired by Javascript, C++, and Python
    - Ethereum: Global, open-source platform for decentralized applications
    - Remix: Open Source IDE that helps your write Solidity contracts straight from the browser
    - Ganache: Personal blockchain for rapid Ethereum dApp development
    
This decentralized application is currently made up of 3 smart contracts

* [`AssociateProfitSplitter.sol`](Starter-Code/AssociateProfitSplitter.sol)
    Function: Pay your Associate-level employees quickly and easily.  
    Smart Contract Detail: This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.  
    
* [`TieredProfitSplitter.sol`](Starter-Code/TieredProfitSplitter.sol) 
    Function: Distribute profits to different tiers of employees. 
    Smart Contract Detail: will distribute different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%. 
    
* [`DeferredEquityPlan.sol`](Starter-Code/DeferredEquityPlan.sol) -- Level 3 starter code.
    Function: Distribute company shares for employees in a "deferred equity incentive plan" automatically.
    Smart Contract Detail: Models traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.
 
 
### Understanding Deferred Equity 

* **A two-minute primer on deferred equity incentive plans:** In this set-up, employees receive shares for joining and staying with the firm. They may receive, for example, an award of 1,000 shares when joining, but with a 4 year vesting period for these shares. This means that these shares would stay with the company, with only 250 shares (1,000/4) actually distributed to and owned by the employee each year. If the employee leaves within the first 4 years, he or she would forfeit ownership of any remaining (“unvested”) shares.

  * If, for example, the employee only sticks around for the first two years before moving on, the employee’s account will end up with 500 shares (250 shares * 2 years), with the remaining 500 shares staying with the company. In this above example, only half of the shares (and any distributions of company profit associated with them) actually “vested”, or became fully owned by the employee. The remaining half, which were still “deferred” or “unvested”, ended up fully owned by the company since the employee left midway through the incentive/vesting period.

  * Specific vesting periods, the dollar/crypto value of shares awarded, and the percentage equity stake (the percentage ownership of the company) all tend to vary according to the company, the specialized skills, or seniority of the employee, and the negotiating positions of the employee/company. If you receive an offer from a company offering equity (which is great!), just make sure you can clarify the current dollar value of those shares being offered (based on, perhaps, valuation implied by the most recent outside funding round). In other words, don’t be content with just receiving “X” number of shares without having a credible sense of what amount of dollars that “X” number represents. Be sure to understand your vesting schedule as well, particularly if you think you may not stick around for an extended period of time.