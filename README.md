Allow your users to add your BEP20 Token and Binance Smart Chain Network to MetaMask.

MetaMask supports EIP 747, which defines a way for sites to suggest an asset to their users’ wallet to track, I decided to build a tool to do that in the simplest way.

just change options at `addtometamask.js`, thats all

```
params: {
    'type': 'ERC20',
    'options': {
        'address': '0xe6ce27025f13f5213bbc560dc275e292965a392f',
        'symbol': 'LOOM',
        'decimals': '18',
        'image': 'https://bscscan.com/token/images/loomtoken_32.png',
    },
}
```
