# Smart Contract Security Dataset

## Dataset
This study used a dataset that had been used, containing **1,353 smart contracts** with Solidity code, bytecode, and opcode, collected from the Ethereum official website **[Etherscan.io](https://etherscan.io/)**. This dataset is categorized into 8 classes: **Decentralized Autonomous Organizations (DAO), Exploit, Gambling, Heist, Parity Wallet, Phish Hack, Ponzi, and Spam Token**. 

## Classes
This study categorizes malicious smart contracts into different classes, briefly explained below:

- **Ponzi**: A fraud that promises large profits with no risk and uses the money of new investors to pay back the existing investors [40].
- **Phish Hack**: An attack that reveals sensitive user information such as passwords, usernames, secret keys, or other authentication data [8].
- **Gambling**: Uses illegal techniques to gain unauthorized access to blockchain resources.
- **Parity Wallet**: Exploits a weakness in the parity multisign wallet, allowing attackers to gain control and make money [41].
- **Exploit**: Takes advantage of vulnerabilities in blockchain smart contracts [42].
- **Heist**: Attackers steal money from victims and transfer it to their accounts, causing significant financial losses [43].
- **DAO**: Exploits vulnerabilities in DAO, allowing repeated withdrawal requests before updating the balance, leading to major Ether theft [43].
- **Spam Token**: Attackers use tokens with similar names, symbols, scripts, or URLs for scams [5].

## Smart contract of each class
**Phish-Hack**	    300
**Ponzi**          	298
**DAO**             250
**Gambling**   	    220
**Parity Wallet**	  127
**Exploit**          76
**Heist**	           57
**Spam Token**       25
