# C-SCALE Documentation

Repository to host the documentation and training for C-SCALE.

# Build the docs locally

## Conda

Conda is a package manager. See https://docs.conda.io/ for more information.

### First time setup

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

### Activate environment

After you have configured the conda environment following the steps above,
you only need to activate it with the following:

```bash
source </path/to/c-scale-docs>/etc/profile.d/conda.sh
conda activate c-scale-docs
```

## MkDocs

MkDocs is a documentation generator that focuses on speed and simplicity.
For getting started visit:

https://docs.readthedocs.io/en/stable/intro/getting-started-with-mkdocs.html

### First time setup

```bash
# go to this repository
cd </path/to/>documentation

# initialize MkDocs
mkdocs new .
```

The `mkdocs new` command generates two files:
* `mkdocs.yml`: the MkDocs configuration
* `docs/index.md`: the Markdown file that is the entry point for your documentation.

### View the documentation locally

Just run:

```bash
mkdocs serve
```

This command builds your Markdown files into HTML and starts a development server
to browse your documentation. Open up http://127.0.0.1:8000/ in your web browser
to see your documentation. You can make changes to your Markdown files and your
docs will automatically rebuild.
