# Example repository for using GAP on Binder

This repository should show you how to use deploy [GAP](https://wwww.gap-system.org) Jupyter notebooks to Binder.

## Using GAP on Binder

GAP provides a Binder-ready Docker image: [gapsystem/gap-docker-master](https://hub.docker.com/r/gapsystem/gap-docker-master/). 
Is is based on the current master branch of GAP.
To use this image to deploy your repository to Binder, use the following steps:

1. Create a new `git`-Repository on [GitHub](https://github.com).
2. Copy the [Dockerfile](TODO) from this repository into the folder you have cloned or created the `git` repository in.
3. Copy your Jupyter notebooks into the repository.
4. Upload the repository to GitHub.
5. Copy the link to the repository and launch it on [MyBinder](https://mybinder.org) or any Binder instance of your choice.