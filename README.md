# Triformer: Linear Triangular Transformer for Long Sequence Multivariate TimeSeries Forecasting
![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg?style=plastic)
![PyTorch 1.2](https://img.shields.io/badge/PyTorch%20-%23EE4C2C.svg?style=plastic)
![cuDNN 7.3.1](https://img.shields.io/badge/cudnn-7.3.1-green.svg?style=plastic)
![License CC BY-NC-SA](https://img.shields.io/badge/license-CC_BY--NC--SA--green.svg?style=plastic)

This is the origin Pytorch implementation of Triangular Transfomer.


## Requirements

- Python 3.6
- matplotlib == 3.1.1
- numpy == 1.19.4
- pandas == 0.25.1
- scikit_learn == 0.21.3
- torch == 1.8.0

Dependencies can be installed using the following command:
```bash
pip install -r requirements.txt
```

## Data and Usage
We used the exact same setup as [Informer](https://github.com/zhouhaoyi/Informer2020). The data processing and usage 
instructions can be found [here](https://github.com/zhouhaoyi/Informer2020).

## Citation

If you find this repository useful in your research, please cite the following paper:

```
@inproceedings{RazvanIJCAI2022,
  author    = {Razvan-Gabriel Cirstea and
                Chenjuan Guo and
                Bin Yang and
                Tung Kieu and
                Xuanyi Dong and
                Shirui Pan},
  title     = {Triformer: Triangular, Variable-Specific Attentions for Long Sequence
                Multivariate Time Series Forecasting},
  booktitle = {IJCAI},
  year      = {2022}
}
``` 