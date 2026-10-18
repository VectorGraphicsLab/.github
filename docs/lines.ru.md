# Направления исследований (публично)

## CoverGAN

Генерация обложек альбомов в **SVG** по аудиодорожке и выбранным эмоциям. Есть код обучения и HTTP-сервис инференса для веб-UI ML-VG.

## VectorNST

Нейронный **перенос стиля** для векторной графики (оптимизация на DiffVG) и API сервиса для демо.

## VectorWeaver

Генеративные модели SVG (VAE / diffusion-подобные, в т.ч. class-conditional): обучение и demo API.

## ML-VG Service (frontend)

Веб-приложение на Remix: CoverGAN, VectorNST, VectorWeaver и встроенный SVG-редактор в одном UI.

## SVG object extraction

Пайплайн выбора drawable SVG-примитивов по текстовому запросу (open-vocabulary detection / segmentation → scoring leaf). Для исследовательских датасетов и тулинга.

English: [lines.md](lines.md)
