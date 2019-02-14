# sequence_tagging-ner
LSTM + CRF in Tensorflow

Before Starting You need:
1. glove.6B.300d embedding vector
2. IOB label samples

Than:
1. Build vocab from the data and extract trimmed glove vectors.
```
python build_data.py
```

2. Train the model with
```
python train.py
```

3. Evaluate and interact with the model with
```
python evaluate.py
```
