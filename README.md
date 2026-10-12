<h1 align="center"> awesome-o1js</h1>

![awesome-o1js](o1js.jpeg)

**<p align="center">A curated list of libraries, projects and resources for o1js.</p>**

## Table of Contents

- [Tutorials &amp; Documentation](#tutorials--documentation)
  - [Blog Posts](#blog-posts)
  - [Examples](#examples)
  - [Tutorials](#tutorials)
- [Presentation &amp; Talks](#presentation--talks)
- [Papers](#papers)
- [Math](#math)
- [Cryptography](#cryptography)
  - [Encryption](#encryption)
  - [Key Exchange](#key-exchange)
  - [Key Generation](#key-generation)
  - [Signatures](#signatures)
  - [Hashing](#hashing)
  - [Authentication](#authentication)
  - [Provers and Verifiers](#provers-and-verifiers)
- [Data Structures](#data-structures)
- [Data Type Manipulation](#data-type-manipulation)
- [Privacy &amp; Security](#privacy--security)
- [Gaming](#gaming)
- [Dev Tooling](#dev-tooling)
- [Contributions](#contributions)

---

⚠️ Caution: This repository may include projects that have not undergone security audits, are
outdated or are no longer maintained. Use them at your own risk. Proceed with caution and consider
additional security measures.

ℹ️ Versions: Tags such as (o1js 2.x) show the o1js major version a project's default branch depends
on, as declared in its package.json (checked October 2026). o1js 3 targets the Mesa hard fork,
changes all verification keys and includes breaking API changes, so projects tagged with an earlier
version may need updating before they work with o1js 3. (SnarkyJS 0.x) marks a project that still
depends on SnarkyJS, the name o1js had before it was renamed.

---

## Tutorials & Documentation

### Blog Posts

- [Mastering o1js](https://medium.com/veridise/mastering-o1js-on-mina-four-key-strategies-for-secure-development-fff3a3f4f6d1) -
  A blog post about secure development.
- [ZkNoid Blog on Actions &amp; Reducers](https://medium.com/zknoid/mina-action-reducers-guide-why-we-need-them-81b6836c1700) -
  Blog post series on the use of actions and reducers.
- [Nullifiers in o1js](https://www.o1labs.org/blog/the-many-saints-of-privacy-nullifiers-in-o1js) -
  A blog post about Nullifiers.
- [Token Accounts](https://mackcee.substack.com/p/overcoming-mina-l1s-concurrency-limitations) - A
  blog post about Token Accounts and how to manage state.

### Tutorials

- [Onboarding to Mina](https://www.youtube.com/playlist?list=PLNwigD3FQvjBvYunrf_v2v7lGSeIOpAkx) -
  Video tutorial series about o1js zkApp development.
- [Mina Playground](https://www.minaplayground.com/) - Interactive o1js tutorials.

### Examples

- [Examples Folder](https://github.com/o1-labs/o1js/tree/main/src/examples) (o1js 3.x) - A
  subdirectory in the o1js repository that showcases example use cases of its functionalities.
- [Nextjs Integration Template](https://github.com/o1-labs-XT/next-js-integration-example) (o1js
  2.x) - A Next.js template using web workers.
- [Mina Name Service](https://github.com/o1-labs-XT/name-service-example) (o1js 2.x) - An
  implementation of a name service application that demonstrates the use of the
  [OffchainState API](https://docs.minaprotocol.com/zkapps/writing-a-zkapp/feature-overview/offchain-storage).
- [Mastermind zkApp Example Series](https://github.com/Shigoto-dev19/mina-mastermind/) (o1js 0.x) -
  An implementation of the Mastermind game as a series that explains different aspects of the o1js
  API.

## Presentation & Talks

- [o1js and ZK Coprocessors](https://www.youtube.com/watch?v=2OroIELozJg) -
  [Florian Kluge](https://x.com/zktrivo) on o1js and where it is used.
- [Building Stateful zkApps](https://www.youtube.com/watch?v=aMWDh4minG4) -
  [Boray Saygilier](https://x.com/boraysaygilier) on building zkApps with o1js.
- [What Makes Mina So Special?](https://www.youtube.com/watch?v=-fG0JLtYlJE) - Nathan Holland
  explains how Mina and o1js works.

## Papers

- [Mina Technical Whitepaper](https://minaprotocol.com/wp-content/uploads/technicalWhitepaper.pdf)

## Math

- [Math Operations](https://github.com/yunus433/o1js-math) (SnarkyJS 0.x) - A library for provable,
  generic and fundamental mathematical operations.
- [BigInt Operations](https://github.com/boray/o1js-bigint) (o1js 2.x) - A library for provable
  BigInt type and operations.
- [Matrix Operations](https://github.com/Vishalkulkarni45/o1js-matrix) (o1js 2.x) - A library for
  provable matrix operations.
- [GCD](https://github.com/PaimaStudios/o1js-gcd) (o1js 1.x) - A library for provable greatest
  common divisor (GCD) calculations.

## Cryptography

### Encryption

- [ChaCha20 Encryption](https://github.com/0x471/o1js-chacha20/tree/main) (o1js 1.x) - A library for
  provable ChaCha20 encryption scheme.
- [ElGamal Encryption](https://github.com/Trivo25/o1js-elgamal) (o1js 0.x) - A library for provable
  ElGamal encryption with multiplicative homomorphism.
- [RSA](https://github.com/Shigoto-dev19/o1js-rsa/tree/main) (o1js 1.x) - A library for provable
  RSA65537 signature verification.
- [AES-128](https://github.com/Raspberry-Devs/mina-aes) (o1js 2.x) - A library for provable AES-128
  encryption verification.

### Key Exchange

- [ECDH on Secp256k1](https://github.com/0x471/o1js-ecdh-secp256k1) (o1js 1.x) - A library for
  Elliptic Curve Diffie-Hellman key exchange on secp256k1.

### Key Generation

- [DKG for Threshold Homomorphic Encryption](https://github.com/auxo-zk/Distributed-key-generation)
  (o1js 0.x) - A library for distributed key generation. Generated keys can be used for Threshold
  Homomorphic Encryption.

### Signatures

- [Schnorr Signature Verification on secp256k1](https://github.com/0x471/o1js-schnorr-secp256k1)
  (o1js 2.x) - A library for verifying Bitcoin and Nostr (BIP340) signatures.
- [ECDSA on secp256k1](https://github.com/45930/ethereum-mina-signatures) (o1js 1.x) - A library for
  verifying Ethereum signatures.
- [EdDSA on Edwards25519](https://github.com/o1-labs-XT/eddsa-o1js) (o1js 2.x) - A library for
  verifying EdDSA signatures.

### Hashing

- [Dynamic SHA256](https://github.com/Shigoto-dev19/o1js-dynamic-sha256) (o1js 1.x) - A library for
  provable SHA256 hash function with dynamic-size inputs.
- [Reinforced Concrete](https://github.com/rymnc/reinforced-concrete-impls/) (o1js 0.x) - A library
  for provable Reinforced Concrete hash function.

### Authentication

- [HMAC-SHA256](https://github.com/o1-labs-XT/hmac-sha256-o1js) (o1js 2.x) - A library for provable
  hash-based message authentication code generation.
- [Passkey/WebAuthn](https://github.com/id-Mask/webauthn-o1js-example) (o1js 2.x) - Example
  integration using passkey verification and webauthn integration.

### Provers and Verifiers

- [Groth16 verifier](https://github.com/onurinanc/o1js-groth16) (o1js 0.x) - A library for Groth16
  proof verification.
- [SP1-Blobstream Verifier](https://github.com/geometers/o1js-blobstream) (o1js 1.x) - A library for
  verifying PLONK proofs generated by the SP1 zkVM for Celestia Blobstream. It also enables the
  verification of Groth16 proofs in o1js besides gnark-based PLONK proofs.

## Data Structures

- [Advanced Merkle Tree Structures](https://github.com/plus3-labs/o1js-merkle) (o1js 1.x) - A
  library for Sparse, Standard and Compact Merkle Tree.

## Data Type Manipulation

- [RegEx](https://github.com/Shigoto-dev19/zk-regex-o1js) (o1js 1.x) - A library for provable
  regular expression verification.
- [Base64](https://github.com/Shigoto-dev19/o1js-base64/tree/main) (o1js 1.x) - A library for
  provable Base64 encoding/decoding.

## Privacy & Security

- [Private Attestations Library](https://github.com/zksecurity/mina-attestations) (o1js 2.x) - A
  standard for anonymous credentials using ZK attestations.
- [RLN(Rate Limiting Nullifiers)](https://github.com/0x471/o1js-rln) (o1js 0.x) - An implementation
  enabling spam prevention in anonymous environments by limiting message rates.
- [zkEmail](https://github.com/zksecurity/mina-attestations/tree/main/src/email) (o1js 2.x) - An
  implementation enabling provable verification of emails to and from specific domains or subsets of
  domains, as well as verification based on specific text in the email body.
- [z2zlib](https://github.com/Yeshilabs/z2zlib/tree/version/0.0.1) - An implementation of provable
  and secure p2p state channels.
- [Anon Aadhaar in o1js](https://github.com/mina-builders-team/anon-aadhaar-o1js/) (o1js 2.x) - An
  implementation of the Anon Aadhaar protocol enabling Aadhaar users to generate proofs about their
  private identity data.

## Gaming

- [Effectstream (formerly Paima Engine)](https://github.com/effectstream/effectstream) - A framework
  for building provable gaming app-chains.
- [ZkNoid](https://github.com/ZkNoid/store) (o1js 1.x) - An SDK for provable game development.
- [Dice Roll](https://github.com/YofiY/zk-dice-roll) (o1js 1.x) - An implementation of a provable
  dice roll game.
- [2048](https://github.com/Chomtana/2048-o1js) (o1js 1.x) - An implementation of the provable 2048
  game.
- [Mina Puzzles](https://github.com/0xStruct/mina-puzzles) (o1js 0.x) - Implementation of provable
  puzzle games like Tic-Tac-Toe, Sudoku and more.

## Dev Tooling

- [zkApp CLI](https://github.com/o1-labs/zkapp-cli) (o1js 2.x) - A cli for kick-starting o1js zkApp.
- [Scaffold-Mina](https://github.com/wagmina/scaffold-mina) (o1js 1.x) - A starter kit for o1js
  zkApps development with web workers.
- [Data Packer](https://github.com/45930/o1js-pack) (o1js 2.x) - A library that enables packing
  extra data into a single Field.
- [Account Update Visualizer](https://github.com/ronykris/mina-account-update) (o1js 2.x) - A tool
  to visualize account updates a transaction performs.

## Contributions

The contribution guidelines can be found
[here](https://github.com/mina-builders-team/awesome-o1js/blob/main/CONTRIBUTING.md).
