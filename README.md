# xeus-cling-experimentations

Experimenting with Xeux and Cling

## Installation and activation notes

A few words about how to install:

- Start by installing conda:

https://docs.anaconda.com/anaconda/install/linux/

- There are some installation instruction for xeus-cling there:

https://github.com/jupyter-xeus/xeus-cling

Note that I needed to install the jupyter notebook also in the anaconda environment after install xeus cling:

```
(cling) ~$ conda install notebook -c conda-forge
```

- Once this is done, use is easy:

```
~$ source ~/anaconda3/bin/activate 
(base) ~$ conda activate cling
(cling) ~$ 
```

## A few needed installs

A few of the installs I needed to get things to work:

```
sudo apt-get install gcc-multilib
conda install -c conda-forge matplotlib 
```

To find path to matplotlibrc:

```
import matplotlib
print(matplotlib.matplotlib_fname())
```

