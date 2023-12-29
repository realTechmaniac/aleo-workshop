<!-- # 🪙 Token -->

[//]: # (<img alt="workshop/token" width="1412" src="../.resources/token.png">)

A transparent & shielded custom token in Leo.

## Run Guide

To run this program, run:
```bash
./run.sh
```

leo example token

cd token

leo account new
 
leo run min_private [address] [amount(integer)]


steps

i) replace the .env privatekey with your generate private key from leo account new and chane the receiver address

ii) leo run mint_private

iii) replace transfer_private in main.leo with  • {
  owner: aleo1uncqp5dhr0u3v2qse6sqn39lvwmy29zagnu9cnnqqgrjv83nkq9qae2jqk.private,
  amount: 100u64.private,
  _nonce: 8123910909750923626585090663021917181231337986326029961215277159123533157502group.public 
}

iv) run leo run transfer_private