# NFT Project with Hardhat

You can mint "Attack On Titan" inspired NFTs here - https://aot-nft-minter.netlify.app/

This is a React app meant for minting ERC721 tokens with all the metadata of the tokens being stored on-chain. The React app takes random values from 3 arrays and puts them together to make a random NFT. But, this randomness is not truly random as it relies on a bunch of strings to generate randomness.

The solution to this problem is to use Chainlink VRF. There's a folder within "contracts" called "ChainlinkVRF" which has updated smart contract code to mint truly random NFTs.