# Kedro POC

## Environment Setup

Create a conda virtual environment and install kedro/airflow.

```
conda create -n kedro
conda activate kedro

pip install kedro
pip install kedro-airflow
pip install kedro-viz

pip install tzlocal==1.5.1 --force-reinstall
pip install ipython
pip install airflow
```


## Using Kedro for Data Pipeline

### Config Kedro project

Create Kedro project called "Kedro POC" by typing below command. 

```
kedro new

cd kedro-poc
kedro install
```

### Config Data Catalog



### Create Data Pipeline


### Package and Deploy to Airflow


## Using Airflow for Data Pipeline

