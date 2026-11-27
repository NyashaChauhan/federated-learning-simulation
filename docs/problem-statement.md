# Problem Statement and Project Scope

## 1. Problem Statement

Traditional machine learning requires collecting training data at a centralized location. However, in many real-world applications, sharing sensitive data between multiple organizations or devices may raise privacy and security concerns.

Federated Learning provides an alternative approach in which multiple clients collaboratively train a shared machine learning model without directly sharing their local training data.

This project aims to simulate a Federated Learning environment using the MNIST handwritten digit dataset and demonstrate how multiple clients can collaboratively train a global model using the Federated Averaging (FedAvg) algorithm.

## 2. Objectives

- Understand the working of Federated Learning.
- Implement the Federated Averaging (FedAvg) algorithm.
- Simulate multiple clients training a shared model locally.
- Compare IID and non-IID data distributions.
- Compare federated learning performance with centralized training.
- Visualize model accuracy across training rounds.

## 3. Proposed Solution

The system will simulate five clients, each holding a portion of the MNIST dataset.

Each client independently trains a local model using its own data. The updated model weights are then sent to a central server, where they are aggregated using the FedAvg algorithm.

The process is repeated over multiple communication rounds to improve the global model.

The simulation will evaluate performance under IID and non-IID data distributions and compare the results with a centralized training baseline.

## 4. Scope of the Project

### In Scope

- MNIST dataset loading and preprocessing.
- Simulation of multiple federated clients.
- IID and non-IID data partitioning.
- Implementation of a small neural network.
- Centralized model training.
- Federated Averaging implementation.
- Performance evaluation and visualization.
- Basic interactive interface for running simulations.

### Out of Scope

- Deployment across real physical devices.
- Real-world hospital or organizational data integration.
- Production-level security and encryption.
- Large-scale distributed training.
- Implementation of multiple advanced federated learning algorithms.

## 5. Expected Outcome

The project is expected to demonstrate how Federated Learning enables collaborative model training without sharing raw training data.

It will also highlight how different data distributions across clients can affect model performance and convergence.
