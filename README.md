# PM Particles Approximation (PM2.5 & PM10)

This repository contains ML experiments focused on approximating air pollution particulate matter concentrations (PM2.5 and PM10).

## Project Description

Data for this project comes from multiple real-world datasets collected from different countries and regions. The goal is not to build a single one-dataset model, but to analyze general patterns in PM predictions across diverse data sources.

## Modeling Approach

Two separate experiments are provided:

| Notebook | Description |
|----------|-------------|
| `notebooks/PM2_5.ipynb` | Experiments on PM2.5 forecasting |
| `notebooks/PM10.ipynb` | Experiments on PM10 forecasting |

The best performance in current experiments was achieved using an **ensemble** approach (combining multiple models).

This repository is currently used primarily for **experimental ML research** (category A).

## Installation and Running

Clone the repository:

```bash
git clone https://github.com/outofdanger/pm_particles_aproximation.git
cd pm_particles_aproximation

### Install Dependencies

```bash
pip install -r requirements.txt

pm_particles_aproximation/
├── notebooks/
│   ├── PM2_5.ipynb
│   └── PM10.ipynb
├── requirements.txt
├── .gitignore
└── README.md

##Notes on Data
Datasets used in experiments are not included in this repository due to size and license constraints.

You are expected to mount/load your own PM datasets in Colab or locally.

##After installing dependencies, you can run the Jupyter notebooks
