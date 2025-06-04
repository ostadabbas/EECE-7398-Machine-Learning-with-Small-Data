# EECE 7398: Machine Learning with Small Data - Fall 2025

## Leveraging the Discovery Cluster for Advanced ML Research

### Instructor: Prof. Sarah Ostadabbas
#### Northeastern University, Department of Electrical and Computer Engineering

---

## Overview

This repository contains the materials for the **EECE 7398: Machine Learning with Small Data** course. The course emphasizes using Northeastern's Discovery Cluster for advanced machine learning experiments, particularly in small data scenarios.

The materials include pre-prepared slides (uploaded directly as `.pdf`) and hands-on exercises to guide students through accessing, setting up, and utilizing the Discovery Cluster for machine learning research. Topics covered:

- Introduction to the Discovery Cluster
- Cluster access and environment configuration
- PyTorch setup and GPU utilization
- Monitoring experiments with Weights & Biases
- Best practices for managing machine learning experiments

---

## Contents

- `Slides/`: Uploaded PDF slides covering session topics
- `Exercises/`: Interactive notebooks and scripts for hands-on learning
  - **Environment Setup**:
    - `interactive_local_setup.ipynb`: Platform-aware setup guide for local development
    - `conda_environment_setup_part1.ipynb`: Setup guide for Discovery Cluster
  - **PyTorch and GPU Training**:
    - `interactive_pytorch_gpu.ipynb`: Interactive GPU training tutorial
    - `pytorch_gpu_training_part2.ipynb`: Advanced GPU training on Discovery
  - **CIFAR-10 Tutorials**:
    - `interactive_cifar10.ipynb`: Comprehensive interactive CIFAR-10 tutorial
    - `cifar10_classification_assignment.ipynb`: Original CIFAR-10 assignment
    - `cifar10_training_inference.py`: Training script
  - **W&B Integration**:
    - `interactive_wandb_tutorial.ipynb`: Interactive W&B tutorial
    - `wandb_monitoring_part3.ipynb`: W&B setup on Discovery
    - `wandb_monitoring_script.py`: W&B monitoring script
- `README.md`: This readme file

---

## Prerequisites

Before using the Discovery Cluster for this course, students must have:

1. **Access to the Discovery Cluster**: [Request access through ServiceNow](https://rc.northeastern.edu/getting-started/)
2. Basic knowledge of **Python** and **machine learning**
3. Familiarity with **Conda** for environment management

---

## Interactive Notebooks Overview

The repository now includes a set of interactive Jupyter notebooks designed for both local development and cluster usage:

1. **Local Environment Setup** (`interactive_local_setup.ipynb`)
   - Automatic OS detection (Windows, MacOS, Linux)
   - Platform-specific installation instructions
   - Interactive environment verification
   - GPU detection and setup

2. **PyTorch GPU Tutorial** (`interactive_pytorch_gpu.ipynb`)
   - GPU operations and memory management
   - Performance benchmarking
   - Multi-GPU training
   - Best practices for GPU utilization

3. **Interactive CIFAR-10** (`interactive_cifar10.ipynb`)
   - End-to-end training pipeline
   - Real-time visualization
   - Model architecture exploration
   - Performance monitoring with W&B

4. **W&B Integration** (`interactive_wandb_tutorial.ipynb`)
   - Experiment tracking setup
   - Custom metrics and logging
   - Hyperparameter optimization
   - Interactive visualizations

These notebooks feature:
- Real-time feedback and progress monitoring
- Interactive visualizations
- Platform-specific optimizations
- Comprehensive error handling
- Integration with W&B for experiment tracking

---

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/EECE7398-ML-Small-Data-Fall2024.git
    ```

2. Choose your development environment:   
   - For local development: Start with `interactive_local_setup.ipynb`
   - For Discovery Cluster: Follow `conda_environment_setup_part1.ipynb`

3. Follow the interactive tutorials:
   - Complete the environment setup
   - Work through the PyTorch GPU tutorial
   - Experiment with CIFAR-10 classification
   - Set up experiment tracking with W&B

---

## Additional Resources

- [RC Discovery Cluster Documentation](https://rc.northeastern.edu)
- [Conda Documentation](https://docs.conda.io/projects/conda/en/latest/)
- [PyTorch Documentation](https://pytorch.org/docs/stable/)
- [Weights and Biases Documentation](https://docs.wandb.ai/)

For any issues or questions, feel free to reach out to the Northeastern RC support team via [ServiceNow](https://rc.northeastern.edu/help/support/).

---

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
