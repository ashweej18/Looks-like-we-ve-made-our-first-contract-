# **Looks like we have made our first smart contract**
---
![smart contract](Images/smart_contracts.png)

---
## **Background**

A new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic.

---
## **Objective**
To create `ProfitSplitter` smart contracts that will:

* Pay your associate-level employees quickly and easily.

* Distribute profits to different tiers of employees.

---
## **Libraries/Tools/Apps**

* Solidity
* Remix IDE
* Ganache
* Metamask

---
## **Code**


* [`AssociateProfitSplitter.sol`](AssociateProfitSplitter.sol) — Level 1 

* [`TieredProfitSplitter.sol`](TieredProfitSplitter.sol) — Level 2 

---

## **Outputs**

1. **AssociateProfitSplitter** </br>

    * Transferring 10 ETH to the contract through deposit function </br>

        ![remix](Level1_Outputs/Remix_code_execution.png)

        `Employee One Address` :`0xc85D482A7d93FEf9531017918f54d26A5eF09009`  </br>
        `Employee Two Address` :`0xA02Ab394a19E79bB33DD13AD5854d1a69C9E7317`  </br>
        `Employee Three Address` :`0x59b9458d8011Eb27fc8936bcfB1342330d91F31f` </br>

    * Remix Transaction details </br>

        ![remix_block](Level1_Outputs/Remix_block_details.png)

    * Ganache </br>

        ![ganache](Level1_Outputs/Ganache_txn_success.png)

     * Ganache Block Transaction </br>

        ![ganache block](Level1_Outputs/Ganache_txn_details.png) </br>

    ---
    </br> </br>

2. **TieredProfitSplitter** </br>

    * Compling the TieredProfitSplitter contract </br>

        ![remix](Level2_Outputs/remix_compile_success.png)

    * Transferring 10 ETH to the contract through deposit function </br>

        ![remix](Level2_Outputs/remix_txn_details.png)

        `Employee One Address (CEO)` :`0xA02Ab394a19E79bB33DD13AD5854d1a69C9E7317`  </br>
        `Employee Two Address (CTO)` :`0x59b9458d8011Eb27fc8936bcfB1342330d91F31f`  </br>
        `Employee Three Address (Bob)` :`0x7b8E3d2D46e212f00024Ae4769335Cdc97998799` </br> </br>

    * Remix Transaction details </br>

        ![remix_block](Level2_Outputs/Remix_block_details.png)

    * Ganache </br>

        ![ganache](Level2_Outputs/remix_txn_succes.png)

     * Ganache Block Transaction </br>

        ![ganache block](Level2_Outputs/Ganache_txn_details.png)

----
