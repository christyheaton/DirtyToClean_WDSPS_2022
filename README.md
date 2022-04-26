## From Dirty to Clean: Addressing Environmental Contamination with Python
For [Women in Data Science Puget Sound, 2022](https://www.widspugetsound.org/)

### Data Sources

* [Washington State Environmental Data](https://ecology.wa.gov/)

### Getting Started

* If you are familiar with [GitHub](http://www.github.com), fork (if you wish) and clone [the repository](https://github.com/christyheaton/DirtyToClean_WDSPS_2022). If not, download the repository and unzip to a working directory. Take note of where you put it!

* Install [Miniconda](https://conda.io/miniconda.html) for your operating system. Please choose the latest Python 3.x version.

* You should now have access to an Anaconda command prompt, open it like you would any program. Note that you should see `(base)` somewhere in your prompt. This means you're in the base Conda environment, which we will now change. 

Navigate to the directory containing environment.yml (included in the repo).

```bash
cd [location where you saved the repo]/DirtyToClean_WDSPS_2022
```

* Create the Conda environment you will need to run the tutorial. Note: it is called `geopandasenv`. **This could take anywhere from 10-30 minutes to finish.**

```bash
conda env create environment.yml
```

* Now you can activate the environment.

```bash
source activate geopandasenv  # macOS and Linux
activate geopandasenv  # Windows.
```

* To open the Jupyter Notebooks included in this tutorial, in your Anaconda prompt navigated to the Notebook directory, type in:

```bash
jupyter notebook
```

This will open a browser where you can click and open each Notebook.

* If you ever want to deactivate the geopandasenv environment, type the following in your Anaconda prompt:

```bash
source deactivate  # macOS and Linux
deactivate  # Windows.
```