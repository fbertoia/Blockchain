# Permissioned Blockchains

> Notes from the [monax.io article](https://monax.io/learn/permissioned_blockchains/) about  permissioned blockchains.

Permissioned blockchains (PB) do not differ from Unpermissioned Blockchains (public blockchains) (UB)  except from the presence of an **access control layer** built into the blockchain nodes.
##### How to define whether it is a permissioned network or not ? 
\- Can anyone restrict who can participate in the consensus mechanism of the blockchain's network?
\- Can anyone restrict who has the ability to issue smart contracts or transact on the blockchain network?

## Benefits of permissioned blockchains :

 - ***Performance*** : one can get better performance from a single blockchain network, since the computation work will focus only on the application you try to use. No extra effort would be spend upon mining useless contracts.

- ***Governance clearly defined*** : innovation is slow to be adopted on UB because it requires consensus between major actors. Conversely, PB are very flexible, and also, may aim at fulfilling very specific objectives compared to UB which '*have to be built for the lowest common denominator*'. 

- ***PB are more cost efficient*** : PB ensure security on blockchain and avoid any attack vector. (Infinite loops can be handle in a different manner than relying upon pricing dynamics).

- ***Security*** : Article unclear on this part

Most blockchains are designed to withstand trustless nodes, which brings about limitations. For instance, 'Bitcoin is a trustless environment, the system was designed so that nobody has to trust anybody else in order for the system to function'. [Quora](https://www.quora.com/What-does-it-mean-that-Bitcoin-is-trustless).

Trust is not always a 'pain point'. When depositing funds in a bank, trust comes in to believe that account are safely kept. Moreover, if one makes a mistake, human discretion is usually required to remedy those mistakes. If a mechanism cannot be broken, it cannot be repaired nor reversed.

Monax prefers verifiability instead of trustlessness. It tends to invent business process automation between stakeholders that includes verifiability.

## Smart Contracts
From [Monax article about smart contracts](https://monax.io/learn/smart_contracts/)
Smart contracts have visility accross the blockchain. Anyone can have access to the contract itself and the code.

Without this system, companies may have to implement redundant softwares to monitor and track data interactions for a given deal. Conversely, having access to the blockchain lead to being able to verify the entirety of the interactions and the history of the data set.
- Benefits come with multi-interactions parties and avoiding redundancies of data and scripting capabilities.
- No real contracts : not enforceable. For the foreseeable future, they will not be enforceable in any court, and few parties will be able to rely on smart contract technology alone. 

### Are smart contracts more than a python script?
In case of API, no one knows what is happening between the request and response. 
Also, scripts can read top level environment variables and run differently on a different version of their language, and therefor have different outcomes.

Smart contracts allows user to predict the output, every compute step along the logic sequence is verified by every node on the network.

However, blockchain smart contracts cannot ensure privacy.
