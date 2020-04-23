# Time Series Forecasting

* [`sarima-model.ipynb`](sarima-model.ipynb) – demo of SARIMA model forecasting air passengers number, time series having annual seasonality.

![](img/sarima-02.png)

* [`prophet-model.ipynb`](prophet-model.ipynb) – demo of [facebook prophet](https://facebook.github.io/prophet/) model forecasting 1961 year and later.

![](img/prophet-00.png)

**Run Notebook**

```bash
docker run -d \
    -p 127.0.0.1:8884:8888 \
    -v "$PWD":/home/jovyan/work \
    --name time-series-forecasting \
    jupyter/datascience-notebook:latest

docker logs time-series-forecasting

# open http://127.0.0.1:8884/?token=**********
```
