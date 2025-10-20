HSI–EBS Fusion Research Review

This repository contains the LaTeX source files and figures for the research paper "Integration of Hyperspectral Imaging (HSI) and Event-Based Sensing (EBS) for Real-Time Ecological Monitoring".
The project explores novel methodologies for combining hyperspectral imaging and event-based sensing to enable efficient, high-fidelity, and real-time data acquisition in dynamic environmental conditions.

Overview

The research focuses on:

Integration of HSI and EBS for wildlife and ecological monitoring.

Development of a spectral–temporal fusion pipeline.

Implementation of Total Variation–Cascaded Denoiser (TV–CD) reconstruction algorithms.

Evaluation using real-world field experiments and simulated datasets.

Project Structure
HSI-EBS-Fusion-Research-Review/
│
├── main.tex                 # Main LaTeX source file
├── references.bib           # Bibliography file
├── figures/                 # All figures and diagrams
│   ├── HSI_EBS_system.png
│   ├── Spectral_Temporal_Fusion.png
│   ├── Sweeping_Rainbow.png
│   └── other images...
├── .gitignore               # Ignore temporary and build files
└── README.md                # This file

⚙️ Requirements

To compile the LaTeX document:

TeXLive or MiKTeX

Packages: IEEEtran, graphicx, booktabs, amsmath, hyperref, etc.

Optional: Overleaf or local LaTeX editor (VSCode + LaTeX Workshop plugin)

How to Build

If you are building locally:

pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex


The compiled paper will be available as main.pdf.

Author

TORONTOSHAH
Kazakhstan, 2025
Contact: via GitHub Issues or Discussions

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Обзор исследований по интеграции HSI–EBS

Этот репозиторий содержит исходные файлы LaTeX и изображения для научной работы «Интеграция гиперспектральной съёмки (HSI) и событийных сенсоров (EBS) для мониторинга экосистем в реальном времени».
Проект исследует современные методы объединения данных гиперспектральных камер и событийных датчиков для эффективного и точного анализа природных объектов.

Описание

Основные направления исследования:

Интеграция HSI и EBS для мониторинга дикой природы.

Разработка спектрально-временного конвейера (fusion pipeline).

Использование алгоритма TV–CD (Total Variation–Cascaded Denoiser) для восстановления изображений.

Экспериментальная проверка на реальных данных и моделях.

Структура проекта
HSI-EBS-Fusion-Research-Review/
│
├── main.tex                 # Основной LaTeX-файл
├── references.bib           # Список литературы
├── figures/                 # Изображения и диаграммы
│   ├── HSI_EBS_system.png
│   ├── Spectral_Temporal_Fusion.png
│   ├── Sweeping_Rainbow.png
│   └── другие изображения...
├── .gitignore               # Игнорируемые файлы
└── README.md                # Этот файл

⚙️ Требования

Для компиляции документа:

Установленный TeXLive или MiKTeX

Пакеты: IEEEtran, graphicx, booktabs, amsmath, hyperref и др.

Можно использовать Overleaf или локальный редактор (например, VSCode + LaTeX Workshop)

Как собрать

Если работаешь локально:

pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex


Готовый документ появится в файле main.pdf.

Автор

TORONTOSHAH
Казахстан, 2025
Связь: через Issues или Discussions на GitHub
