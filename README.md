<h3>How to create the container</h3>
docker build --tag cmdstan .

docker run -e JUPYTER_TOKEN="jupyter_notebook_token" -dp 8888:8888 cmdstan

<h3>Open the Jupyter notebook</h3>
to open Jupyter Notebook go to:  http://localhost:8888/tree?token=jupyter_notebook_token

<h3>More on CmdStanPy</h3>
https://arviz-devs.github.io/arviz/notebooks/InferenceDataCookbook.html#From-CmdStanPy

<h4>More on Jupyter notebooks in Docker</h4>
https://blog.ouseful.info/2019/02/05/on-not-faffing-around-with-jupyter-docker-container-auth-tokens/

the key piece is the environment insturction in the docker run -e JUPYTER_TOKEN="jupyter_notebook_token"
