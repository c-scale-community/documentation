# C-SCALE Documentation

Repository to host the documentation and training for C-SCALE.

# Build the docs locally

## First time setup

Below are the steps to configure the working environment for the first time:
```bash
# download and install miniconda
cd </path/to/working/dir>
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh -b -p c-scale-docs

# create and activate conda environment
conda env create -f </path/to/>environment.yml
conda activate c-scale-docs
```

## Activate environment

After you have configured the conda environment following the steps above,
you only need to activate it with the following:

```bash
source </path/to/c-scale-docs>/etc/profile.d/conda.sh
conda activate c-scale-docs
```
