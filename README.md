# Binance Skills Hub

Binance Skills Hub is an open skills marketplace that gives AI agents native access to crypto: both centralized and decentralized. Search tokens, execute trades, track wallets, monitor signals, and manage onchain workflows through modular skills.

Built by Binance. Built for everyone.

We're not building this just for Binance products. Skills Hub is designed for the entire crypto ecosystem: any agent, any framework, any chain. Whether you're building on LangChain, CrewAI, or your own stack, the project gives your AI agents native access to crypto tooling.

---

## About This Repository

Each skill lives in its own folder and contains a `SKILL.md` file with YAML frontmatter and structured instructions.

Browse the existing skills to understand patterns and naming conventions before contributing.

---

## Installation

Get started with Binance Skills Hub in a single command. Works with various agents such as OpenClaw and Claude Code.

### Prerequisites

Before installing Binance Skills Hub, ensure you have the following prerequisites:

* **Node.js** (version 22 or higher)

### Install Skills Hub

Run the following command to add Binance Skills Hub to your project:

```bash
npx skills add https://github.com/binance/binance-skills-hub
```

### Authentication

For Binance Skills, certain endpoints require you to provide Binance API credentials. You can do this by setting environment variables, using a secrets file (such as `.env` or `.openclaw/secrets.env`), or using the default platform secret vault when supported.

---

## Commercialization

This repository is ready to be packaged for commercial distribution as a premium skill catalog for individuals, developers, and enterprises.

### Commercial offer

The repository can be offered under the following model:

- Starter: single-user license for one or more skills
- Pro: full skill suite for developers and automation builders
- Enterprise: custom integration, installation support, and SLA-backed assistance

### Available commercial docs

- `LICENSE.md` — commercial license template
- `TERMS_OF_SERVICE.md` — terms of service
- `PRIVACY_POLICY.md` — privacy policy
- `REFUND_POLICY.md` — refund policy
- `INSTALLATION.md` — installation and setup guide
- `commercial/index.html` — landing page for sales

Important: replace the placeholder payment links in the landing page with your own Mercado Pago links before publishing publicly.

### Disclaimer

This repository is not an official Binance product and is not endorsed or sponsored by Binance in a commercial distribution context. Any commercial use should be reviewed by legal counsel and aligned with the upstream project licensing and your own compliance process.

---

## Contribution

We welcome contributions.

To add a new skill:

1. **Fork the repository** and create a new branch:

   ```bash
   git checkout -b feature/<skill-name>
   ```

2. **Create a new folder** containing a `SKILL.md` file.

3. **Follow the required format:**

   ```markdown
   ---
   title: <Skill Name>
   description: A clear description of what the skill does and when to use it.
   metadata:
     version: <Skill Version>
     author: <Your Github Username>
   license: MIT
   ---

   # <Skill Name>

   [Add instructions, examples, and guidelines here]
   ```

4. **Open a Pull Request** to `main` for review.
   Once approved, the skill will be merged.

---

## Disclaimer

Binance Skills Hub is an informational tool only. Binance Skills Hub and its outputs are provided to you on an "as is" and "as available" basis, without representation or warranty of any kind, express or implied. This repository is maintained as a skill collection and does not constitute financial, legal, or investment advice.

---

## Commercial contact

Before selling or distributing this repository commercially, review the local licensing, compliance, and support requirements and update the public landing page with your payment links, support contact, and refund policy.

This repository includes a basic commercial-ready starter kit to help you package the skills for sale to users, developers, and enterprise customers.

