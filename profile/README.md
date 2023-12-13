## (🌱) Wayve - The ESG funds governing protocol

### ETHGlobal Istanbul Project Showcase

https://ethglobal.com/showcase/wayve-4kzwf

### Intro 👋

What is Wayve?

Wayve is a protocol that empowers consumer loyalty points with the ability to govern Environmental, Social, and Governance (ESG) funds.

### Project Description 📔

❗❗ Problem Statement

This project aims to tackle 2 key problems with how ESG initiatives are being carried out.

1. Currently, the ESG initiatives being carried out by businesses & corporations are opaque. There is no easy way for the general public to verify and audit the ESG efforts done or the impact they have made.

2. Furthermore, there is a lack of clear, open standards to achieve a unified ESG goal. For instance, achieving net zero by 2050 requires concerted effort. Without a unified approach, the positive impact one business makes may be nullified by another business without proper coordination.

✨✨ Vision

Wayve aims to empower consumers with the ability to direct ESG funds towards creating positive impact on the world and society, publicly attest to the impacts of successful ESG initiatives, with open standards and metrics for impact measurement across the value chain, and streamline the gathering, evaluation, and reporting of ESG data in accordance with ESRSs in an appropriate and auditable manner.

✔️✔️ Unique Value Proposition

We duplicate the familiar loyalty points system already present in our daily lives, and putting them onchain as ERC-20 tokens, ensuring interoperability across the Ethereum ecosystem. Account Abstraction enables ordinary consumers to easily vote on the allocation of ESG funds, all while safeguarding private and sensitive user data with zero-knowledge identity.

### How It's Made 🧰

To achieve the vision, we leveraged several cutting-edge technology provided by our sponsors:

1. **Safe Account Abstraction SDK & WalletConnect SDK & Base Paymaster** - Handles user smart wallet creation and onchain transactions (+ gas sponsors) without the user needing to know how to use Ethereum. On the vendor's side, it enables seamless issuance of loyalty points to consumers, submission of ESG proposals onchain, and publishing loyalty points issuance policy.
2. **Worldcoin & Mina Protocol** - A zero-knowledge proof is generated for user's private and sensitive data alongside its biometrics info (or finger print). The proof is then assigned a unique World ID to represent the unique user. Users can then seamlessly confirm onchain transactions with just their finger print, without exposing any of their personal information.
3. **IPFS & Filecoin** - The ESG proposals created are stored permanently on a decentralized file storage via lighthouse.storage to ensure permanent accessibility of the proposals.
4. **ERC-6551 Token-Bound Accounts** - Upon user smart wallet creation, a global loyalty card compliant with the ERC-6551 Token-Bound Accounts standard is created, and the loyalty points are transferred under its control. This ensures that all the loyalty points received in this protocol are unified and controllable under a single NFT portfolio view, instead of having a scattered view of all the tokens showing up under the user's smart wallet view.
5. **ENS & Nouns** - To make onchain interactions more fun and friendly, the app supports the display of ENS names and subnames, as well as adopting a Nounish approach to make it more fun to interact with.
6. **Ethereum Attestation Service** - Once the proposals have been successfully executed, results will be periodically submitted onchain for verification by the general public. The general public can then collectively attest whether the ESG initiatives being executed have positively impacted their quality of life.

### The Stack ⚙️


### Deployments 🚀

Live Demo


Smart Contracts

**Arbitrum Goerli**: 0x544515BB43Cd609a351abeD097a2d43C1C75a994 _(erc6551 account implementation)_

**Base Goerli**: 0x07A2C46436F6fc96848E9ee32DAdA491B5CE2aEd _(Account Abstraction)_ & Paymaster: https://paymaster.base.org

**Celo Alfajores**: 0x000000006551c19487814612e58FE06813775758 _(erc6551 registry)_ & 0xB4954D821815f7DEC998E08c8c3D303DCF0E6586 _(erc6551 account implementation)_ & 0x07A2C46436F6fc96848E9ee32DAdA491B5CE2aEd _(Account Abstraction)_

**Gnosis Chain**: 0x544515BB43Cd609a351abeD097a2d43C1C75a994 _(erc6551 account implementation)_

**Linea Goerli**: 0x07A2C46436F6fc96848E9ee32DAdA491B5CE2aEd _(Account Abstraction)_ & Paymaster: https://paymaster.base.org

**Mantle**: 0x000000006551c19487814612e58FE06813775758 _(erc6551 registry)_ & 0xB4954D821815f7DEC998E08c8c3D303DCF0E6586 _(erc6551 account implementation)_

**Neon EVM testnet**: 0x054419ffbaaec39fa32e45a873eef8cfebcac7a0 _(erc6551 registry)_ & 0x2FAF333249e0e1c41aa2efc5697a0Fce2Ebaa87f _(erc6551 account implementation)_

**Polygon zkEVM testnet**: 0x000000006551c19487814612e58FE06813775758 _(erc6551 registry)_ & 0xB4954D821815f7DEC998E08c8c3D303DCF0E6586 _(erc6551 account implementation)_

**Scroll Sepolia**: 0x30F53D30C8aE4a8Ad6115117aEc1FE62db7e6AE1 _(erc6551 account implementation)_

**zkSync Era testnet**: 0x8b7900E312111A7e94C6006BB9e468A54105Eb1e _(erc6551 registry)_

### Getting Started 💪

_We recommend installing Wayve by building from the source code as follows:_

```bash
# Download the source code
git clone https://github.com/wayve-ethglobal-ist/wayve-app
cd wayve-app

# Install dependencies
npm install --legacy-peer-deps

# Run app
npm run dev
```
