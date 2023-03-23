# Metaflux
## Introduction
Meta-learning framework for climate sciences. Currently supports the following features:
- Takes as input timeseries data (eg. FLUXNET eddy covariance stations)
- Customizable hyperparameters (create your own and place them under the `configs` directory)
- Sample training script with sample data that can be adapted to your own use case
- (TBD) Training script to generate Metaflux once the paper is available

## Quickstart
1. Clone this repository into your private workspace:
```
git clone https://github.com/juannat7/metaflux.git
```

2. Install dependencies using `pip` or `conda`
```
pip install -r requirements.txt
```

![Meta inference](https://github.com/juannat7/metaflux/blob/main/docs/gpp_infer.jpeg)

![Meta inference with context encoder](https://github.com/juannat7/metaflux/blob/main/docs/gpp_encoder_infer.jpeg)

## Sample Notebooks
1. `01a_non_temporal_pipeline`: for non-temporal dataset and model (eg. MLP)
2. `01b_temporal_pipeline`: for temporal dataset and model (eg. LSTM, BiLSTM)
3. `01c_with_encoder_pipeline`: adding context encoder to current classic metalearning model