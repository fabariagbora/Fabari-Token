# Fabari-Token

ERC means Ethereum Request for Comment. ERC is a memorandum that describes methods of writing smart contracts on the ethereum blockchain. Many ERC standards focuses on tokens issued on the Ethereum blockchain to ensure it remains compatible with existing decentralized exchanges. Check out the Ethereum blockchain for to know more about token standards on the Ethereum blockchain. https://ethereum.org/en/developers/docs/standards/tokens/

This repository contains code written in solidity for the creation of ERC-20 and ERC-721 (NFT) tokens named after the owner of this repo Mr. Fabari. The smart contracts written were deployed to the Rinkeby Ethereum testnet.

## ERC-721 (FBR)

ERC-721 is an acceptable standard used for the creation of Non-Fungible Tokens on the Ethereum Blockchain. The link to Rinkeby ethereum testnet for the ERC-721 token named FabariNFT with the symbol (FBR) is: https://rinkeby.etherscan.io/address/0x1efc8bfffae9f87787270ab20d5676b79baf4c83

### IPFS-links

IPFS is Interplanetary File System. It is a decentralized file storage that leverages blockchain technology to ensure that files stored are always available and retrievable. I used IPFS to store the images of the NFTs minted on the blockchain. I minted two NFTs on the blockchain. 
The link to the  images can be viewed here:

Token ID    Image_Link
0           https://ipfs.io/ipfs/QmevZ4KajjgNAyLhZ99DQjsqrswaL12ZHKcSESyvm4H6ug
1           https://ipfs.io/ipfs/QmZ7p8aQjHqgG6tmexF7uBvJcCQxbjHsopZXg2KAMBmgg9

### Metadata

Metadata generated when the metadata function was queried is given below:

     
    For TokenID 0

    {
    name: Inspired Fabari
    image: https://ipfs.io/ipfs/QmevZ4KajjgNAyLhZ99DQjsqrswaL12ZHKcSESyvm4H6ug
    description: Owning this NFT gives you ownership of Mr. Fabari Agbora's personal journal filled with ideas that he penned down during his lifetime. This journal                    will be given to the holder of this NFT after Mr. Fabari's passing.
    }
    
    For TokenID 1

    {
    name: Focused Fabari
    image: https://ipfs.io/ipfs/QmZ7p8aQjHqgG6tmexF7uBvJcCQxbjHsopZXg2KAMBmgg9
    description: Owning this NFT grants you ownership of Mr. Fabari Agbora's personal journal filled with his personal weekly goals that he penned down during his                     lifetime. This journal will be given to the current holder of this NFT after Mr. Fabari's passing.
    }
    
