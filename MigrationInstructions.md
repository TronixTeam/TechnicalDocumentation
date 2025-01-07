
![1_eL4vDtwwMLwATt4Iw4CFPg](https://github.com/user-attachments/assets/21565a97-cff2-4b4a-9f80-0927c985ecf9)
We have started migrating Tron tokens from the old ERC20 standard to the new TRX20 (also known as TRC20) standard. New Tron tokens serve an important role as native tokens used on the Tron Mainnet. Tron holders should swap their old legacy ERC20 TRX for the new TRC20 using a migration contract.

> This is a 1:1 swap, which means that anyone who holds the ERC20 token will receive the same amount of TRX20 tokens. There is no reduction in the token supply.

## How to migrate TRX tokens from the Ethereum tokens to the Tron Mainnet?

For any remaining TRX ERC20 tokens that have not yet been migrated, we have decided to conduct the migration directly using **migration smart contract**, rather than using a migration user interface that is no longer supported. This makes the migration process for the remaining old Tron ERC20 token holders **simple**.

The migration smart contract, created solely for migration purposes, allows you to migrate your TRX tokens without connecting to any external platforms. The migration smart contract address is **open-source**, meaning the code can be checked by anyone.

Using the migration contract requires users to **pay the gas fee** on the Ethereum Blockchain. This means every user who wants to perform migration needs to have ETH in their wallet. The migration process is similar to any other transaction on the Ethereum Blockchain, and the gas fee is the same as any other transaction. We recommend choosing the average (normal) gas fee to avoid any inconvenience.

## Steps to Start Migration Process

**1. Access Your Wallet:** Check your TRX balance in the list of Ethereum tokens.

**2. Send Tokens:** Send your old ERC20 TRX tokens to the migration smart contract address `0x1ec168E7013edd0c5e1e3942d783EE5Aa923c194`. The migration smart contract address begins with `0x1e` and ends with `c194`. The case of letters does not matter (lower case or upper case).
Choose to send the **entire balance** of TRX tokens. The migration contract will wait for the **full balance** to arrive before initiating the migration process to optimize due to high Ethereum gas fees, partially covered by the Tron Foundation.

**3. Confirmation:** After the transaction is confirmed and broadcasted to the blockchain, the migration process will start, and your wallet will be credited with new TRX tokens. Depending on network usage, it may take 5–30 minutes to process the migration.

## Post-Migration

Your wallet will **automatically recognize** the new Tron Mainnet, and TRX will be credited to your wallet once the migration is complete. The public address of your Tron Mainnet wallet will look different from your Ethereum address where ERC20 TRX was stored, due to different hash algorithms used by Tron Mainnet. However, the migration contract will still know where to send the new migrated tokens. Your new Mainnet TRC20 TRX tokens will be tied to the same private key and seed.

Once the migration is complete, you will have new TRX tokens in your wallet. These tokens can be sold on any exchange that lists Tron, as all exchanges now support the new Tron Mainnet.

Congratulations, you have successfully performed the migration.

![kraj_clanka](https://github.com/user-attachments/assets/3a2a916d-b642-4f03-aea2-885942309a9b)
