## Gemachain Mobile Wallet

A mobile wallet for Gemachain made in flutter

Features:
- Watch over any address
- Import wallets with it's seedphrase (devnet only for now)
- Create new wallets (devnet only for now)

TODO / Ideas:
- [ ] **A name for the app**
- [ ] Seedphrases encryption
- [x] Mainnet/betanet/custom net support besides devnet
- [x] Ability to name and rename imported and created wallets, and watched addresses
- [x] Ability to make transactions
- [x] Ability to refresh the current GEMA value by pulling down
- [ ] Option to use another currency besides dollar as equivalent value
- [x] Display latest transactions
- [ ] Better project organization
- [ ] Ability to easily share an address (QR?)
- [ ] Have some UI tweaking options, like themes.
- [ ] Unit tests
- [ ] Ability to display NFTs owned by a wallet 
- [ ] Upload to https://itsallwidgets.com/
- [ ] Small note when making transactions

WIP.



### Building

```
flutter build apk --tree-shake-icons --split-per-abi
```

MIT License