# Master-Thesis-Experiment
The purpose of this research project is to evaluate the usefulness, usability, and analytical value of a visualization tool designed to support a process analyst during exploratory process analysis.

## Overview

1. **Install Prerequisites**   
   Install LogView and the required packages (explanation below).
3. **Tutorial (at home)**  
   The first part of the study is a tutorial [`Tutorial.ipynb`](./Tutorial.ipynb), which introduces the tools used in the experiment. This ensures you are familiar with the tools before taking part in the actual experiment.

4. **Experiment (in the presence of the researcher)**  
   The second part is the experiment [`Experiment.ipynb`](./Experiment.ipynb). This will take place once the tutorial is complete, either in person or online, under the supervision of the researcher.

## Prerequisites

Ensure you have **Python 3.9 – 3.12** installed. You can use any environment manager (e.g., `conda`, `venv`). Here's an example using **conda**:

```bash
conda create -n logview_env python=3.10
conda activate logview_env
```

To run the tutorial and experiment notebooks, install the following packages:

```bash
pip install ipykernel pandas pm4py os zipfile
```


### Installing **LogView**

#### 1. Clone the LogView Repository

```bash
git clone https://github.com/fzerbato/logview.git
cd logview
```

#### 2. Install LogView Locally

```bash
python setup.py sdist bdist_wheel
pip install .
```

### Download this repository
Download or clone this repository to your local machine:
```bash
git clone https://github.com/lauradidden/Master-Thesis-Experiment.git
cd Master-Thesis-Experiment
```

## Support
For any questions or installation issues, please contact Laura Didden (l.l.c.didden@student.tue.nl).
