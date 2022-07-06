# Roadmap for the you blockchain-contacts

🥁
A w3bapp for your blockchain contacts.
The base-func:
You auth with your wallet, we fetch all the wallets you ever had interaction with (on EVM chains) and you can save them with names, notes and tags, basically like the contacts on your phone.
That's an easy to implement base and offers a lot of room for creative expansion (sponsor challenges):

-   Fetch multi-blockchain data - use of Covalent api
-   Browse an address and show how many hops away it is (based on your contacts). - Implement TheGraph subgraph
-   Show assets of a Wallet - use TheGraph
-   Public tags (legit, fraud, weirdo, nft...) which you can add to an wallet you interacted with and can be retrieved by anyone. - use IPFS for db storage (DAGs?) - or use Ceramic
-   Send files to your contacts - use IPFS lib2p
-   Plot your 'universe', close circle, income/outcome, target group if you have an app. - saw this in a SuperFluid demo
-   ML algs, like link prediction. But that goes to far for 3 weeks.
-   OnChain messenger - use XMTP

We could use Remix (https://remix.run/blog/remix-stacks) which has a nice template for auth and database or stick to NextJs and use Supabase (I like that one better, we can do GraphQL queries here).

Both hackathons are very vague about what they want, both have a 'social track'.
The social impact of this app would be to help w3b users to organize and interact-with their contracts, one step further it could expose fraud or match you with cool new addresses.

## TODOs

1. Get started:
    - find a template or make a new UI design.
