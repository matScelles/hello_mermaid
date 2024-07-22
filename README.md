```mermaid
graph TD
  A[User] -->|Signs up / Casts bets| B[Next.js Frontend]
  B -->|Sends data| C[Node Backend]
  C -->|Interacts with| D[Solidity Smart Contract]
  C -->|Verifies| E[NFC Signatures]
  C -->|Fetches| F[Projects from Showcase]
```


https://mermaid.js.org/