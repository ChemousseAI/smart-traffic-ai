# Smart Traffic AI: Intelligent Transportation Using Computer Vision, Reinforcement Learning, and Graph Neural Networks

[![Python](https://img.shields.io/badge/Python-3.10+-blue)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-orange)](#)
[![YOLOv8](https://img.shields.io/badge/YOLO-v8-green)](#)
[![PPO](https://img.shields.io/badge/Reinforcement%20Learning-PPO-red)](#)
[![GNN](https://img.shields.io/badge/Graph%20Neural%20Networks-GNN-purple)](#)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

🚦 Intelligent Transportation Systems | 👁️ Computer Vision | 🤖 Reinforcement Learning | 🕸️ Graph Neural Networks


---

## Overview

This repository presents a collection of experiments exploring the application of Artificial Intelligence techniques to intelligent transportation systems and smart-city traffic management.

The project investigates three key aspects of modern traffic systems:

- Vehicle detection using Computer Vision
- Adaptive traffic signal control using Reinforcement Learning
- Traffic flow forecasting using Graph Neural Networks



## Objectives

The primary objectives of this project are:

- Detect and analyze traffic conditions using deep learning-based computer vision.
- Optimize traffic signal decisions through reinforcement learning.
- Forecast traffic dynamics using graph-based neural networks.
- Explore how multiple AI paradigms can contribute to smart-city infrastructure.


## Notebook 1: Smart City AI Pipeline

### Description

This notebook demonstrates an integrated AI pipeline for intelligent traffic management by combining multiple machine learning paradigms.

### Components

#### Vehicle Detection

- YOLOv8-based object detection
- Vehicle identification from traffic scenes
- Traffic state extraction

#### Adaptive Signal Control

- Reinforcement Learning using Proximal Policy Optimization (PPO)
- Dynamic decision-making for traffic-light management
- Optimization of traffic flow through learned policies

#### Traffic Forecasting

- Graph Neural Networks (GNNs)
- Modeling traffic interactions as graph structures
- Future traffic-state prediction

### Workflow

```text
Traffic Images
       │
       ▼
Vehicle Detection (YOLOv8)
       │
       ▼
Traffic State Representation
       │
       ▼
Traffic Signal Optimization (PPO)
       │
       ▼
Traffic Forecasting (GNN)
```



## Notebook 2: PPO Traffic Signal Control

### Description

This notebook focuses on adaptive traffic signal optimization using Reinforcement Learning.

A custom traffic simulation environment is implemented to evaluate the effectiveness of PPO agents in managing traffic flow.

### Methodology

#### Environment Design

- Traffic arrival simulation
- Queue management
- Traffic-light phase control

#### Reinforcement Learning Agent

- PPO (Proximal Policy Optimization)
- Policy learning through environment interaction
- Reward-driven optimization

#### Evaluation

The trained agent is compared against baseline strategies such as:

- Random control
- Fixed-time control
- Static signal policies

### Workflow

```text
Traffic Environment
       │
       ▼
State Observation
       │
       ▼
PPO Agent
       │
       ▼
Signal Action
       │
       ▼
Environment Feedback
       │
       ▼
Policy Improvement
```



## Technologies

The project utilizes the following technologies and frameworks:

- Python
- PyTorch
- YOLOv8
- Stable-Baselines3
- Gymnasium
- PyTorch Geometric
- NumPy
- Pandas
- Matplotlib
- OpenCV



## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/smart-traffic-ai.git
cd smart-traffic-ai
```

Install dependencies:

```bash
pip install -r requirements.txt
```



## Applications

Potential applications include:

- Intelligent Transportation Systems (ITS)
- Smart City Infrastructure
- Traffic Monitoring
- Adaptive Traffic Signal Control
- Urban Mobility Analytics
- AI-driven Transportation Research



## Results

The experiments demonstrate the feasibility of integrating:

- Computer Vision for traffic perception
- Reinforcement Learning for decision-making
- Graph Neural Networks for forecasting

within a unified intelligent transportation framework.



## Educational and Research Value

This repository serves as an exploratory study of modern AI techniques applied to transportation systems.

The implementations are intended for:

- Research prototyping
- Educational purposes
- Reinforcement learning experimentation
- Smart-city AI demonstrations


---

## License

This project is released under the MIT License.
