# nft_collection
This smart contract is designed to manage an NFT collection in NEAR blockchain. It allows the owner to create new NFTs (minting) and associate each NFT with their NEAR account ID. The UnorderedMap is used to keep track of the ownership of each NFT by storing the mapping of token IDs to owner account IDs. The contract also ensures that it's properly initialized and that only the owner can mint NFTs.

Here is documentation file of [nft_collection](https://docs.google.com/document/d/1D-pD8eq8bobvh9Xr3G8CvwLxZcHKT7Cg53pibosMcNs/edit?usp=sharing)

We can also add more funcnalities into our smart contract.

Access Control:
Define roles and permissions within the contract to allow multiple users to interact with the collection, not just the owner. For example, you can have minting administrators who can mint NFTs.

Metadata Management: 
Implement the management of token metadata in an efficient and organized way, ensuring that metadata is retrievable for each NFT.

Events and Notifications: 
Emit events and notifications when minting, transferring, or selling NFTs. This allows external systems to listen for changes in the contract state.

Upgradeability: 
Consider implementing an upgrade mechanism that allows for the contract to be updated while preserving the existing state and NFT ownership.


