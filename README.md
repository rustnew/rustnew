<!--
  ╔══════════════════════════════════════════════════════════════════════╗
  ║   MARTIAL FOSSO · RUSTNEW · MLOPS / AIOPS / FINOPS ARCHITECT          ║
  ║   Rust Systems Engineer · AI Compiler Builder · ML Engineer          ║
  ╚══════════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=F74C00&center=true&vCenter=true&width=780&lines=Martial+Fosso+%E2%80%94+MLOps+%2F+AIOps+%2F+FinOps+Architect;Rust+Systems+Engineer+%7C+AI+Compiler+Builder;From+the+kernel+to+the+cluster.;From+Douala+to+the+world." alt="Typing SVG" />

<br/>

[![GitHub followers](https://img.shields.io/github/followers/rustnew?label=Follow&style=social)](https://github.com/rustnew)
[![Profile views](https://komarev.com/ghpvc/?username=rustnew&color=orange&style=flat)](https://github.com/rustnew)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![LLVM](https://img.shields.io/badge/-MLIR%2FLLVM-262D3A?style=flat-square&logo=llvm&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

</div>

---

### 📌 Table des matières
1. [Qui je suis](#-qui-je-suis)
2. [Ce que je peux faire pour vous](#-ce-que-je-peux-faire-pour-vous)
3. [Compétences clés](#️-compétences-clés)
4. [Projets phares](#-projets-phares)
5. [Boîte à outils complète](#️-boîte-à-outils-complète)
6. [Statistiques GitHub](#-statistiques-github)
7. [Mission actuelle](#-mission-actuelle--vision)
8. [Collaborer / Me contacter](#-collaborer-avec-moi)

---

## 🧠 Qui je suis

Je suis un **ingénieur systèmes orienté IA** (*Systems-first AI Engineer*). Là où la majorité des ingénieurs IA se concentrent sur les modèles, je me concentre sur **ce qui les fait tourner en production** : orchestration GPU distribuée, routage de cache KV, optimisation au niveau compilateur, et performance bas niveau en Rust.

Ma mission : **industrialiser l'IA**, la faire passer du prototype Jupyter au service de production fiable, mesurable et rentable.

- ✅ **MLOps / AIOps / FinOps** — je transforme des prototypes en plateformes souveraines, scalables et maîtrisées en coût (vLLM, LMCache, llm-d, Kubernetes).
- ✅ **Backend Rust haute performance** — j'écris des systèmes memory-safe à abstraction zero-cost (Actix-web, Tokio, `kube-rs`) conçus pour un haut débit avec une empreinte mémoire minimale.
- ✅ **Compilation IA** — je construis des compilateurs analytiques (NEURAX) qui prédisent FLOPs, VRAM et coût *avant* qu'un seul GPU ne démarre (MLIR, LLVM, CUDA/Triton).
- ✅ **Ingénierie ML** — je conçois et déploie des modèles (CNN, RNN, RL) de la recherche à la production, en construisant le pont entre le prototypage Python et l'exécution Rust (Burn, PyTorch).

---

## 💼 Ce que je peux faire pour vous

Si vous êtes une entreprise, une startup IA ou une équipe qui cherche à **fiabiliser et rentabiliser son infrastructure d'inférence LLM**, voici où je peux intervenir concrètement :

| Besoin | Ce que j'apporte |
| :--- | :--- |
| **Vos coûts GPU explosent** | Audit de l'infrastructure d'inférence, mise en place de cache-aware routing, disaggregation Prefill/Decode, dimensionnement piloté par les coûts. |
| **Votre stack Python est trop lente / trop lourde en mémoire** | Réécriture des composants critiques en Rust (Tokio, Actix-web, `kube-rs`) pour des services plus légers et plus prévisibles. |
| **Vous voulez éviter les `CUDA out of memory` en production** | Analyse statique des coûts mémoire/FLOPs avant déploiement grâce à des outils de compilation IA (NEURAX). |
| **Vous cherchez une souveraineté numérique (data locale, hardware maîtrisé)** | Conception de plateformes MLOps auto-hébergées, optimisées pour du matériel intermédiaire (RTX A2000/A4000), sans dépendance aux hyperscalers. |
| **Vous avez besoin d'un modèle ML sur-mesure** | Conception et entraînement de modèles (vision, séries temporelles, reinforcement learning) et intégration en production. |

📩 **Disponible pour des missions freelance, du conseil technique et des collaborations open source.** Voir la section [Collaborer](#-collaborer-avec-moi) plus bas.

---

## 🗺️ Compétences clés

| Pilier | Technologies & concepts | Ce que je fais concrètement |
| :--- | :--- | :--- |
| **MLOps / AIOps / FinOps** | `Kubernetes` `Helm` `vLLM` `LMCache` `llm-d` `KEDA` `Karpenter` `Prometheus` `Grafana` `Tempo` | Conception de clusters GPU souverains, routage cache-aware (disaggregation P/D), réduction des coûts GPU, automatisation d'opérations auto-cicatrisantes (*self-healing*). |
| **Rust haute performance** | `Rust 1.85+` `Tokio` `Actix-web` `kube-rs` `candle` `serde` `clap` `Rayon` | Backends natifs à faible empreinte mémoire, zéro data race, démarrage à froid en millisecondes pour des microservices IA. |
| **Compilation & IR pour l'IA** | `MLIR` `LLVM` `CUDA` `Triton` `ONNX` `Représentations intermédiaires` | Construction de pipelines IR (NEURAX, Lift) pour analyser le coût des tenseurs, optimiser des workflows hybrides quantique-classique, générer des kernels. |
| **Ingénierie Machine Learning** | `PyTorch` `TensorFlow` `ONNX` `Burn` `MuJoCo` `PPO` `CNN/LSTM` `Diffusers` | Implémentation de stacks d'inférence, reinforcement learning (marche bipède), vision par ordinateur médicale, diffusion texte-image en Rust/Python hybride. |

---

## 🚀 Projets phares

| Projet | Stack | Ce qu'il résout |
| :--- | :--- | :--- |
| **⚡ [Custom-Ai-Ops](https://github.com/rustnew/Custom-Ai-Ops)** | `Rust` `K8s` `vLLM` `LMCache` `llm-d` `Envoy` | **Plateforme MLOps souveraine.** Orchestre vLLM avec LLM-d pour un routage cache-aware. Implémente un cache KV hiérarchique (L0/L1/L2) pour réduire les coûts d'inférence GPU. Inclut des tableaux de bord FinOps et des contrôleurs auto-cicatrisants. |
| **🧮 [NEURAX](https://github.com/rustnew/NEURAX)** | `Rust` `MLIR` `LLVM` | **Compilateur analytique.** Prédit statiquement FLOPs, VRAM, latence et coût d'entraînement de tout réseau de neurones — avant même le chargement du modèle. |
| **🌀 [Lift](https://github.com/rustnew/Lift)** | `Rust` `IR` `Quantique` `Tenseurs` | **Représentation intermédiaire unifiée.** Fait le pont entre IA classique (opérations tensorielles) et informatique quantique (opérations sur portes). Export vers ONNX, LLVM et OpenQASM. |
| **🚶 [SAPGGO](https://github.com/rustnew/SAPGGO)** | `Rust` `MuJoCo` `PPO` `RL` | **Reinforcement learning pour la marche bipède.** Inspiré des traditions africaines de portage de charges sur la tête. Apprend à un agent MuJoCo à marcher sur terrain accidenté avec un équilibre dynamique. |
| **🩺 [Malaria Detection AI](https://github.com/rustnew/Malaria_model_2)** | `Rust` `Burn` `CNN` | **Vision par ordinateur médicale en Rust pur.** Classification d'images de cellules sanguines (parasitées / saines) avec le framework de deep learning `Burn`, sans runtime Python. |
| **🕸️ [Rust_network](https://github.com/rustnew/Rust_network)** | `Rust` `ndarray` `Backprop` | **Réseaux de neurones from scratch.** Implémentation complète de la passe avant/arrière en Rust pour la prédiction de séries temporelles financières — démonstration de la maîtrise de l'autodiff et du calcul matriciel. |

---

## 🛠️ Boîte à outils complète

<details>
<summary><b>🦀 Écosystème Rust</b></summary>

- **Web / Réseau** : `tokio`, `actix-web`, `axum`, `hyper`, `tonic` (gRPC)
- **Kubernetes** : `kube-rs` (controllers, watchers, reflectors), `k8s-openapi`
- **ML & IA** : `candle`, `burn`, `tch-rs`, `ndarray`, `nalgebra`
- **CLI & outils** : `clap`, `serde`, `anyhow`, `thiserror`, `rayon`, `cross`
- **Compilation** : `inkwell` (bindings LLVM), IR SSA maison
- **Performance** : `criterion` (benchmarks), `flamegraph` (profiling)

</details>

<details>
<summary><b>☸️ Cloud Native & MLOps</b></summary>

- **Orchestration** : Kubernetes, Helm, ArgoCD, Karpenter, Volcano, KEDA
- **Serving ML** : vLLM, SGLang, LMCache, llm-d, Envoy Gateway
- **Observabilité** : Prometheus, Grafana, Loki, Tempo, OpenTelemetry
- **Stockage** : Longhorn, MinIO, Delta-rs, PostgreSQL
- **GPU** : NVIDIA Operator, CUDA, DCGM, NIXL/RDMA

</details>

---

## 📊 Statistiques GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=rustnew&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rustnew&layout=compact&theme=radical&hide_border=true&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rustnew&theme=radical&hide_border=true" alt="streak stats" />

</div>

---

## 🏆 Mission actuelle & vision

> *« La souveraineté n'est pas qu'une question politique ; c'est une question d'infrastructure. »*

Je travaille actuellement sur **Custom-Ai-Ops**, une architecture de référence pour la **souveraineté numérique africaine en IA** : une plateforme MLOps open source, clé en main, capable de tourner efficacement sur du matériel intermédiaire (RTX A2000/A4000), réduisant la dépendance aux hyperscalers étrangers tout en gardant les données locales, sécurisées et maîtrisées en coût.

**Axes d'exploration actifs :**
- Disaggregation Prefill/Decode avec des sidecars Rust.
- Compilateurs de modèles de coût (NEURAX) pour le FinOps GPU.
- Déploiement Edge-AI en Rust sur ARM — construire le pont entre le cloud et les infrastructures rurales.

---

## 🤝 Collaborer avec moi

Je suis toujours ouvert à collaborer sur des projets **open source Rust**, d'**infrastructure IA** et de **souveraineté numérique** — et disponible pour des missions de conseil ou de développement.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/VOTRE-PROFIL)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:votre-email@domaine.com)
[![Mastodon](https://img.shields.io/badge/-Mastodon-6364FF?style=for-the-badge&logo=mastodon&logoColor=white)](https://hachyderm.io/@rustnew)

</div>

---

<div align="center">
<i>— Du kernel au cluster. De Douala au monde. —</i>
</div>
