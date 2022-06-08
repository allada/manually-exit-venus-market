# Document how to manually exit a venus market (specifically for UST/LUNA)
1. Head to the `Unitroller` contract of the Venus protocol in BSCScan: [0xfd36e2c2a6789db23113685031d7f16329158384](https://bscscan.com/address/0xfd36e2c2a6789db23113685031d7f16329158384)
2. Go to the `Contract` tab
3. Click `Write as Proxy`
4. Click `Connect to Web3`
5. Search for `exitMarket` and type the vToken address of the token you want to remove:
    - vUST - [0x78366446547D062f45b4C0f320cDaa6d710D87bb](https://bscscan.com/address/0x78366446547D062f45b4C0f320cDaa6d710D87bb)
    - vLuna - [0xb91A659E88B51474767CD97EF3196A3e7cEDD2c8](https://bscscan.com/address/0xb91A659E88B51474767CD97EF3196A3e7cEDD2c8)
6. Click `Write` and sign the contract with your favorite web3 wallet
7. Sign the transaction and you should be done

Sample:

![exit-market](https://user-images.githubusercontent.com/1831202/172690869-6c99d4b7-17f9-40f1-b007-c05286fd7a38.png)
