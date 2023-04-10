# Solidity-Smart-Contracts

Remix: https://remix.ethereum.org 

Solidity `Documentation:` https://docs.soliditylang.org/en/latest/index.html   
Solidity `Best practices:` https://consensys.github.io/smart-contract-best-practices/   
Solidity `By example:` https://solidity-by-example.org/

[Zero-Knowledge Proofs](https://ethereum.org/en/zero-knowledge-proofs/)   
[ERC20 Docs](https://docs.openzeppelin.com/contracts/4.x/)

## Tutorial Resources:

`1. Patrick Collins 32 hour course`   
  - [Youtube](https://www.youtube.com/watch?v=gyMwXuJrbJQ&list=PLQj6KMbjsRt7ft3xEtU8WhkK5-TsxDplY&t=12715s)   
  - Git: https://github.com/smartcontractkit/full-blockchain-solidity-course-js
 
`2. Dapp University`   
  - [Youtube](https://www.youtube.com/watch?v=EhPeHeoKF88&list=PLQj6KMbjsRt7ft3xEtU8WhkK5-TsxDplY&t=5131s)  
  - [More Youtube](https://www.youtube.com/watch?v=eoQJ6nFZOcs)
  - Git: https://github.com/dappuniversity/master_solidity
  
`3. Tech With Tim`   
  - [Youtube](https://www.youtube.com/watch?v=vwBxc8qfei8)     
  - Git: https://github.com/techwithtim
  
`4. HashLips NFT`
  - [Youtub](https://www.youtube.com/@HashLipsNFT)
  - Git: https://github.com/hashlips
  
## Tokens
* ERC-20 - Token contract for fungible assets.
* ERC-721 - Token standard for non-fungible assets.
* ERC-1155 - Multi Token Standard to take the best from previous standards to create a fungibility-agnostic and gas-efficient token contract.
* ERC-918 - Mineable Token Standard.
* ERC-165 - Creates a standard method to publish and detect what interfaces a smart contract implements.
* ERC-725 - A standard interface for a simple proxy account.
* ERC-173 - A standard interface for ownership of contracts.  

`Interview Questions`
- 100 Solidity Questions: https://youtu.be/FoCM07HlfhU?t=1644
- 10 Solidity Questions: https://www.youtube.com/watch?v=Vzjc-xffhJs

## Attacks 
- Reetrancy    
[Rekt](https://duckduckgo.com/?q=rekt.news&ia=web)   
Git: https://github.com/dappuniversity/Reentrancy-attack-Smart-Contract-Security
- Sandwhich https://www.youtube.com/watch?v=26lWg6UIrKw

## Key Terms   
`ABI` - specifies interface of set of functions that can be accessed outside of smart contract; similar to a JSON interface   
`Assert`   
`Constant` - naming convention ALL_CAPS; more `gas efficient`   
`Constructor` - called once when contract is deployed   
`Custom errors` - declared at top are more `gas efficient`   
`enums`   
`events`   
`Fallback`   
`invariant` -   
`immutable` - set once outisde of sentence that are declared, more `gas efficient` - i_owner - i meaning immutable    
`modifier` - `_;` - the underscore proceeds with code; code that can be run before and/or after a function call
  1. Restrict access
  2. Validate inputs
  3. Guard against reentrancy hack   
    
`Pure` - static, does not effect or modify state, more computational [free function]   
`recieve` -   
`Require` -   
`Revert` - gives back gas but loses some    
`TVL` - or total value locked   

Strings, arrays, and loops are computationally expensive    

`Unchecked` instead of `SafeMath` can be more `gas efficient` if you know your math won’t reach top or bottom limits.  




