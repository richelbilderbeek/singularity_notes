# singularity_notes

 * [RIS course material](https://redmine.hpc.rug.nl/redmine/projects/peregrine/wiki/Course_material)

My notes on Singularity

## Install Singularity

 * Download from [http://singularity.lbl.gov/install-linux](http://singularity.lbl.gov/install-linux)
   `wget https://github.com/singularityware/singularity/releases/download/2.2.1/singularity-2.2.1.tar.gz`
 * Untar
 * `./configure`
 * `make`
 * `sudo make install`


```
sudo singularity create richel.img
```

```
sudo singularity import richel.img docker://python:3.5.2
```

```
sudo singularity expand richel.img --size 500Mb
```

Note that it expands 512 Mb
