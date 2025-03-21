# 👋 Welcome to Once Upon AI

Welcome to the **Once Upon AI** course! In this course you'll learn everything you need to know about AI (Artificial Intelligence), ML (Machine Learning) and DL (Deep Learning). This course is for anyone interested in learning about how AI works and wants to build skills in AI. We'll start at the beginning, building up slowly, learning the different building blocks, all while keeping jargon to a minimum, mostly using simple to understand stories to break down the concepts. 

Interested??? Let's get started.

## Course Overview

This course teaches foundational concepts in:
- Artificial Intelligence (AI)
- Machine Learning (ML) 
- Deep Learning (DL)

Using simple stories and minimal jargon, we break down complex concepts into easy-to-understand building blocks. Interested??? Let's get started!

## Getting Started

### Using GitHub Codespaces (Recommended)
The easiest way to follow along is using GitHub Codespaces, which provides a pre-configured development environment.

#### Running in CodeSpaces

Getting started with this course using GitHub Codespaces is simple and requires no local setup:

1. Click the green "Code" button at the top of this repository.
2. Select the "Codespaces" tab.
3. Click "Create codespace on main".

This will launch a cloud-based development environment with everything pre-configured:
- All required dependencies are set up
- Jupyter Notebooks are ready to run
If you don't know what any of this means, don't worry, it just means the tools you need are already installed and you don't need to do anything.

Once your Codespace loads:
1. Click on any `.ipynb` notebook file to open it
2. You'll see a notification to select a kernel - choose "Python 3"
3. Now you can run the notebook cells by clicking the ▶️ play button next to each cell or using `Shift+Enter`

The environment includes:
- PyTorch and related libraries
- NumPy, Matplotlib, and other data science tools
- Git for version control
- VS Code's Python and Jupyter extensions

> **Note**: Codespaces provides 60 hours of free usage per month for personal accounts. When you're done, you can stop your Codespace by clicking the menu in the bottom left corner and selecting "Stop Current Codespace".

### Local Setup (Running everything on your computer)
To run the course materials on your local machine:

1. **Install Conda**
   - Download [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
   - Follow the installation instructions for your operating system

2. **Activate Conda Environment**
    ```bash
    conda create --name onceUponAI python=3.9
    conda activate onceUponAI
    ```

3. **Install PyTorch**
   ```bash
   pip install --upgrade pip
   pip install torch torchvision torchaudio
   ```

3. **Install Additional Dependencies**
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

## Course Content

The course is organized into the following Jupyter notebooks:

1. **[Introduction.ipynb](Basics/Introduction.ipynb)**  
    - Overview of the course
    - Tools Check - To make sure everything is working before we begin.

2. **[Lesson1.ipynb](Basics/Lesson1.ipynb)**  
    - "Perceptron": The most basic unit of a neural network.
    - Build up your first Perceptron.

3. **[Lesson2.ipynb](Basics/Lesson2.ipynb)**  
    - TODO


Each notebook builds on the previous one, so it's recommended to follow them in order. Happy learning!
