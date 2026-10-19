# Vector Graphics Lab

Public face of the [VectorGraphicsLab](https://github.com/VectorGraphicsLab) organization (ITMO University).

**[Читать на русском →](https://github.com/VectorGraphicsLab/.github/blob/main/profile/README.ru.md)**

We work on **vector graphics + ML**: generative SVG, style transfer in the vector domain, text-guided editing/extraction, and web tooling around these models.

## Public code

| Project | Description | Repository |
|---------|-------------|------------|
| **SVG object extraction** | Text-guided object extraction from existing SVG (raster grounding → leaf prune) | [VectorGraphicsLab/svg-object-extractor](https://github.com/VectorGraphicsLab/svg-object-extractor) |
| **CoverGAN** | Album covers as SVG from audio and emotions | [IzhanVarsky/CoverGAN](https://github.com/IzhanVarsky/CoverGAN) (train) · [ML-VG-CoverGAN-service-backend](https://github.com/IzhanVarsky/ML-VG-CoverGAN-service-backend) (serve) |
| **VectorNST** | Neural style transfer for vector graphics | [IzhanVarsky/VectorNST](https://github.com/IzhanVarsky/VectorNST) |
| **VectorWeaver** | Generative SVG (class-conditional) | [IzhanVarsky/VectorWeaverClassConditional](https://github.com/IzhanVarsky/VectorWeaverClassConditional) |
| **ML-VG frontend** | Web UI for the vector-ML demos | [IzhanVarsky/ML-VG-service-frontend](https://github.com/IzhanVarsky/ML-VG-service-frontend) |
| **diffvg** | Differentiable vector graphics rasterization (fork) | [IzhanVarsky/diffvg](https://github.com/IzhanVarsky/diffvg) |

Related library (CTLab-ITMO, not yet under this org): [CTLab-ITMO/VGLib](https://github.com/CTLab-ITMO/VGLib) — ML methods for vector graphics processing/generation.

## Selected papers / workshop artifacts

Private camera-ready / poster packs live under `VectorGraphicsLab/paper-*` (archived after submission). Highlights:

| Venue | Topic | Repo |
|-------|--------|------|
| CVEU @ CVPR 2026 | Text-guided SVG object extraction (EA) | [paper-2026-cvpr-cveu--svg-extraction](https://github.com/VectorGraphicsLab/paper-2026-cvpr-cveu--svg-extraction) |
| ICML 2026 HAIcoCr | Object-level access to SVG scenes (benchmark + method) | [paper-2026-icml-haicocr--svg-extraction](https://github.com/VectorGraphicsLab/paper-2026-icml-haicocr--svg-extraction) |
| ICML 2026 HAIcoCr | SVG-BERT | [paper-2026-icml-haicocr--svgbert](https://github.com/VectorGraphicsLab/paper-2026-icml-haicocr--svgbert) |
| VISAPP / extensions | CoverGAN, VectorNST, VectorWeaver, … | see org `paper-2024-*` / `paper-2025-*` |

Full inventory of paper repos: local `meta/papers/` on the lab host (mirrored from Overleaf archives).

## Research lines

Short descriptions: [docs/lines.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.md) · [на русском](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.ru.md)

Public repo index: [docs/repos.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/repos.md)

## Elsewhere

- **Hugging Face:** [VectorGraphics](https://huggingface.co/VectorGraphics) — datasets and models when published
- **GitLab:** [vectorgraphicslab](https://gitlab.jarskylab.ru/vectorgraphicslab)
