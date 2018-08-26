# haskell-notebook: Jupyter's Datascience Notebook with Haskell support

Thanks to the [IHaskell project](https://github.com/gibiansky/IHaskell), Jupyter can be extended with a Haskell backend.

## Running

```
docker run -p 8888:8888 -v work:/home/jovyan/work muerku/haskell-notebook
```

You can start Jupyter Lab by providing `-e JUPYTER_ENABLE_LAB=1` - jupyter's start script `start-notebook.sh` will start `lab` instead of `notebook` when that environment variable is set. By default, Jupyter starts a notebook.

**NOTE:** While the notebook worked for me, the lab didn't!

