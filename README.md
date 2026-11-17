# Consumer cancellation prediction

Using historical hotel reservations, the notebook prepares the is_canceled target, scales inputs with MinMaxScaler and trains a dense Keras classifier. It evaluates predictions and saves the model and scaler. Run its cells in order.

## Run locally

```sh
python -m pip install jupyter tensorflow scikit-learn pandas numpy matplotlib seaborn joblib watermark
jupyter notebook Projeto1.ipynb
```
