<p align="center">
  <img src="./assets/header.svg" alt="Mnilax — AI systems, onchain data and automation. Now building lintcha." width="100%">
</p>

# hey, i'm mnilax.

I build small tools for things that are hard to inspect: AI agents, onchain data and automation.

> **now building: lintcha — copy-trading on Robinhood Chain**<br>
> Follow the wallets you choose. Copy their BUYs inside limits you set. Keep every SELL in your own hands.

## current work

### [lintcha](https://lintcha.com) — copy-trading in [@lintchabot](https://t.me/lintchabot?start=copy_site)

Pick a public wallet or supported launchpad activity on Robinhood Chain, then choose per source:

- **notify only** — see the move, decide yourself
- **auto-copy BUY** — matched BUYs copied automatically, inside your per-trade and daily caps, max slippage, allowed routes and an expiring permission
- **manual SELL** — never automatic: fresh quote, separate review, your wallet confirms

Funds stay in your own self-custody wallet. No seed or private key ever goes through Telegram or lintcha's servers. Every copied BUY is simulated on current state, checked by independent RPCs and submitted once — no blind retries. A per-user stop halts auto-copy immediately.

Status: final testing. Auto-BUY stays off until every delegation, provider and safety gate passes.

[open copy-trading](https://t.me/lintchabot?start=copy_site) · [lintcha.com](https://lintcha.com) · [source](https://github.com/Mnilax/lintcha-chain)

### lintcha core — the read-only tools underneath

The original launch-reading tools live on inside lintcha, read-only: paste what a Robinhood Chain launch calls itself and see which of those strings already appear in the published snapshot. No score. No verdict.

[compare a launch](https://lintcha.com/#s04) · [live launches](https://lintcha.com/live/) · [deployer history](https://lintcha.com/deployer/)

### [lintcha charter](https://github.com/Mnilax/lintcha)

An earlier charter-linting experiment, kept as a complete public source snapshot.

[preserved source](https://github.com/Mnilax/lintcha)

## toolbox

`Python` · `JavaScript` · `TypeScript` · `Node.js`<br>
`Cloudflare Workers` · `Telegram Bot API` · `Solidity` · `Privy` · `MCP` · `GitHub Actions`

I like tools that are small enough to understand, useful enough to keep open, and honest about what they don't know.

[@mnilax](https://x.com/mnilax) · [@lintchadotcom](https://x.com/lintchadotcom) · [telegram room](https://t.me/lintcha)
