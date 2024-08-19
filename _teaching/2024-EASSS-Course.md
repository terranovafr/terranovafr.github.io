---
title: "Tutorial: Deep Reinforcement Learning - Foundations and Practical Environment Setup for Real-World Applications"
collection: teaching
type: "European Agent Systems Summer School (EASSS) 2024"
permalink: /teaching/2024-EASSS-Course
venue: "School of Computer Science at University College Dublin"
date: 2024-08-20
location: "Dublin, Ireland"
---

# Agenda

This tutorial hosted at [EASSS 2024](https://euramas.github.io/easss2024/), will be composed of a theoretical lesson on Reinforcement Learning (RL), followed by a laboratory mainly focusing on RL environments setup.

## Theoretical Session (10:00 - 11:30)

### Description
The tutorial will begin by covering fundamental RL concepts such as agents, environments, and learning paradigms. We will then discuss why deep learning is increasingly employed to solve complex, high-dimensional decision-making challenges.

📑 **[Theoretical Session Slides](../files/EASSS_2024_Theory.pdf)**

## Practical Session (12:00 - 13:30)

### Description
The hands-on component will guide participants through setting up a training environment tailored for RL agents. This part of the tutorial will include a practical introduction to OpenAI’s Gym library and references to prominent libraries that implement deep RL algorithms.

🛠️ **[Practical Session Slides](../files/EASSS_2024_Practical.pdf)**

📦 **[Tutorial Code](../files/easss-RL-tutorial-main.zip)**

### Environment Setup
To create a conda environment and install the necessary libraries, use the following commands:

```bash
conda env create --name rleasss
conda activate rleasss
pip install stable-baselines3 tensorboard
```

Or use the requirements.txt file:

```bash
conda env create --name rleasss
conda activate rleasss
pip install -r requirements.txt
```

Or use the attached environment.yml file:

```bash
conda env create -f environment.yml
conda activate rleasss
```

If you use venv, do the same steps and use the requirements.txt file or the manual installation:
```bash
python -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt
```

However, with MacOS some issues may arise based on the numpy version. In that case downgrade numpy to a version lower than 2.0:
```bash
pip install "numpy<2"
```

I look forward to a productive and insightful tutorial. Please ensure you have the necessary environment set up before the practical session begins.

