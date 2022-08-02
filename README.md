## To run the tutorial material on servers elsewhere

## 1. Clone the repository locally

In your terminal, use `git` to clone the repository locally.

```bash
git clone git@github.com:hbata/bayesian_stats.git 
```
## 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3,
go get it
(note: you can also set up your project environment w/out Anaconda using `pip` to install the required packages;
however Anaconda is great for Data Science and we encourage you to use it).

## 3. Set up your environment

### 3a. `conda` users

If this is the first time you're setting up your compute environment,
use the `conda` package manager
to **install all the necessary packages**
from the provided `environment.yml` file.
Run this command:

```bash
conda env update -f environment.yml
```

Then activate the environment using:

```bash
conda activate bldr_sess 
```
