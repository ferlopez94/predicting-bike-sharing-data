# Predicting bike sharing data

In this [notebook](Notebook.ipynb), we'll build a neural network from scratch and use it to predict daily bike rental ridership from a dataset that contains the hourly count of rental bikes from January 1, 2011, to December 31, 2012, belonging to Capital Bikeshare system with the corresponding weather and seasonal information.

You can also read this notebook in [Español](Notebook_es.ipynb).


## Getting started with Conda
If you have Conda installed on your local machine, download the entire folder of the project to your computer and then open your terminal and navigate to its location.

Then run
```
conda env create -f environment.yaml
```

This will create a new environment with the same name listed in `environment.yaml`.

Once you have the environment created, use `source activate predicting-bike-sharing-data` to enter it on OSX/Linux. On Windows, use `activate predicting-bike-sharing-data`.

Now run
```
jupyter notebook
```

Finally, open your browser and visit localhost:8888 (or the port indicated in your terminal), and you should see all of the contents of the project. You can now open the notebook.


## Getting started without Conda
If you don't have Conda, a `requirements.txt` file is provided to install all of the necessary packages using `pip`.


## License
This project is licensed under MIT License - see [LICENSE](https://github.com/ferlopez94/predicting-bike-sharing-data/blob/master/LICENSE) for more details.
