
This repository collects the dataset, code and Latex documents used to compile my PhD thesis.

# Prerequisites

## Git lfs
This repository uses [git lfs](https://git-lfs.com) to manage big files. Please follow the installation procedure before cloning the repository. Remember to run `git lfs install`.

# How to clone the repository

## Git clone command
The repository integrates submodules for each chapter, which I used to separate code development and data. This command will recursively clone the repository and all the submodules:
```bash
git clone --recurse-submodules https://github.com/andy941/PhD_Thesis.git
```

## If the submodules are not cloned
To check for updates or clone the submodules at a later stage, from the repository folder:
```bash
git submodule update --init --recursive
```
