# epidemiology_toolkit

A suite of tools and demonstartive cases for epidemiologic analyses.

To run demo notebooks in a preinstalled environment, please build the Docker image and run

```
docker run --rm -p 127.0.0.1:8787:8787 -v $PWD:/home/rstudio/local_files -e USERID=$UID -e PASSWORD=[SOME PASWORD] epidemi
```