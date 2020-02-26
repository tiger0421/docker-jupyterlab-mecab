# docker-jupyterlab-mecab
This image enables you to run MeCab and tensorflow on Jupyter Lab

## Usage
```
docker run --rm -p 8888:8888 -it tiger0421/jupyterlab-mecab-tensorflow
```

When you use GPU. (NOTE: Specify a tag suited to your CUDA version.)
```
docker run --rm --gpus all -p 8888:8888 -it tiger0421/jupyterlab-mecab-tensorflow:tensorflow_gpu_cuda8
docker run --rm --gpus all -p 8888:8888 -it tiger0421/jupyterlab-mecab-tensorflow:tensorflow_gpu_cuda9
docker run --rm --gpus all -p 8888:8888 -it tiger0421/jupyterlab-mecab-tensorflow:tensorflow_gpu_cuda10
```

See details about option
https://jupyter-docker-stacks.readthedocs.io/en/latest/using/common.html

## Base image
(tag : latest)
https://hub.docker.com/r/jupyter/tensorflow-notebook

(others)
https://hub.docker.com/r/tensorflow/tensorflow

## TensorFlow and CUDA version combinations
https://www.tensorflow.org/install/source#linux
