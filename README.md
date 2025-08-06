# Infodemic Source Detection with Infomation Flow: Foundations and Scalabale Computation

## Background

We extend the rumor source detection problem beyond graphs and and give an alternative formulation that incorporate the rate constraints.

We illustrate our method with an example butterfly network and synthetic directed graphs, and show the scalability of our lazy-greedy forward search algorithm in [directed.ipynb](https://github.com/ZimengInfo/InfodemicSource/blob/main/directed.ipynb).

## Installation

We recommend using **Python 3.10+**.

### Clone the repository

```
git clone https://github.com/ZimengInfo/InfodemicSource.git
cd InfodemicSource
```

### Create virtual environment (Conda is recommended)
```
conda env create -f environment.yml
conda activate infodemic
```
Alternatively, create it manually:
```
conda create -n infodemic python=3.10
conda activate infodemic
pip install -r requirements.txt
```

### 

## Citation

If you find this code and the paper helpful, please considering cite our work:
