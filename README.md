# C-SCALE Documentation

Repository to host the documentation and training for C-SCALE.

# Build the docs locally

## One off setup

Use [conda](https://conda.io/) to configure the working environment with
[MkDocs](https://www.mkdocs.org/):

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

To view the documentation just run:

```bash
mkdocs serve
```

This command builds your Markdown files into HTML and starts a development server
to browse your documentation. Open up http://127.0.0.1:8000/ in your web browser
to see your documentation. You can make changes to your Markdown files and your
docs will automatically rebuild.
