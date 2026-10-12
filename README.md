<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img alt="Avish Rakshe — Building payment & trust rails for AI agents" src="./assets/banner-light.svg" width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/avish-rakshe-92552b372/"><img src="https://img.shields.io/badge/LinkedIn-Avish_Rakshe-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/ARakshe34041"><img src="https://img.shields.io/badge/@ARakshe34041-000000?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://www.instagram.com/_avish._01/"><img src="https://img.shields.io/badge/Instagram-__avish.__01-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" /></a>
</p>

I'm a Computer Science student, artist, and full-stack developer. I build the plumbing that lets **AI agents find, trust and pay each other**: per-call payments over x402, on-chain identity and reputation, private settlement, and spend controls that stop a runaway agent before it drains a wallet.

I ship end to end. That means the Solidity, Rust or Compact contracts, the TypeScript services between them, and the interface on top. I design that interface myself, because a protocol nobody can understand is a protocol nobody uses.

### Now

- **[Turn](https://github.com/avishrakshe/Turn)**: on-chain rotating savings circles for families who already run them offline. Built for Monad Metropolis.
- **[DeFi Agent Marketplace](https://github.com/avishrakshe/Defi-Agents-On-monad-)**: agents that pay agents, live on Monad testnet and MagicBlock.
- **[Tabula](https://github.com/avishrakshe/Tabula)**: spend control and treasury for agents paying over Solana payment channels.

---

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### [DeFi Agent Marketplace](https://github.com/avishrakshe/Defi-Agents-On-monad-)
Ask a question in plain language. Specialist agents split the work, verify each other against on-chain registries, pay **$0.001 USDC per call** over x402, and return one answer. No LLM sits in the money path.

`Monad` `MagicBlock` `x402 / EIP-3009` `ERC-8004` `TypeScript`

[Live](https://frontend-eight-peach-71.vercel.app) · [API](https://defi-agents-backend.vercel.app/api/status) · [Code](https://github.com/avishrakshe/Defi-Agents-On-monad-)

</td>
<td width="50%" valign="top">

### [Tabula](https://github.com/avishrakshe/Tabula)
Every agent payment, accounted for. Tabula checks each voucher against budgets, price caps and vendor allowlists before signing, kills runaway agents, and anchors a Merkle root of the ledger on-chain.

`Solana` `Payment channels` `Squads v4` `Next.js`

[Live](https://tabula-agents.vercel.app) · [Film](https://tabula-agents.vercel.app/film) · [Code](https://github.com/avishrakshe/Tabula)
<br><sub>Colosseum · Crypto World's Fair, Solana track</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Turn](https://github.com/avishrakshe/Turn)
The chit fund, tanda or committee, on-chain. Members sign in with a passkey, pay no gas, bid for early turns in an auction, and post collateral that covers anyone who stops paying.

`Monad` `Foundry` `EIP-7702` `Chainlink CRE` `Envio`

[Live](https://turn-sigma.vercel.app) · [Code](https://github.com/avishrakshe/Turn)
<br><sub>Monad Metropolis · Consumer Products &amp; Payments</sub>

</td>
<td width="50%" valign="top">

### [Private OTC Agent Desk](https://github.com/avishrakshe/Private-OTC-Agent-Desk-On-Midnight-)
A sealed-RFQ trading desk for DAO treasuries, market makers and AI agents. Nobody sees the order until it fills. Has 67 verified testnet users, CI, and a contract test suite.

`Midnight` `Compact` `Zero-knowledge` `React 19`

[Live](https://mn-demo.vercel.app) · [Demo video](https://youtu.be/vIem1ycVtyE) · [Code](https://github.com/avishrakshe/Private-OTC-Agent-Desk-On-Midnight-)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [CallRank](https://github.com/avishrakshe/CallRank)
A leaderboard for verifiable market calls. AI trading agents and humans compete on fixed-window event contracts, and Elo is computed only from on-chain settlements, so the rankings can't be faked.

`Somnia` `DreamDEX` `Next.js` `TypeScript`

[Live](https://callrank.vercel.app) · [Code](https://github.com/avishrakshe/CallRank)
<br><sub>Somnia × DreamDEX Event Contracts Hackathon</sub>

</td>
<td width="50%" valign="top">

### [Agent Passport](https://github.com/avishrakshe/AgentPassport)
Identity and reputation for autonomous agents. Ratings decay with a 14-day half-life to stop sleep-and-exit attacks, an SDK covers LangChain, ElizaOS and CrewAI, and a MetaMask Snap checks the counterparty before you sign.

`Monad` `Solidity` `Envio` `MetaMask Snaps`

[Code](https://github.com/avishrakshe/AgentPassport)
<br><sub>Monad Metropolis · Trust, Identity &amp; AI Infrastructure</sub>

</td>
</tr>
</table>

### More builds

| Project | What it does | Built with |
|---|---|---|
| [Hush](https://github.com/avishrakshe/Hush) | Private x402 payments for AI agents using encrypted eERC tokens, with an MCP server | Avalanche · TypeScript |
| [AgentPay Rails](https://github.com/avishrakshe/stellar-mastery) · [live](https://stellar-mastery.vercel.app) | Escrow and payment routing for agents through Soroban inter-contract calls | Stellar · Rust |
| [Private Agent Marketplace](https://github.com/avishrakshe/Agent-Marketplace) · [live](https://agent-marketplace-frontend.vercel.app) | Permissioned L1 with encrypted agent payments and an auditor key for compliance | Avalanche · Solidity · FastAPI |
| [Nox Agent Market](https://github.com/avishrakshe/Nox-Agent-Market) | Hidden balances and private reputation bands using iExec Nox confidential computing | Sepolia · iExec Nox |
| [Monarc](https://github.com/avishrakshe/Monarc) | Agent hiring marketplace with ERC-8004 identity, staking and escrowed payouts | Monad · Solidity |
| [EquityOS](https://github.com/avishrakshe/EquityOs) | Agents that research tokenized stocks and pay each other over x402, in paper mode | Base · TypeScript |
| [BeatFlow](https://github.com/avishrakshe/Beatflow-) | Music marketplace with AI vocals, beat NFTs, remix provenance and pay-per-listen | Next.js · Solidity · ElevenLabs |
| [BeatFlow Cred](https://github.com/avishrakshe/beatflow-onchain-cred) · [live](https://beatflow-onchain-cred.vercel.app) | On-chain credibility scores and reward tiers for independent creators | Ethereum · TypeScript |
| [CargoSync](https://github.com/avishrakshe/CargoSync) | Fleet and logistics command center with dispatch validation and ROI analytics | HTML · JavaScript |
| [Presence Pulse](https://github.com/avishrakshe/presence-pulse) | Detects social settings and nudges you off your phone (built with Manad Pagare) | Django · MySQL · Web Bluetooth |

---

## Tech stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/stack-dark.svg">
  <img alt="Tech stack: TypeScript, JavaScript, Solidity, Rust, Python, Java, C, C++, HTML, CSS, SQL, Next.js, React, Vite, Tailwind, Node.js, FastAPI, Django, PostgreSQL, MongoDB, Firebase, GraphQL, Ethereum, Solana, Avalanche, Stellar, Chainlink, Web3.js, Git, GitHub, GitHub Actions, Vercel, pnpm, Linux, Figma, Canva" src="./assets/stack-light.svg" width="100%">
</picture>

**Languages**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white" alt="Solidity" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

**Blockchain & Web3**

<p>
  <img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white" alt="Ethereum" />
  <img src="https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white" alt="Solana" />
  <img src="https://img.shields.io/badge/Avalanche-E84142?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjQwIDUwIDE3NiAxNDAiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xMTcgNThjNC42LTggMTMuOC04IDE4LjQgMGwxMyAyMi42YzIuNiA0LjUgMi42IDEwLjEgMCAxNC42TDEwMiAxNzZjLTIuNiA0LjUtNy40IDcuMy0xMi42IDcuM0g1NS42Yy04LjIgMC0xMy4zLTguOS05LjItMTZ6Ii8%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTE2Ni40IDEyNC42YzQuMS03LjEgMTQuMy03LjEgMTguNCAwbDI1LjYgNDQuM2M0LjEgNy4xLTEgMTYtOS4yIDE2aC01MS4yYy04LjIgMC0xMy4zLTguOS05LjItMTZ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Avalanche" />
  <img src="https://img.shields.io/badge/Stellar-7D00FF?style=for-the-badge&logo=stellar&logoColor=white" alt="Stellar" />
  <img src="https://img.shields.io/badge/Web3.js-F16822?style=for-the-badge&logo=web3dotjs&logoColor=white" alt="Web3.js" />
  <img src="https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white" alt="Chainlink" />
</p>

**Backend & data**

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL" />
</p>

**Tools & design**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white" alt="pnpm" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEyIDBDNS4zNzMgMCAwIDUuMzczIDAgMTJzNS4zNzMgMTIgMTIgMTIgMTItNS4zNzMgMTItMTJTMTguNjI3IDAgMTIgMHpNNi45NjIgNy42OGMuNzU0IDAgMS4zMzcuNTQ5IDEuNDA1IDEuMi4wNjkuNTgzLS4xNzEgMS4wOTctLjgyMiAxLjQwNi0uMzQzLjE3MS0uNDguMTcyLS41NDkuMDY5LS4wMzQtLjA2OSAwLS4xMzcuMDY5LS4yMDYuNjE3LS41MTQuNjE3LS45MjYuNTQ4LTEuNTA4LS4wMzQtLjM3OC0uMzA4LS42MTgtLjU4My0uNjE4LTEuMiAwLTIuOTE0IDIuNjc0LTIuNjc0IDQuNjI5LjEwMy43NTQuNTQ5IDEuNjQ2IDEuNTA5IDEuNjQ2LjMwOCAwIC42NS0uMTAzLjk2LS4yNC41LS4yNjQuNzk5LS40NyAxLjA5Ny0uOC0uMDczLS44ODUuNzA0LTIuMDQ2IDEuODUxLTIuMDQ2LjUxNSAwIC45MjYuMjA1Ljk2LjU4My4wNjguNTE0LS4zNzcuNTgyLS41MTQuNTgycy0uMzc4LS4wMzQtLjM3OC0uMTdjLS4wMzQtLjEzOC4zMDktLjA3LjI3NS0uMzc4LS4wMzUtLjIwNi0uMjQtLjI3NC0uNDQ2LS4yNzQtLjcyIDAtMS4xMzEuOTk0LTEuMDI5IDEuNjExLjAzNS4yNzUuMTcyLjU0OS40NDcuNTQ5LjIwNSAwIC41MTQtLjMxLjYxNy0uNzU1LjA2OC0uMzA4LjM0My0uNTE0LjU4My0uNTE0LjEwMiAwIC4xNy4wMzQuMjA1LjE3MXYuMTM4Yy0uMDM0LjEzNy0uMTM3LjU0OC0uMTAyLjY1MSAwIC4wNjkuMDM0LjE3MS4xNy4xNzEuMDkyIDAgLjQzNi0uMTguNzc3LS40NTkuMTE3LS41OS4yNTMtMS4yOTguMjUzLTEuMzU3LjAzNC0uMjQuMTM3LS40OC42MTctLjQ4LjEwMyAwIC4xNzEuMDM0LjIwNS4xNzF2LjEzOGwtLjEzNi42MTdjLjQ0NS0uNTgzIDEuMDk3LS45OTQgMS41MDgtLjk5NC4xNzIgMCAuMzA5LjEwMi4zMDkuMjc0IDAgLjEwMyAwIC4yNzQtLjA2OS40NDYtLjEzNy4zNzctLjMwOS45Ni0uNDEyIDEuNDc0IDAgLjEzNy4wMzUuMjc0LjIwNy4yNzQuMTcxIDAgLjY4NS0uMjA2IDEuMDk2LS43NTRsLjAwNy0uMDA0Yy0uMDAyLS4wNjgtLjAwNy0uMTM0LS4wMDctLjIwMiAwLS40MTEuMDM1LS43NTQuMTA0LS45OTQuMDY4LS4yNzQuNDExLS41MTQuNjE3LS41MTQuMTAzIDAgLjIwNS4wNjkuMjA1LjE3MSAwIC4wMzUgMCAuMTAzLS4wMzQuMTM3LS4xMzcuNDQ2LS4yNC44NTctLjI0IDEuMjY5IDAgLjI0LjAzNC41ODIuMTAyLjc4OCAwIC4wMzQuMDM1LjA2OS4wNy4wNjkuMDY4IDAgLjU0OC0uNDQ1Ljg5LTEuMDI4LS4zMDgtLjIwNi0uNDgtLjU0OS0uNDgtLjk2IDAtLjcyLjQ0Ni0xLjA5Ny44NTgtMS4wOTcuMzQzIDAgLjYxNy4yNC42MTcuNzIgMCAuMzA4LS4xMDMuNjUtLjI3NC45NmguMTAyYS43Ny43NyAwIDAgMCAuNTg0LS4yNC4yOTMuMjkzIDAgMCAxIC4xMzQtLjExN2MuMzM1LS40MjUuODMtLjc0IDEuNDEtLjc0LjQ4IDAgLjkyNC4yMDUuOTU5LjU4Mi4wNjguNTE1LS4zNzguNjE4LS41MTUuNjE4bC0uMDAyLS4wMDJjLS4xMzggMC0uMzc3LS4wMzUtLjM3Ny0uMTcyIDAtLjEzNy4zMDktLjA2OC4yNzQtLjM3Ni0uMDM0LS4yMDYtLjI0LS4yNzUtLjQ0Ni0uMjc1LS42ODYgMC0xLjEzLjg5MS0xLjAyOCAxLjYxMS4wMzQuMjc1LjE3MS41ODMuNDQ1LjU4My4yMDYgMCAuNTE1LS4zMDguNjUyLS43NTQuMDY4LS4yNzQuMzQzLS41MTQuNTgzLS41MTQuMTAzIDAgLjE3LjAzNC4yMDUuMTcxIDAgLjA2OSAwIC4yMDYtLjEzNy42NTItLjE3LjMwOC0uMTcxLjQ4LS4xMzcuNjE3LjAzNC4yNzQuMTcxLjQ4LjMwOS41ODMuMDM0LjAzNC4wNjguMTAyLjA2OC4xMDIgMCAuMDY5LS4wMzQuMTM4LS4xMzcuMTM4LS4wMzQgMC0uMDY4IDAtLjEwMy0uMDM1LS41MTQtLjIwNS0uNzItLjU0OC0uNzg5LS44OTEtLjIwNS4yNC0uNDQ1LjM3Ny0uNzIuMzc3LS40NDUgMC0uODktLjQxMS0uOTYtLjkyNmExLjYwOSAxLjYwOSAwIDAgMSAuMDc1LS42NDljLS4yMDMuMTMtLjQyMi4yMDMtLjYyMy4yMDNoLS4xN2MtLjQ0Ny42NTItLjkyNyAxLjA5OC0xLjI3IDEuMzAzYS44OTYuODk2IDAgMCAxLS4zNzcuMTA0Yy0uMDY4IDAtLjE3MS0uMDM1LS4yMDUtLjEwNC0uMDk1LS4xNTItLjE1Ni0uMzkyLS4xOTMtLjY2Ny0uNDgxLjUyNy0xLjE0NS44MDUtMS40NTMuODA1LS4zNDMgMC0uNTQ4LS4yMDYtLjU4Mi0uNTV2LS4zNzZjLjEwMi0uNzU0LjM3Ny0xLjIuMzc3LTEuMzM3YS4wNzQuMDc0IDAgMCAwLS4wNjktLjA3Yy0uMjQgMC0xLjAyOC44MjQtMS4xNjYgMS4zNzNsLS4xMDMuNDQ1Yy0uMDY4LjMwOS0uMzc3LjUxNS0uNTgyLjUxNS0uMTAzIDAtLjE3Mi0uMDM1LS4yMDYtLjE3MnYtLjEzN2wuMDQ2LS4yMzNjLS40MzUuMzEtLjg3LjUwOC0xLjA3NS41MDgtLjMwOCAwLS40OC0uMTcyLS41MTQtLjQxMi0uMjA2LjI3NC0uNDQ1LjQxMi0uNzU0LjQxMi0uMzUyIDAtLjY5Ni0uMjQtLjg2Mi0uNTkzLS4yNDQuMjc1LS41MjMuNTUzLS44NTIuNzY0LS40OC4zMDktMS4wMjguNTQ5LTEuNjguNTQ5LS41ODIgMC0xLjA5Ny0uMzA5LTEuMzcxLS41ODMtLjQxMi0uMzc3LS42NTEtLjk2LS42ODYtMS41MDktLjIwNS0xLjY4LjgyMy0zLjg0IDIuNC00LjguMzc4LS4yMDUuNzU1LS4zNDMgMS4xMzItLjM0M3ptOS43NyAzLjI5MWMtLjEwNCAwLS4xNzIuMTcyLS4xNzIuMzQzIDAgLjI3NC4xMzcuNTgzLjMwOS43NTVhMS43NCAxLjc0IDAgMCAwIC4xMDItLjU4M2MwLS4zNDMtLjEzNy0uNTE1LS4yNC0uNTE1eiIvPjwvc3ZnPg%3D%3D" alt="Canva" />
</p>

<sub>Also: Compact (Midnight), Soroban, Foundry, Hardhat, viem, wagmi, OpenZeppelin, Envio HyperIndex, and protocols like x402, EIP-3009, ERC-8004 and EIP-7702.</sub>

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=avishrakshe&theme=dark&background=0E0E11&border=24242A&ring=A08BFF&fire=A08BFF&currStreakLabel=A08BFF&hide_border=false&border_radius=12">
  <img alt="GitHub contribution streak" src="https://streak-stats.demolab.com/?user=avishrakshe&background=FAFAF7&border=E6E5DF&ring=6E56CF&fire=6E56CF&currStreakLabel=6E56CF&border_radius=12">
</picture>

---

<sub>Open to hackathon teams, internships and collaborations on agent payments, on-chain identity and anything where design meets protocol. The fastest way to reach me is on [LinkedIn](https://www.linkedin.com/in/avish-rakshe-92552b372/).</sub>
