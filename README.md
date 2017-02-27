# operative-ml-training
    docker run -it -p 8888:8888 -v $(pwd)/docker-volume:/home/jovyan/work jupyter/all-spark-notebook

* Browse to localhost:8888
* from notebook home open a new terminal tab (new -> terminal)
* run in terminal 
 * `conda install -y -n python2 flask`
 * `conda install -c r r-essentials` (this takes some 5-10 mins!)
 * `conda install -c bioconda r-corrplot=0.77` 
 * `conda install -c bioconda r-tsne=0.1_3`
