# Mito Demo

[![Launch Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/saga-vcs/mito-demo.git/master?urlpath=lab/tree/example/example.ipynb)

When this repo is deployed on MyBinder.org, this lets a user experiment with Mito version 0.1.15.

## How to use

Launch a Binder instance by clicking the Binder badge above.

If you launch a Binder instance through some other process, you may default to the older Jupyter Notebook interface, in which case replace `tree` at the end of your URL with `lab`.

Thats it!

## Create a Binder link that points to JupyterLab

You can also create a Binder link that points to JupyterLab by adding the following
to the end of your link:

`?urlpath=lab`

You can point to a specific file using JupterLab by including a file path
beginning with `tree/` to the end of `urlpath`, like so:

`?urlpath=lab/tree/path/to/my/notebook.ipynb`

For example, the Binder badge above goes to the following URL:

`http://mybinder.org/v2/gh/binder-examples/jupyterlab/master?urlpath=lab/tree/index.ipynb`

Note: this repository also installs several JupyterLab extensions via a `postBuild` script, allowing
you to use JupyterLab's extensions and widgets functionality.

For a more complete demo of JupyterLab using Binder, see the
[JupyterLab Demo](https://github.com/jupyterlab/jupyterlab-demo). 
 
