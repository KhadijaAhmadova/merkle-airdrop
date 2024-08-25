# Merkle Airdrop

The project uses Merkle Proofs to verify address eligibility for an ERC20 token aidrop. 
It allows claiming tokens and paying gas fees on behalf of the claiming adress using signature.

### Requirements
- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [foundry](https://getfoundry.sh/)

### Installation
```bash
git clone https://github.com/KhadijaAhmadova/merkle-airdrop
cd merkle-airdrop
```
Install [Openzeppelin library](https://github.com/OpenZeppelin/openzeppelin-contracts)
```bash
forge install OpenZeppelin/openzeppelin-contracts
```
Add `remappings = ["@openzeppelin/contracts/=lib/openzeppelin-contracts/contracts/"]` in `foundry.toml`.