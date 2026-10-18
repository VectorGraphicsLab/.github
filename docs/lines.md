# Research lines (public)

## CoverGAN

Generate album covers as **SVG** from audio tracks and selected emotions. Includes training code and an HTTP inference service used by the ML-VG web UI.

## VectorNST

Neural **style transfer** that works with vector graphics (DiffVG-based optimization), with a service API for demos.

## VectorWeaver

Generative models for SVG (VAE / diffusion-style, including class-conditional variants), with training code and a demo API.

## ML-VG Service (frontend)

A Remix web application that exposes CoverGAN, VectorNST, VectorWeaver, and an in-browser SVG editor behind one UI.

## SVG object extraction

Pipeline work to select drawable SVG primitives for a text query (open-vocabulary detection / segmentation → SVG leaf scoring). Used for research datasets and tooling.

Русская версия: [lines.ru.md](lines.ru.md)
