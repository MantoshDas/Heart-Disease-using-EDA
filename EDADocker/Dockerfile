FROM jupyter/base-notebook

WORKDIR /home/jovyan/work

COPY EDA_HeartDisease.ipynb .
COPY requirements.txt .

RUN pip install -r requirements.txt

