# Web3Bandits-subgraph

## How To:
To find the URI of a token and see where their metadata is hosted:
1. Find their contract on etherscan
<img width="870" alt="Screen Shot 2022-02-26 at 12 55 30 AM" src="https://user-images.githubusercontent.com/15346823/155836998-80981c13-e55a-4c6d-b452-515eb230dfdf.png">
2. Go to Contract > Read Contract
3. If it's an ERC-721 implementation (NFT project), look for ```tokenURI```. Pass in a token ID and then copthe alphanumeric string only. Don't copy the 
"ipfs://" that precedes the string.
<img width="827" alt="Screen Shot 2022-02-26 at 12 57 15 AM" src="https://user-images.githubusercontent.com/15346823/155837069-961ef423-bb39-43dc-816d-7af81d0c4df0.png">
4. In the browser, navigate to ```https://ipfs.io/ipfs/alphanumeric-string-you-copied-here```
<img width="951" alt="Screen Shot 2022-02-26 at 12 58 25 AM" src="https://user-images.githubusercontent.com/15346823/155837089-46a95ba2-5500-457b-bfa3-a347fe4d0ed1.png">
5. [Copy the JSON object and paste into an online JSON formatter to view the object more clearly.](https://jsonformatter.curiousconcept.com/#) 

