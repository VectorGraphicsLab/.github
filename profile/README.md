# Vector Graphics Lab

Public face of the [VectorGraphicsLab](https://github.com/VectorGraphicsLab) organization (ITMO University).

**[Читать на русском →](https://github.com/VectorGraphicsLab/.github/blob/main/profile/README.ru.md)**

We work on **vector graphics + ML**: generative SVG, style transfer in the vector domain, text-guided editing/extraction, and web tooling around these models.

## Public code

| Project | Description | Repository |
|---------|-------------|------------|
| **SVG object extraction** | Text-guided object extraction from existing SVG (raster grounding → leaf prune) | [VectorGraphicsLab/svg-object-extractor](https://github.com/VectorGraphicsLab/svg-object-extractor) |
| **VGLib** | ML methods for vector graphics processing/generation (fork of CTLab-ITMO) | [VectorGraphicsLab/VGLib](https://github.com/VectorGraphicsLab/VGLib) · upstream [CTLab-ITMO/VGLib](https://github.com/CTLab-ITMO/VGLib) |
| **CoverGAN** | Album covers as SVG from audio and emotions | [IzhanVarsky/CoverGAN](https://github.com/IzhanVarsky/CoverGAN) (train) · [ML-VG-CoverGAN-service-backend](https://github.com/IzhanVarsky/ML-VG-CoverGAN-service-backend) (serve) |
| **VectorNST** | Neural style transfer for vector graphics | [IzhanVarsky/VectorNST](https://github.com/IzhanVarsky/VectorNST) |
| **VectorWeaver** | Generative SVG (class-conditional) | [IzhanVarsky/VectorWeaverClassConditional](https://github.com/IzhanVarsky/VectorWeaverClassConditional) |
| **ML-VG frontend** | Web UI for the vector-ML demos | [IzhanVarsky/ML-VG-service-frontend](https://github.com/IzhanVarsky/ML-VG-service-frontend) |
| **diffvg** | Differentiable vector graphics rasterization (fork) | [IzhanVarsky/diffvg](https://github.com/IzhanVarsky/diffvg) |

## Papers

Authors and venues follow the published PDF / camera-ready where available. Private submission archives stay off this page.

### Accepted / published

| Year | Title | Authors | Venue / status | Links |
|------|-------|---------|----------------|-------|
| 2026 | Object-Level Access to SVG Scenes: A Benchmark and Raster-Grounded Method for Text-Guided Vector Object Extraction | Ivan Jarsky, Boris Malashenko, Boris Timofeenko, Viacheslav Shalamov, Valeria Efimova | ICML 2026 Workshop on Human-AI Co-Creativity (HAIcoCr); also IRJ (RU) | [ICML](https://icml.cc/virtual/2026/68581) · [PDF](https://genaicreativity.org/icml2026/files/33/33_paper.pdf) · [IRJ DOI](https://doi.org/10.60797/irj.2026.169.21) · [code](https://github.com/VectorGraphicsLab/svg-object-extractor) |
| 2026 | Text-Guided Object Extraction in SVG via Raster Grounding and Filtering Primitives | Ivan Jarsky, Boris Timofeenko, Boris Malashenko, Valeria Efimova | CVEU workshop @ CVPR 2026, Extended Abstract (not in CVPR proceedings) | [CVEU listing](https://cveu.github.io/event/cvpr2026.html) · [code](https://github.com/VectorGraphicsLab/svg-object-extractor) |
| 2026 | SVG-BERT: Code-Native Representations for Structure-Aware Vector Graphics Workflows | Boris Malashenko, Ivan Jarsky, Viacheslav Shalamov, Valeria Efimova | ICML 2026 HAIcoCr workshop | [ICML](https://icml.cc/virtual/2026/68586) · [PDF](https://genaicreativity.org/icml2026/files/43/43_paper.pdf) |
| 2025 | VectorWeaver 2: Towards Class-Conditional Generation of Vector Graphics | Ivan Jarsky, Boris Malashenko, Viacheslav Shalamov, Valeria Efimova | VISAPP / VISIGRAPP extended track — accepted, publication pending | [related code](https://github.com/IzhanVarsky/VectorWeaverClassConditional) |
| 2025 | VectorWeaver: Transformers-Based Diffusion Model for Vector Graphics Generation | Ivan Jarsky, Maxim Kuzin, Valeria Efimova, Viacheslav Shalamov, Andrey Filchenkov | VISAPP 2025 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2025/131851/131851.pdf) · [DOI](https://doi.org/10.5220/0013185100003912) · [INSTICC](https://www.insticc.org/node/TechnicalProgram/VISIGRAPP/2025/presentationDetails/131851) · [code](https://github.com/IzhanVarsky/VectorWeaverClassConditional) |
| 2025 | Leveraging Large Language Models For Scalable Vector Graphics Processing: A Review | Boris Malashenko, Ivan Jarsky, Valeria Efimova | arXiv + Zap. Nauchn. Sem. POMI 546 (2025) | [arXiv](https://arxiv.org/abs/2503.04983) · [Math-Net](https://www.mathnet.ru/php/archive.phtml?jrnid=znsl&paperid=7630&option_lang=eng) |
| 2025 | SVG-BERT: Representation Learning for Scalable Vector Graphics | Boris Malashenko, Ivan Jarsky, Viacheslav Shalamov, Valeria Efimova | VISAPP — accepted; not published in SciTePress (see ICML HAIcoCr version above) | — |
| 2024 | Advancements in Vector Graphics Generation for Music Cover Art | Ivan Jarsky, Artem Treschev, Viacheslav Shalamov, Valeria Efimova | VISIGRAPP extended chapter, Springer CCIS | [Springer](https://link.springer.com/chapter/10.1007/978-3-032-07623-6_19) · [DOI](https://doi.org/10.1007/978-3-032-07623-6_19) · [code](https://github.com/IzhanVarsky/CoverGAN) |
| 2024 | Conditional Vector Graphics Generation for Music Cover Images | Ivan Jarsky, Valeria Efimova, Ilya Bizyaev, Andrey Filchenkov | VISAPP 2024 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2024/124561/124561.pdf) · [DOI](https://doi.org/10.5220/0012456100003660) · [arXiv](https://arxiv.org/abs/2205.07301) · [code](https://github.com/IzhanVarsky/CoverGAN) |
| 2024 | Neural Style Transfer for Vector Graphics | Ivan Jarsky, Valeria Efimova, Artyom Chebykin, Viacheslav Shalamov, Andrey Filchenkov | VISAPP 2024 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2024/124382/124382.pdf) · [DOI](https://doi.org/10.5220/0012438200003660) · [arXiv](https://arxiv.org/abs/2303.03405) · [code](https://github.com/IzhanVarsky/VectorNST) |
| 2024 | EvoVec: Evolutionary Image Vectorization with Adaptive Curve Number and Color Gradients | Egor Bazhenov, Ivan Jarsky, Valeria Efimova, Sergey Muravyov | PPSN 2024 (Springer LNCS) | [Springer](https://link.springer.com/chapter/10.1007/978-3-031-70085-9_24) · [DOI](https://doi.org/10.1007/978-3-031-70085-9_24) · [code](https://github.com/EgorBa/EvoVec-Evolutionary-Image-Vectorization) |
| 2024 | Evolutionary image vectorization with variable curve number | Egor Bazhenov, Ivan Jarsky, Valeria Efimova, Sergey Muravyov | GECCO 2024 Companion | [code](https://github.com/EgorBa/EvoVec-Evolutionary-Image-Vectorization) |
| 2023 | Image Vectorization: a Review | Maria Dziuba, Ivan Jarsky, Valeria Efimova, Andrey Filchenkov | Zap. Nauchn. Sem. POMI 530 (2023); J. Math. Sci. translation 2024 | [arXiv](https://arxiv.org/abs/2306.06441) · [Math-Net](https://www.mathnet.ru/php/archive.phtml?jrnid=znsl&option_lang=eng&paperid=7429&wshow=paper) · [J. Math. Sci. DOI](https://doi.org/10.1007/s10958-024-07422-4) |
| 2022 | Conditional Vector Graphics Generation for Music Cover Images | Valeria Efimova, Ivan Jarsky, Ilya Bizyaev, Andrey Filchenkov | AI4CC workshop @ CVPR 2022 (poster; not in CVPR proceedings) | [workshop schedule](https://ai-for-content-creation.github.io/2022/#schedule) · [arXiv](https://arxiv.org/abs/2205.07301) · [code](https://github.com/IzhanVarsky/CoverGAN) |

### Other (rejected / unpublished keeps)

Kept internally for reuse; no public paper page.

| Year | Title | Venue / status |
|------|-------|----------------|
| 2026 | Semantic-SVG-BERT: A Source-Aware Encoder for SVG Retrieval Pipelines | Rejected at ReNeuIR @ SIGIR 2026 |
| 2025 | VectorTDAM: Vector Technical Drawing Analyzer with Memory | Rejected at ECML-PKDD 2025 |

## Research lines

Short descriptions: [docs/lines.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.md) · [на русском](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.ru.md)

Public repo index: [docs/repos.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/repos.md)

## Elsewhere

- **Hugging Face:** [VectorGraphics](https://huggingface.co/VectorGraphics) — datasets and models when published
- **GitLab:** [vectorgraphicslab](https://gitlab.jarskylab.ru/vectorgraphicslab)
