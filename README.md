# exploring-data-science

Resources and experiments to explore data science concepts, technologies and tools.

## Using jupyter-notebooks

Start jupyter-notebooks docker image using the following command in git checkout root directory:

```bash
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work jupyter/datascience-notebook
```