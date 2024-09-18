# ERIC Documentation

This repository contains the documentation for ERIC/internal and ERIC/open.
It utilizes Jupyterbook to generate HTML from `.md` and `.ipynb` files.

Follow this [Guide](https://jupyterbook.org/en/stable/start/overview.html) on how to set up your python environment.

To build run:
```bash
jupyter-book build --all docs/
```

## Nice to know
With this command you can generate gifs from all png files in folder:
```bash
convert -delay 150 -loop 0 *.png output.gif
```

## Known issues
You might need to copy videos (`.mp4`) to the build directory manually.

