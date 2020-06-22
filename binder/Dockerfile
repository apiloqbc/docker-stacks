  
# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.
FROM jupyter/base-notebook:latest
ENV TAG="latest"
RUN jupyter labextension install @jupyter-voila/jupyterlab-preview

COPY binder/README.ipynb .
