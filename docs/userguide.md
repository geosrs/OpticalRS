# Getting Started

There are two ways of using `OpticalRS`. You can use the [OpticalRS QGIS Processing Scripts](#processing-scripts) or you can invoke the code directly using the [Python Library](#python-library). Presently, the processing tools represent a small fraction of the `OpticalRS` functionality. Please see the appropriate page for more detail.

## Python Library

At its current stage of development, `OpticalRS` is most suited for use as a [Python] library. An autogenerated [list of modules](modules.md) with brief descriptions has been provided as an overview of `OpticalRS`. For more information, please see the docstrings in the code.

Usage examples will be provided in the form of Jupyter (formerly IPython) notebooks. These can be viewed in static form [on GitHub](https://github.com/jkibele/OpticalRS/tree/master/docs/notebooks) or downloaded and run interactively. However, some notebooks may require datasets that can not be made available (because of licensing and/or enormous file size).

If you are not familiar with [Python] but would like to learn, the [Scipy-Lectures](http://www.scipy-lectures.org/) are a good place to start. The lessons there are directed toward the types of coding that are applicable to optical remote sensing and the specific libraries that were used to build `OpticalRS`.

## Processing Scripts

[QGIS] processing scripts are a relatively simple way to make the `OpticalRS` functionality available to [QGIS] users through a graphical user interface. `OpticalRS` provides [several processing scripts](https://github.com/jkibele/OpticalRS/tree/master/QgisProcessing) but they are still in the early stages of development. Once the scripts are better tested and documented, this section will contain more information about how to install and use them. If you're eager to give it a go before then, consult the [QGIS documentation](http://docs.qgis.org/latest/en/docs/user_manual/processing/index.html) for information on how to install and run the scripts.

[QGIS]: https://www.qgis.org/
[Python]: https://www.python.org/