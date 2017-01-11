FROM jupyter/datascience-notebook

RUN conda update scikit-learn -y
RUN conda install dipy caffe tqdm nilearn -y
RUN pip install tensorflow==0.12.1
RUN pip install mne
RUN conda install --name python2 caffe
