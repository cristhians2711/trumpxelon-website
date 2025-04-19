# 🚀 TrumpXElon Token ($TXE)

**The Meme-Apocalypse Has Arrived**  
A fusion of chaos, satire, and deflationary crypto economics inspired by Trump, Elon Musk, and the unpredictable future of WLFI.

![TXE Logo](logo.png)

## 🧠 What is TrumpXElon ($TXE)?

TrumpXElon is a deflationary meme token on the Binance Smart Chain (BSC) that burns 2% of every transaction.  
It blends political absurdity, tech billionaire vibes, and a heavy dose of crypto-culture into a token with attitude.

> "_When memes, power, and chaos collide._"

## 🔥 Tokenomics

- **Name:** TrumpXElon  
- **Symbol:** TXE  
- **Supply:** 1,000,000,000 TXE  
- 🔥 **Burn Mechanism:** 2% burned on every transaction  
- 🚀 **10% Marketing Fund**  
- 💧 **10% Liquidity & Development**

## 🧾 Contract

```
Address: [To be added after deploy]
Network: Binance Smart Chain
Standard: BEP-20
```

## 💻 Website

Check the official website: [https://yourprojectdomain.com](https://yourprojectdomain.com)

## 📦 How to Use

1. Add the token to your wallet:
   - Contract address
   - 18 decimals
2. Swap BNB for $TXE on PancakeSwap (once listed)
3. Join the meme-army on Telegram and Twitter

## 👥 Community Links

- [Telegram](#)
- [Twitter](#)
- [Whitepaper](#)

## 🧠 Developers

This token uses a custom burn mechanism:

```solidity
function _transfer(address from, address to, uint256 amount) internal {
    uint256 burnAmount = (amount * burnRate) / 100;
    uint256 sendAmount = amount - burnAmount;

    balanceOf[from] -= amount;
    balanceOf[to] += sendAmount;
    totalSupply -= burnAmount;

    emit Transfer(from, to, sendAmount);
    emit Transfer(from, address(0), burnAmount);
}
```

## ⚠️ Disclaimer

This is a meme project. It is not financial advice.  
Always DYOR (Do Your Own Research). Memes may moon. Or not. ¯\_(ツ)_/¯

## 📜 License

MIT
