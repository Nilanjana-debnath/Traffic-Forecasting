# Traffic Forecasting with PyTorch Geometric Temporal

## Project Overview

This project implements a traffic forecasting model using temporal graph neural networks (GNNs) with the PyTorch Geometric Temporal library. The primary objective is to predict future traffic speeds based on historical data collected from sensors in metropolitan areas, specifically focusing on Los Angeles.

## Key Features

- **Temporal Graph Neural Networks:** Leverages advanced GNN architectures to capture spatial and temporal dependencies in traffic data.
- **Metropolitan LA Dataset:** Utilizes a dataset comprising traffic speed measurements from 207 sensors at five-minute intervals, providing a rich source of real-time traffic data.
- **Model Variants:** Implements both single-shot and autoregressive prediction models to enhance forecasting accuracy.

## Installation

To set up the project, ensure you have the following dependencies installed:

```bash
pip install torch torchvision torchaudio
pip install torch-geometric
pip install torch-geometric-temporal
