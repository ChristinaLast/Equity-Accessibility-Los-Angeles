# Using measures of Equity to predict Accessibility in Los Angeles County, a comparative study of Multilevel Modelling and Artificial Neural Networks

**Goal:** To compare the results of Multilevel Modelling and Machine Learning regression to analyse the suburbanisation of poverty using Equity and Accessibility data in Los Angeles County.

### Authors
- Christina Last - University of Bristol
- Supervisor: [Levi John Wolf](https://ljwolf.org) - [University of Bristol](http://www.bristol.ac.uk/geography/levi-j-wolf/overview.html)

Following this will require recent installations of:

- Python >= 3.5
- pandas
- geopandas >= 0.3.0
- matplotlib
- rtree
- PySAL
- scikit-learn
- mgwr
- cartopy
- Pystan = 2.18.1 
- geoplot
- [Jupyter Notebook](http://jupyter.org)

If you do not yet have these packages installed, we recommend to use the [conda](http://conda.pydata.org/docs/intro.html) package manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (larger) Anaconda
distribution, found at https://www.anaconda.com/download/). To instal Pystan 2.18.1, ``pip`` will be required. 

Once this is installed, the following command will install all required packages in your Python environment:

```
conda env create -f environment.yml
```

## Downloading the materials

If you have git installed, you can get the tutorial materials by cloning this repo:

    git clone https://github.com/ChristinaLast/Equity-Accessibility-Los-Angeles.git

Otherwise, you can download the repository as a .zip file by heading over
to the GitHub repository (https://github.com/ChristinaLast/Equity-Accessibility-Los-Angeles.git) in
your browser and click the green "Download" button in the upper right:

## Test the environment

To make sure everything was installed correctly, open a terminal, and change its directory (`cd`) so that your working directory is the tutorial materials you downloaded in the step above. Then enter the following:

```sh
python check_environment.py
```

Make sure that this scripts prints "All good."
