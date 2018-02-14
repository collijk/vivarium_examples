# Vivarium Examples

This repository contains several [Jupyter notebooks](http://jupyter.org/) that construct agent based models using the 
[vivarium](https://github.com/ihmeuw/vivarium) framework.  

## Installation Instructions
You'll need Python 3.6+ in order to use vivarium.  I recommend setting up your enviromnent
with [conda](https://conda.io/miniconda.html) as we'll be bringing in some complicated dependencies 
from the scientific python stack. I'll assume that's the tool you're using and that you've followed
the installation guide.  

Next, open up a terminal (cmd.exe, bash, etc.) and navigate to this directory. Then run 

```
conda env create -f vivarium_examples.yml
```

and conda will go and install all the necessary dependencies.  To
activate your new python environment, do 
```
source activate vivarium_examples
```
You can then start playing with the models by typing
```
jupyter notebook
```
which will open up a new window in your browser from which you
can launch any of the available notebooks.

### Contributors
 
 - Zane Rankin
 - [Abie Flaxman](https://github.com/aflaxman) 
 - [Alec Deason](https://github.com/alec-deason)
 - [James Collins](https://github.com/collijk)
 
