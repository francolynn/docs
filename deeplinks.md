Open in Trust Wallet dApp Browser `https://trustwalletapp.com`

```json
{
   "event": "openURL",
   "url": "https://trustwalletapp.com",
   "$canonical_url": "https://trustwalletapp.com",
}
```

Add new token custom token to the wallet. Ex: `0x86fa049857e0209aa7d9e616f7eb3b3b78ecfdb0`


```json
{
   "event": "newToken",
   "contract": "0x86fa049857e0209aa7d9e616f7eb3b3b78ecfdb0"
}
```

Branch Key: `key_live_lfvIpVeI9TFWxPCqwU8rZnogFqhnzs4D`

Example: `https://links.trustwalletapp.com/7aoeGc6UzM` - points to peepeth.com DApp

One liner to deep link into google.com:

```
https://links.trustwalletapp.com/a/key_live_lfvIpVeI9TFWxPCqwU8rZnogFqhnzs4D?&event=openURL&url=https://google.com
```

### Recomended

Reference for [iOS implementation](https://github.com/TrustWallet/trust-wallet-ios/blob/master/Trust/Core/Types/BranchEvent.swift)

Reference for [Mobile DApps with Deep Linking and Trust Wallet](https://medium.com/@trustwallet/mobile-dapps-with-deep-linking-and-trust-wallet-6a4712b9b9a4
)

