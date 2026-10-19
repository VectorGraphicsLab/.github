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

Авторы и площадки — по опубликованному PDF / camera-ready, где они есть. Приватные архивы подач на эту страницу не выносим.

### Принято / опубликовано

| Год | Название | Авторы | Площадка / статус | Ссылки |
|-----|----------|--------|-------------------|--------|
| 2026 | Object-Level Access to SVG Scenes: A Benchmark and Raster-Grounded Method for Text-Guided Vector Object Extraction | Ivan Jarsky, Boris Malashenko, Boris Timofeenko, Viacheslav Shalamov, Valeria Efimova | ICML 2026 HAIcoCr; также МНИЖ (IRJ, RU) | [ICML](https://icml.cc/virtual/2026/68581) · [PDF](https://genaicreativity.org/icml2026/files/33/33_paper.pdf) · [IRJ DOI](https://doi.org/10.60797/irj.2026.169.21) · [код](https://github.com/VectorGraphicsLab/svg-object-extractor) |
| 2026 | Text-Guided Object Extraction in SVG via Raster Grounding and Filtering Primitives | Ivan Jarsky, Boris Timofeenko, Boris Malashenko, Valeria Efimova | CVEU @ CVPR 2026, Extended Abstract (не в proceedings CVPR) | [список CVEU](https://cveu.github.io/event/cvpr2026.html) · [код](https://github.com/VectorGraphicsLab/svg-object-extractor) |
| 2026 | SVG-BERT: Code-Native Representations for Structure-Aware Vector Graphics Workflows | Boris Malashenko, Ivan Jarsky, Viacheslav Shalamov, Valeria Efimova | ICML 2026 HAIcoCr | [ICML](https://icml.cc/virtual/2026/68586) · [PDF](https://genaicreativity.org/icml2026/files/43/43_paper.pdf) |
| 2025 | VectorWeaver 2: Towards Class-Conditional Generation of Vector Graphics | Ivan Jarsky, Boris Malashenko, Viacheslav Shalamov, Valeria Efimova | VISAPP / VISIGRAPP extended — принято, публикация pending | [связанный код](https://github.com/IzhanVarsky/VectorWeaverClassConditional) |
| 2025 | VectorWeaver: Transformers-Based Diffusion Model for Vector Graphics Generation | Ivan Jarsky, Maxim Kuzin, Valeria Efimova, Viacheslav Shalamov, Andrey Filchenkov | VISAPP 2025 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2025/131851/131851.pdf) · [DOI](https://doi.org/10.5220/0013185100003912) · [INSTICC](https://www.insticc.org/node/TechnicalProgram/VISIGRAPP/2025/presentationDetails/131851) · [код](https://github.com/IzhanVarsky/VectorWeaverClassConditional) |
| 2025 | Leveraging Large Language Models For Scalable Vector Graphics Processing: A Review | Boris Malashenko, Ivan Jarsky, Valeria Efimova | arXiv + Записки научн. сем. ПОМИ 546 (2025) | [arXiv](https://arxiv.org/abs/2503.04983) · [Math-Net](https://www.mathnet.ru/php/archive.phtml?jrnid=znsl&paperid=7630&option_lang=eng) |
| 2025 | SVG-BERT: Representation Learning for Scalable Vector Graphics | Boris Malashenko, Ivan Jarsky, Viacheslav Shalamov, Valeria Efimova | VISAPP — принято; в SciTePress не публиковали (см. версию ICML HAIcoCr выше) | — |
| 2024 | Advancements in Vector Graphics Generation for Music Cover Art | Ivan Jarsky, Artem Treschev, Viacheslav Shalamov, Valeria Efimova | Расширенная глава VISIGRAPP, Springer CCIS | [Springer](https://link.springer.com/chapter/10.1007/978-3-032-07623-6_19) · [DOI](https://doi.org/10.1007/978-3-032-07623-6_19) · [код](https://github.com/IzhanVarsky/CoverGAN) |
| 2024 | Conditional Vector Graphics Generation for Music Cover Images | Ivan Jarsky, Valeria Efimova, Ilya Bizyaev, Andrey Filchenkov | VISAPP 2024 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2024/124561/124561.pdf) · [DOI](https://doi.org/10.5220/0012456100003660) · [arXiv](https://arxiv.org/abs/2205.07301) · [код](https://github.com/IzhanVarsky/CoverGAN) |
| 2024 | Neural Style Transfer for Vector Graphics | Ivan Jarsky, Valeria Efimova, Artyom Chebykin, Viacheslav Shalamov, Andrey Filchenkov | VISAPP 2024 (VISIGRAPP) | [SciTePress PDF](https://www.scitepress.org/Papers/2024/124382/124382.pdf) · [DOI](https://doi.org/10.5220/0012438200003660) · [arXiv](https://arxiv.org/abs/2303.03405) · [код](https://github.com/IzhanVarsky/VectorNST) |
| 2024 | EvoVec: Evolutionary Image Vectorization with Adaptive Curve Number and Color Gradients | Egor Bazhenov, Ivan Jarsky, Valeria Efimova, Sergey Muravyov | PPSN 2024 (Springer LNCS) | [Springer](https://link.springer.com/chapter/10.1007/978-3-031-70085-9_24) · [DOI](https://doi.org/10.1007/978-3-031-70085-9_24) · [код](https://github.com/EgorBa/EvoVec-Evolutionary-Image-Vectorization) |
| 2024 | Evolutionary image vectorization with variable curve number | Egor Bazhenov, Ivan Jarsky, Valeria Efimova, Sergey Muravyov | GECCO 2024 Companion | [код](https://github.com/EgorBa/EvoVec-Evolutionary-Image-Vectorization) |
| 2023 | Image Vectorization: a Review | Maria Dziuba, Ivan Jarsky, Valeria Efimova, Andrey Filchenkov | Зап. научн. сем. ПОМИ 530 (2023); перевод J. Math. Sci. 2024 | [arXiv](https://arxiv.org/abs/2306.06441) · [Math-Net](https://www.mathnet.ru/php/archive.phtml?jrnid=znsl&option_lang=eng&paperid=7429&wshow=paper) · [J. Math. Sci. DOI](https://doi.org/10.1007/s10958-024-07422-4) |
| 2022 | Conditional Vector Graphics Generation for Music Cover Images | Valeria Efimova, Ivan Jarsky, Ilya Bizyaev, Andrey Filchenkov | AI4CC @ CVPR 2022 (poster; не в proceedings CVPR) | [расписание воркшопа](https://ai-for-content-creation.github.io/2022/#schedule) · [arXiv](https://arxiv.org/abs/2205.07301) · [код](https://github.com/IzhanVarsky/CoverGAN) |

### Прочее (отклонённые / оставлены для reuse)

Внутри для возможного переиспользования; публичной страницы статьи нет.

| Год | Название | Площадка / статус |
|-----|----------|-------------------|
| 2026 | Semantic-SVG-BERT: A Source-Aware Encoder for SVG Retrieval Pipelines | Rejected at ReNeuIR @ SIGIR 2026 |
| 2025 | VectorTDAM: Vector Technical Drawing Analyzer with Memory | Rejected at ECML-PKDD 2025 |

## Направления исследований

Кратко: [docs/lines.ru.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.ru.md) · [English](https://github.com/VectorGraphicsLab/.github/blob/main/docs/lines.md)

Индекс публичных реп: [docs/repos.ru.md](https://github.com/VectorGraphicsLab/.github/blob/main/docs/repos.ru.md)

## Где ещё

- **Hugging Face:** [VectorGraphics](https://huggingface.co/VectorGraphics)
- **GitLab:** [vectorgraphicslab](https://gitlab.jarskylab.ru/vectorgraphicslab)
