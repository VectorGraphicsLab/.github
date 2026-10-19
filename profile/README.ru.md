# Vector Graphics Lab

Публичная витрина организации [VectorGraphicsLab](https://github.com/VectorGraphicsLab) (Университет ИТМО).

**[Read in English →](https://github.com/VectorGraphicsLab/.github/blob/main/profile/README.md)**

Мы занимаемся **векторной графикой и ML**: генеративный SVG, перенос стиля, text-guided редактирование/извлечение объектов и веб-инструменты вокруг этих моделей.

## Публичный код

| Проект | Описание | Репозиторий |
|--------|----------|-------------|
| **SVG object extraction** | Извлечение объектов из SVG по тексту (raster grounding → leaf prune) | [VectorGraphicsLab/svg-object-extractor](https://github.com/VectorGraphicsLab/svg-object-extractor) |
| **VGLib** | Методы ML для обработки/генерации векторной графики (fork CTLab-ITMO) | [VectorGraphicsLab/VGLib](https://github.com/VectorGraphicsLab/VGLib) · upstream [CTLab-ITMO/VGLib](https://github.com/CTLab-ITMO/VGLib) |
| **CoverGAN** | Обложки альбомов в SVG по аудио и эмоциям | [IzhanVarsky/CoverGAN](https://github.com/IzhanVarsky/CoverGAN) (обучение) · [ML-VG-CoverGAN-service-backend](https://github.com/IzhanVarsky/ML-VG-CoverGAN-service-backend) (сервис) |
| **VectorNST** | Нейронный перенос стиля для векторной графики | [IzhanVarsky/VectorNST](https://github.com/IzhanVarsky/VectorNST) |
| **VectorWeaver** | Генеративный SVG (class-conditional) | [IzhanVarsky/VectorWeaverClassConditional](https://github.com/IzhanVarsky/VectorWeaverClassConditional) |
| **ML-VG frontend** | Веб-UI для демо vector-ML | [IzhanVarsky/ML-VG-service-frontend](https://github.com/IzhanVarsky/ML-VG-service-frontend) |
| **diffvg** | Дифференцируемая растеризация (fork) | [IzhanVarsky/diffvg](https://github.com/IzhanVarsky/diffvg) |

## Статьи

Приватные camera-ready / постеры: `VectorGraphicsLab/paper-*` (обычно archived после сдачи). Авторы и площадки — по опубликованному PDF / camera-ready, где они есть.

### Принято / опубликовано

| Год | Название | Авторы | Площадка / статус | Ссылки | Репозиторий |
|-----|----------|--------|-------------------|--------|-------------|
| 2026 | Object-Level Access to SVG Scenes: A Benchmark and Raster-Grounded Method for Text-Guided Vector Object Extraction | Ivan Jarsky, Boris Malashenko, Boris Timofeenko, Viacheslav Shalamov, Valeria Efimova | ICML 2026 HAIcoCr; также МНИЖ (IRJ, RU) | [ICML](https://icml.cc/virtual/2026/68581) · [PDF](https://genaicreativity.org/icml2026/files/33/33_paper.pdf) · [IRJ DOI](https://doi.org/10.60797/irj.2026.169.21) · код: [svg-object-extractor](https://github.com/VectorGraphicsLab/svg-object-extractor) | [paper-2026-icml-haicocr--svg-extraction](https://github.com/VectorGraphicsLab/paper-2026-icml-haicocr--svg-extraction) |
| 2026 | Text-Guided Object Extraction in SVG via Raster Grounding and Filtering Primitives | Ivan Jarsky, Boris Timofeenko, Boris Malashenko, Valeria Efimova | CVEU @ CVPR 2026, Extended Abstract (не в proceedings CVPR) | [список CVEU](https://cveu.github.io/event/cvpr2026.html) | [paper-2026-cvpr-cveu--svg-extraction](https://github.com/VectorGraphicsLab/paper-2026-cvpr-cveu--svg-extraction) |
| 2026 | SVG-BERT: Code-Native Representations for Structure-Aware Vector Graphics Workflows | Boris Malashenko, Ivan Jarsky, Viacheslav Shalamov, Valeria Efimova | ICML 2026 HAIcoCr | [ICML](https://icml.cc/virtual/2026/68586) · [PDF](https://genaicreativity.org/icml2026/files/43/43_paper.pdf) | [paper-2026-icml-haicocr--svgbert](https://github.com/VectorGraphicsLab/paper-2026-icml-haicocr--svgbert) |
| 2025 | VectorWeaver 2: Towards Class-Conditional Generation of Vector Graphics | Ivan Jarsky, Boris Malashenko, Viacheslav Shalamov, Valeria Efimova | VISAPP / VISIGRAPP extended — принято, публикация pending | — | [paper-2025-visapp-ext--vectorweaver2](https://github.com/VectorGraphicsLab/paper-2025-visapp-ext--vectorweaver2) |
| 2025 | VectorWeaver: Transformers-Based Diffusion Model for Vector Graphics Generation | Ivan Jarsky, Maxim Kuzin, Valeria Efimova, Viacheslav Shalamov, Andrey Filchenkov | VISAPP 2025 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2025/131851/131851.pdf) · [DOI](https://doi.org/10.5220/0013185100003912) · [INSTICC](https://www.insticc.org/node/TechnicalProgram/VISIGRAPP/2025/presentationDetails/131851) · код: [VectorWeaverClassConditional](https://github.com/IzhanVarsky/VectorWeaverClassConditional) | [paper-2025-visapp--vectorweaver](https://github.com/VectorGraphicsLab/paper-2025-visapp--vectorweaver) |
| 2025 | Leveraging Large Language Models For Scalable Vector Graphics Processing: A Review | Boris Malashenko, Ivan Jarsky, Valeria Efimova | arXiv + Записки научн. сем. ПОМИ 546 (2025) | [arXiv](https://arxiv.org/abs/2503.04983) · [Math-Net](https://www.mathnet.ru/php/archive.phtml?jrnid=znsl&paperid=7630&option_lang=eng) | [paper-2025-ainl--llm-svg-review](https://github.com/VectorGraphicsLab/paper-2025-ainl--llm-svg-review) |
| 2025 | SVG-BERT: Representation Learning for Scalable Vector Graphics | Boris Malashenko, Ivan Jarsky, Viacheslav Shalamov, Valeria Efimova | VISAPP — принято; в SciTePress не публиковали (см. версию ICML HAIcoCr) | — | [paper-2025-visapp--svgbert](https://github.com/VectorGraphicsLab/paper-2025-visapp--svgbert) |
| 2024 | Advancements in Vector Graphics Generation for Music Cover Art | Ivan Jarsky, Artem Treschev, Viacheslav Shalamov, Valeria Efimova | Расширенная глава VISIGRAPP, Springer CCIS | [Springer](https://link.springer.com/chapter/10.1007/978-3-032-07623-6_19) · [DOI](https://doi.org/10.1007/978-3-032-07623-6_19) · код: [CoverGAN](https://github.com/IzhanVarsky/CoverGAN) | [paper-2024-visapp-ext--covergan-advancements](https://github.com/VectorGraphicsLab/paper-2024-visapp-ext--covergan-advancements) |
| 2024 | Conditional Vector Graphics Generation for Music Cover Images | Ivan Jarsky, Valeria Efimova, Ilya Bizyaev, Andrey Filchenkov | VISAPP 2024 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2024/124561/124561.pdf) · [DOI](https://doi.org/10.5220/0012456100003660) · [arXiv](https://arxiv.org/abs/2205.07301) · код: [CoverGAN](https://github.com/IzhanVarsky/CoverGAN) | [paper-2024-visapp--covergan](https://github.com/VectorGraphicsLab/paper-2024-visapp--covergan) |
| 2024 | Neural Style Transfer for Vector Graphics | Ivan Jarsky, Valeria Efimova, Artyom Chebykin, Viacheslav Shalamov, Andrey Filchenkov | VISAPP 2024 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2024/124382/124382.pdf) · [DOI](https://doi.org/10.5220/0012438200003660) · [arXiv](https://arxiv.org/abs/2303.03405) · код: [VectorNST](https://github.com/IzhanVarsky/VectorNST) | [paper-2024-visapp--vectornst](https://github.com/VectorGraphicsLab/paper-2024-visapp--vectornst) |
| 2024 | EvoVec: Evolutionary Image Vectorization with Adaptive Curve Number and Color Gradients | Egor Bazhenov, Ivan Jarsky, Valeria Efimova, Sergey Muravyov | PPSN 2024 (Springer LNCS) | [Springer](https://link.springer.com/chapter/10.1007/978-3-031-70085-9_24) · [DOI](https://doi.org/10.1007/978-3-031-70085-9_24) · код: [EvoVec](https://github.com/EgorBa/EvoVec-Evolutionary-Image-Vectorization) | [paper-2024-ppsn--evovec](https://github.com/VectorGraphicsLab/paper-2024-ppsn--evovec) |
| 2024 | Evolutionary image vectorization with variable curve number | Egor Bazhenov, Ivan Jarsky, Valeria Efimova, Sergey Muravyov | GECCO 2024 Companion | код: [EvoVec](https://github.com/EgorBa/EvoVec-Evolutionary-Image-Vectorization) | [paper-2024-gecco--evovec](https://github.com/VectorGraphicsLab/paper-2024-gecco--evovec) |
| 2023 | Image Vectorization: a Review | Maria Dziuba, Ivan Jarsky, Valeria Efimova, Andrey Filchenkov | Зап. научн. сем. ПОМИ 530 (2023); перевод J. Math. Sci. 2024 | [arXiv](https://arxiv.org/abs/2306.06441) · [Math-Net](https://www.mathnet.ru/php/archive.phtml?jrnid=znsl&option_lang=eng&paperid=7429&wshow=paper) · [J. Math. Sci. DOI](https://doi.org/10.1007/s10958-024-07422-4) | [paper-2023-ainl--vectorization-survey](https://github.com/VectorGraphicsLab/paper-2023-ainl--vectorization-survey) |
| 2022 | Conditional Vector Graphics Generation for Music Cover Images | Valeria Efimova, Ivan Jarsky, Ilya Bizyaev, Andrey Filchenkov | AI4CC @ CVPR 2022 (poster; не в proceedings CVPR) | [расписание воркшопа](https://ai-for-content-creation.github.io/2022/#schedule) · [arXiv](https://arxiv.org/abs/2205.07301) · код: [CoverGAN](https://github.com/IzhanVarsky/CoverGAN) | [paper-2022-cvpr-ai4cc--covergan](https://github.com/VectorGraphicsLab/paper-2022-cvpr-ai4cc--covergan) |

### Отклонённые / оставлены для reuse

| Год | Название | Авторы | Площадка / статус | Ссылки | Репозиторий |
|-----|----------|--------|-------------------|--------|-------------|
| 2026 | Semantic-SVG-BERT: A Source-Aware Encoder for SVG Retrieval Pipelines | в исходниках anonymous (double-blind) | Rejected at ReNeuIR @ SIGIR 2026 | — | [paper-2026-sigir-reneuir--semantic-svgbert](https://github.com/VectorGraphicsLab/paper-2026-sigir-reneuir--semantic-svgbert) |
| 2025 | VectorTDAM: Vector Technical Drawing Analyzer with Memory | в исходниках anonymous (double-blind) | Rejected at ECML-PKDD 2025 | — | [paper-2025-ecmlpkdd--vectortdam](https://github.com/VectorGraphicsLab/paper-2025-ecmlpkdd--vectortdam) |

## Направления исследований

Кратко: [docs/lines.ru.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.ru.md) · [English](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.md)

Индекс публичных реп: [docs/repos.ru.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/repos.ru.md)

## Где ещё

- **Hugging Face:** [VectorGraphics](https://huggingface.co/VectorGraphics)
- **GitLab:** [vectorgraphicslab](https://gitlab.jarskylab.ru/vectorgraphicslab)
