# dataframe_visualiser
Make simple high-level visualisations of a Pandas dataframe to help when starting new data projects

This is a Python 3 project (and with some tiny edits it would run in Python 2.7).

To run:

    >>> # assuming IPython and Python 3.4
    >>> import visualise_dataframe
    >>> visualise_dataframe.summarise(df)  # draw single-variable plot
    >>> visualise_dataframe.summarise(df, dependent_col=xxx)  # draw dependent-variable plot

If you run the script then the example will load the Kaggle Titanic competition's `train.csv` file and will draw a single-variable plot.
