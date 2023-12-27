# [Nomad3](https://nomad3.vercel.app)
⛓️ Chaining your memories together ⛓️

## What is **Nomad3**? 🤔
 
![Dancing Monkey](https://drive.google.com/uc?export=view&id=12V8hjGPMa-qIjqzry0kscsRz1X44TTXU) 
<br /><br />
Nomad3 is a platform that lets event nomads forge meaningful memorable connections. It's designed for enthusiasts of web3 events and conferences, enabling them to authenticate their attendance, manage event interactions, and create lasting memories on the blockchain. 


## Project Description 📔
### ❗❗ Problem Statement ❗❗
The web3 event landscape currently lacks a comprehensive platform for attendees to authenticate their presence, manage their event interactions, and create lasting memories in a unified and meaningful way.

### ✨✨ Vision ✨✨
Nomad3 aims to transform the web3 event experience. It offers a unique platform for users to authenticate their event attendance, manage past and upcoming events, connect with fellow attendees, and create a digital narrative of their event journey.

### ✔️✔️ Unique Value Proposition ✔️✔️
Nomad3 distinguishes itself with several innovative features:

- **Seamless Wallet Connectivity**: Facilitates user authentication and interaction through embedded wallet address connections, offering a streamlined user experience and removing the need for private keys and long seed phrases.

- **ERC-6551 Token-Bound Account (TBA) Deployment**: Upon claiming an event NFT, a TBA is automatically deployed for each user. This account acts as a personal hub for managing event-related activities, including adding new connections and uploading pictures.

- **Personalized NFT Profiles**: Each user's event journey is captured and represented as a unique NFT profile, created using the ERC-6551 contract, providing a verifiable and personal record of their event experiences.

- **Event Interaction Management**: The TBA enables users to manage their event interactions, including recording connections made at events, stored in an organized array.

- **IPFS-Enabled Photo Sharing**: Users can upload pictures from events, which are stored as IPFS hashes, ensuring a decentralized and permanent storage solution. This feature allows users to revisit and cherish their event memories securely and reliably.

## How It's Made 🦿
The platform's functionality follows a specific flow:

1. **Event Registration by Organizers**: Organizers register events in the Nomad3Drops contract, receiving an eventID.
2. **Event NFT Claim by Participants**: Participants claim their event NFT using the eventID, triggering the automatic deployment of a TBA.
3. **Interaction with TBA**: Participants use an interface and address combination to interact with their TBA, creating and managing their event experiences.
4. **Connection and Picture Management**: The TBA allows for the addition of connections and the uploading of pictures, with the latter stored as IPFS hashes for decentralized and secure access.

Nomad3 is more than an app; it's a comprehensive platform for web3 event enthusiasts to capture, share, and relive their experiences, fostering a community of connected, engaged participants in the evolving digital interaction landscape.

## Features Utilisation 🌟

### For Event Attendees
As an Event Attendee, you can:
- **Collect Event POPs**: Securely gather digital proofs of presence from Web3 events you attend.
- **Review Event Histories**: Access a chronological display of both past and upcoming events, categorized by year.
- **Create and Manage Your NFT Profile**: Utilize the ERC-6551 contract to develop and maintain a unique NFT that represents your event journey.
- **Network and Connect**: View and manage connections made at various events, enhancing your networking experience.
- **Access Photo Galleries**: Relive memories from events through a user-friendly photo gallery feature.

### For Event Organizers
As an Event Organizer, you can:
- **List Your Event**: Make your event visible to a wide audience of Web3 enthusiasts.
- **Interact with Attendees**: Engage with participants, collect feedback, and provide updates on future events.
- **Monitor Event POPs**: Track the distribution and collection of POPs by attendees, ensuring a seamless experience.

**Note**: Every interaction and connection made on the app will contribute to the user's profile, enriching their Web3 event journey.

## The Stack ⚙️

- **Package-Manager**: `Node Package Manager (NPM)`
- **Smart Contract Development**: `foundry` `remix` 
- **Network**: `viction`
- **Frontend**: Developed using `Next.js` for a robust and responsive user interface.
- **Contract Interactions**: `thirdweb`
- **Styling**: Implemented using `tailwindcss` for a sleek and modern design.

## Smart Contracts Deployments 🌳

**[ERC6551 Registry](https://testnet.vicscan.xyz/address/0xBAF8DD01C6f1AFbFae4FADc4800c182387cf9962)**  

**[ERC6551 Account](https://testnet.vicscan.xyz/address/0x87FE9a73d69da217895110Ecbbe363B51a78FAAA)** 

**[Nomad3Drops](https://testnet.vicscan.xyz/address/0xbc97C3c3a9c9C020B6a573bf5993ab751330F1b6)** 

**[Nomad3](https://testnet.vicscan.xyz/address/0xC27ef22b7c0CD3c0296DBa772987b142a71Eff48)** 

**[Sample Token Bound Account](https://testnet.vicscan.xyz/address/0x75dFC61417A32224196ccE4e0CB2081CCFa843A2)** 
