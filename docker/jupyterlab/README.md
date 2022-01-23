https://docs.jupyter.org/en/latest/projects/deployment.html?highlight=docker
https://github.com/jupyter/docker-stacks
https://jupyter-docker-stacks.readthedocs.io/en/latest/
https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html


<!-- docker run --rm -it -p 8000:8888 jupyter/datascience-notebook bash -->

docker run --rm -it -p 8000:8888 jupyter/datascience-notebook /bin/bash -c "jupyter lab --ip=0.0.0.0 --allow-root"
