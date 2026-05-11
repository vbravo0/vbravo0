# Victor Bravo

[English](README.md) | [Español](README.es.md)

Data Engineer based in Buenos Aires. I build and maintain batch pipelines, Airflow DAGs, and data lake workflows in production financial environments.

B.Sc. in Systems Analysis from FIUBA (2024). Finishing the last stretch of a B.Eng. in Computer Science (FIUBA).

## Stack

**Production:** Python · SQL · PySpark · Apache Airflow · AWS S3 · Parquet · SQL Server  
**Cloud:** AWS · GCP (BigQuery, GCS, Dataproc)  
**Tooling:** Git · GitLab CI/CD · Docker

## Projects

### [Wave3](https://github.com/wave3org/wave3)
Decentralized music platform where fans invest in songs and collect royalties.  
Built on Base Sepolia (L2). Monorepo with 6 services:
- **Solidity contracts** — ERC-1155 royalty distribution, smart accounts, session keys for gasless playback
- **Ponder** — on-chain event indexer exposing a GraphQL API
- **FastAPI ML service** — hybrid recommendation engine: ALS + content features (genre, year) + FAISS
- **Storage API** — IPFS file management (local node / Pinata in prod)
- **Next.js frontend** — Scaffold-ETH 2
- **CI/CD** — GitHub Actions · Hardhat · Docker Compose · Render

### [Harpokrates](https://github.com/harpokrates-org)
Steganography detection using convolutional neural networks.
- CNN trained on stego/clean image pairs (Keras / TensorFlow)
- Model exported to TF.js and run client-side via WebAssembly (Rust/wasm-bindgen)
- Next.js frontend · Fastify backend · MongoDB · Docker · CI/CD

## Contact

[linkedin.com/in/victorbravoarroyo](https://linkedin.com/in/victorbravoarroyo) · victorbravolab@gmail.com · [CV (PDF)](cv-en.pdf)
