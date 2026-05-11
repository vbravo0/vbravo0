# Victor Bravo

[English](README.md) | [Español](README.es.md)

Data Engineer en Buenos Aires. Construyo y mantengo pipelines batch, DAGs en Airflow y flujos de Data Lake en entornos financieros productivos.

## Stack

**Producción:** Python · SQL · PySpark · Apache Airflow · AWS S3 · Parquet · SQL Server  
**Cloud:** AWS · GCP (BigQuery, GCS, Dataproc)  
**Herramientas:** Git · GitLab CI/CD · Docker

## Proyectos

### [Wave3](https://github.com/wave3org/wave3)
Plataforma de música descentralizada donde los fans invierten en canciones y cobran regalías.  
Construida sobre Base Sepolia (L2). Monorepo con 6 servicios:
- **Contratos Solidity** — distribución de regalías ERC-1155, smart accounts, session keys para reproducción sin gas
- **Ponder** — indexador de eventos on-chain con API GraphQL
- **Servicio ML en FastAPI** — recomendaciones híbridas: ALS + features de contenido (género, año) + FAISS
- **Storage API** — gestión de archivos en IPFS (nodo local / Pinata en producción)
- **Frontend Next.js** — Scaffold-ETH 2
- **CI/CD** — GitHub Actions · Hardhat · Docker Compose · Render

### [Harpokrates](https://github.com/harpokrates-org)
Detección de esteganografía en imágenes mediante redes neuronales convolucionales.
- CNN entrenada sobre pares de imágenes con y sin esteganografía (Keras / TensorFlow)
- Modelo exportado a TF.js e inferencia en el cliente vía WebAssembly (Rust/wasm-bindgen)
- Frontend Next.js · Backend Fastify · MongoDB · Docker · CI/CD

### [Portal 2D](https://github.com/mechanix97/Portal-Taller-de-Programacion-9508-FIUBA) *(FIUBA — Taller de Programación)*
Clon multijugador de Portal con arquitectura cliente-servidor en C++.
- SDL2 para renderizado, Qt para el editor de niveles, YAML-cpp para configuración de mapas
- Networking sobre sockets, build con CMake, tests unitarios con CxxTest
- [Demo en YouTube](https://www.youtube.com/watch?v=zYuNiUTCyk0) · [Listado en la página oficial de la cátedra (FIUBA)](https://taller-de-programacion.github.io/trabajos-practicos)

## Contacto

[linkedin.com/in/victorbravoarroyo](https://linkedin.com/in/victorbravoarroyo) · victorbravolab@gmail.com · [CV (PDF)](cv-es.pdf)
