# Many Hands Don’t Always Make Light Work: 
## Explaining Social Loafing via Multiprocessing Efficiency (CogSci 2024)

- **Preprint**: X

Humans collaborate to improve productivity and collective outcomes, but people don't always exert maximal effort towards accomplishing collaborative goals. Instead, individuals often expend less effort in group settings, a phenomenon known as social loafing that is traditionally viewed as detrimental to productivity. However, theories from multiprocessing computer systems suggest that this behavior might be a rational response to the diminishing returns from division of labor when scaling group size. Here, we examine how considerations of efficiency, analogous to principles in multiprocessing, affect the perceived acceptability of withholding effort during a collaborative task. We conducted experiments varying workload and group size across scenarios in which all agents except for one are actively contributing to a common goal. We then compare human judgments to a model inspired by computational efficiency in multiprocessing systems. We find that people are systematically influenced by task efficiency in addition to social norms when judging social loafing. 

### This repository contains:
- **Notebooks** to generate stimuli (StimulusCreation.ipynb), modeling (Modeling.ipynb), and analyze + plot experimental data (ExperimentAnalysis.ipynb)
- **Raw data** (CSV) from Prolific experiments
- Full **stimulus set**

### Prerequisites

Before you begin, ensure you have both Conda and pip installed on your system. You can install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) which is a minimal installer for Conda.

### Setup Instructions

**1. Clone the Repository**

Start by cloning this repository to your local machine. Use the following command:

```bash
git clone https://github.com/yourusername/socialloafing.git
cd socialloafing
```

**2. Create conda environment**

```bash
conda create -n socialloafing python=3.9
```

**3. Activate the environment**

```bash
conda activate socialloafing
```

**4. Install requirements**

```bash
pip install -r requirements.txt
```
