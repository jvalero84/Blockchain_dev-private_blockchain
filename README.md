Test results' screenshots

1. Use a GET call to request the Genesis block:
    ![Request: http://localhost:8000/block/0 ](./screenshots/GetGenesisBlock.png)
2. Use a POST call to requestValidation:
    ![Request: http://localhost:8000/requestValidation ](./screenshots/RequestValidation.png)
3. Sign message with your wallet:
    ![Use the Wallet to sign a message](./screenshots/MessageSignedWithWallet.png)
4. Submit your Star
     ![Request: http://localhost:8000/submitstar](./screenshots/SubmitStar.png)
5. Use GET call to retrieve starts owned by a particular address
    ![Request: http://localhost:8000/blocks/<WALLET_ADDRESS>](./screenshots/GetStarsByWalletAddress.png)
6. Create an endpoint that will trigger the execution of validateChain()
    ![Request: http://localhost:8000/validateChain](./screenshots/validateChain.png)