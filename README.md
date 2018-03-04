# singularity-docker-fedora26-buildenv-singularity-git-release-2.4
fedora26 build env for singularity/git-release-2.4

example Dockerfile provided for convenience.
```
Running without installation:
singularity run shub://truatpasteurdotfr/singularity-docker-fedora26-buildenv-singularity-git-release-2.4
Building:
singularity build singularity-docker-fedora26-buildenv-singularity-git-release-2.4.simg  Singularity
Download and rename:
singularity pull --name "singularity-docker-fedora26-buildenv-singularity-git-release-2.4" shub://truatpasteurdotfr/singularity-docker-fedora26-buildenv-singularity-git-release-2.4
Running with a separate $HOME 
mkdir -p  ~/singularity.d/home/singularity-docker-fedora26-buildenv-singularity-git-release-2.4
singularity run -B /run -H  ~/singularity.d/home/singularity-docker-fedora26-buildenv-singularity-git-release-2.4 singularity-docker-fedora26-buildenv-singularity-git-release-2.4.simg
```
