# HOW TO INSTALL

[For 32 bit](https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86.exe) 

[For 64 bit](https://docs.anaconda.com/miniconda/)


# conda commands

### 1-how to create conda env
```
conda create --name myenv python=3.9

conda activate myenv

```

### 2-how to delete conda env

```
conda env remove --name myenv
```
### 3-how to change env name

```
conda activate myenv
conda config --set env:myenv.name newenvname

```

### 4-how to install libraries

```
conda install numpy pandas matplotlib

```

### 5- how to install ipykernel and notebook

```
conda install ipykernel
conda install notebook

```

### 6-Command line help

```
conda command-name --help
```

### 7-Use conda to search for a package

```
conda search package-name

```
