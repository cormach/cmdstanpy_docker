https://blog.ouseful.info/2019/02/05/on-not-faffing-around-with-jupyter-docker-container-auth-tokens/

-e JUPYTER_TOKEN="jupyter_notebook_token"

docker build --tag cmdstan .

docker run -e JUPYTER_TOKEN="jupyter_notebook_token" -dp 8888:8888 cmdstan

to open Jupyter Notebook go to:  http://localhost:8888/tree?token=jupyter_notebook_token
