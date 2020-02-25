# docker-jupyterlab-mecab
This image enables you to run MeCab and tensorflow on Jupyter Lab

## Usage
```
docker run --rm -p 8888:8888 -it tiger0421/jupyterlab-mecab-tensorflow
```
If you want change user name (ex: ubuntu)
```
docker run --rm -p 8888:8888 -e NB_USER=ubuntu -it tiger0421/jupyterlab-mecab-tensorflow
```

See details about option
https://jupyter-docker-stacks.readthedocs.io/en/latest/using/common.html

## Base image
https://hub.docker.com/r/jupyter/tensorflow-notebook
