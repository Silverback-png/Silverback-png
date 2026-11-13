### Hi, I'm Drikus

Self-taught developer in South Africa. I build desktop and web software, and I work **AI-first**: I direct coding agents to implement, then verify what they produce with tests and manual review rather than trusting it.

Most of what I've shipped is software that had to work offline, on real hardware, for real businesses — which is where the "prove it" habit comes from.

**TypeScript · Python · Rust · Electron · Tauri · Flask · SQLite · Flutter**

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| **[ManaPOS](https://github.com/Silverback-png/ManaPOS)** | Offline-first desktop point-of-sale. Sales, inventory, reporting, PDF receipts, manager-PIN voids with audit logging, automatic backups. No cloud, no internet required. Packaged and shipped v1.0.0. | Electron · React · TypeScript · SQLite |
| **[Kwartel](https://github.com/Silverback-png/kwartel)** | A UTXO blockchain built from scratch — Ed25519, SHA-256, Merkle trees, CPU proof-of-work, and a peer-to-peer TCP gossip network with partition/heal. **202 tests passing.** | Python |
| **[Mana CRM](https://github.com/Silverback-png/mana-crm)** | Client pipeline manager that audits prospect websites and refuses to report any finding it cannot prove from the visible page. | Flask · SQLite |
| **PROTEA** | Voice-driven desktop command centre for a locally hosted LLM agent harness — speech in, spoken replies out, live agent state. | Tauri · Rust |
| **Commercial websites** | Designed, built and deployed end to end — including [manasoftware.co.za](https://manasoftware.co.za), [newgenewaste.co.za](https://newgenewaste.co.za) and [soberlivingangels.co.za](https://soberlivingangels.co.za). | HTML · CSS · JS · Netlify |

---

## How I work

- **Test-first where it counts.** Kwartel's 202 tests exist because no module shipped without a failing test first.
- **Verify agent output, don't trust it.** Running `pytest` and reading the diff is not optional.
- **Fail closed.** If a claim can't be demonstrated, drop it rather than soften it — a habit from doing client-facing work.
- **Ship something that runs.** A working thing that a person can click beats an elegant thing that only exists on paper.

---

📧 djdrikus9@gmail.com · 🌍 South Africa · 🏢 [Mana Software](https://manasoftware.co.za)
