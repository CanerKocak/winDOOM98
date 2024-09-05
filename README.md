# DOOM on the Internet Computer

![image](https://github.com/user-attachments/assets/653cd88a-f1a0-4d8d-bac5-d416dfbdc10f)

Experience the classic DOOM game running on the Internet Computer blockchain!

[Play the Demo](https://uc2wh-kaaaa-aaaag-alc4q-cai.icp0.io/)

## About the Project

This project brings the iconic DOOM game to the Internet Computer, demonstrating the potential of blockchain technology for gaming. We've adapted the [Cloudflare DOOM WASM](https://github.com/cloudflare/doom-wasm) project to run on the IC network, showcasing what's possible with a bit of creativity and blockchain integration.

### Features

- DOOM running entirely on the blockchain
- First level available (stripped down for size optimization)
- Demonstrates blockchain capabilities in gaming

### Performance Notes

- Building and compiling may be slow due to the nature of blockchain technology
- Once running, gameplay is smooth
- Average request size is max 2MB for fetching all assets
- Blockchain finality rate is around 2 seconds

## Getting Started

### Prerequisites

- [DFINITY Canister SDK](https://sdk.dfinity.org/docs/quickstart/local-quickstart.html)
- Node.js and npm

### Installation

```bash
# 1. Clone the repository:
git clone https://github.com/your-username/doom-windoge.git
cd doom-windoge

# 2. Install dependencies:
npm install

# 3. Start the local Internet Computer replica:
dfx start --background

# 4. Deploy the canisters so its served via dfx
dfx deploy

# 5. Open the dapp in your browser served via npm
npm start
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements

- Original DOOM by id Software
- [Cloudflare DOOM WASM](https://github.com/cloudflare/doom-wasm) project
- DFINITY Foundation for the Internet Computer
