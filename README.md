# AGWN: Attention-based Graph WaveNet for Multi-scale
Lane-level Traffic Prediction

This is the original pytorch implementation of Atention-based Graph WaveNet（AGWN）:


## Requirements
- python 3.6
- matplotlib
- numpy
- scipy
- pandas
- torch
- argparse


## Data Preparation

### Step1: We provide the processed PeMS data and source data in the Data_process folder, you can also generate a new training file in the following way：

```python
python generate_training_data.py
```

## Train Commands

```
python train.py
```

