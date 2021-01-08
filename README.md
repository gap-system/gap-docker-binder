# Example repository for using GAP on Binder

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/gap-system/gap-docker/master)

This repository should show you how to use deploy [GAP](https://wwww.gap-system.org) Jupyter notebooks to Binder.
If you simply want to try out GAP on mybinder.org, you can click the launch badge above.

## Using existing jupyter notebooks

GAP provides several Binder-ready Docker images, for example:
- for the latest GAP release [gap-system/gap-docker](https://hub.docker.com/r/gapsystem/gap-docker/)
- for the GAP development version [gap-system/gap-docker-master](https://hub.docker.com/r/gapsystem/gap-docker-master/)

Is is based on the current master branch of GAP.
To use for example the 4.11 image to deploy your notebook to Binder, use the following steps:

1. Create a new `git`-Repository on [GitHub](https://github.com).
2. Copy the [Dockerfile](https://github.com/gap-system/gap-docker-stable-4.11/blob/master/Dockerfile) from the [gapsystem/gap-docker-stable-4.11](https://hub.docker.com/r/gapsystem/gap-docker-stable-4.11/) repository into your newly created `git` repository.
3. Copy your Jupyter notebooks into the repository.
4. Upload the repository to GitHub.
5. Copy the link to the repository and launch it on [MyBinder](https://mybinder.org) or any Binder instance of your choice.
