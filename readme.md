# Time series final work

## How to run notebooks

First of all, you must have conda installed. Follow instructions here:

https://docs.anaconda.com/anaconda/install/index.html

Once you have anaconda installed, please execute the following command to create an ad-hoc environment to work:

`conda env create -f environment.yml --prefix ./time-series-final-work-env`

After doing this, in order to be able to access this environment from within a Jupyter Lab Session execute the following command:

`python -m ipykernel install --user --name time-series-final-work-env --display-name="time-series-final-work-ker"`

Finally, execute 

`jupyter lab`

and select the notebook of interest.