# EGU 2017: Data analysis with Python and Jupyter

During the [EGU 2017](http://egu2017.eu) we presented a short course introducing
how to do data science with Python and Jupyter. This is the material used in the
course. The course itself was 90 minutes. However, there is a bit more material
that can also be used for self-study and for finding references that go more
in-depth.

## Preparation

[Install Anaconda](https://www.continuum.io/downloads), Python 3.x
version. Anaconda is an open data science platform which includes Python and
most packages necessary for doing data science. Anaconda can be installed even
without root/administrator privileges.

## Material

The course is made available as a series of Jupyter Notebooks. The notebooks can
be read directly here at Github, but you will have a better, more interactive
experience by downloading them and running the locally. How to do this is
explained [below](#downloading-the-material).

This short course is not a course in Python, the programming language. Instead
we aim to show you how Python has become a full-blown platform for doing data
science.

The following short lessons are available:

+ [Anaconda](01_anaconda.ipynb)
+ [Jupyter Notebooks](02_jupyter_notebooks.ipynb)
+ [Reading files](03_reading_files.ipynb)
+ [Working with JSON-data](04_working_with_json.ipynb)
+ [Numerical data in numpy](05_numerical_data_in_numpy.ipynb)
+ [Pandas and time series](06_pandas_and_time_series.ipynb)
+ [Plotting data](07_plotting_data.ipynb)
+ [Storing data](08_storing_data.ipynb)
+ [Distributing Jupyter notebooks](09_distributing_jupyter_notebooks.ipynb)
+ [Further resources](10_further_resources.ipynb)

## Downloading the material

The notebooks can be downloaded from this github-page, by scrolling to the top,
click the green `Clone or download`-button and then clicking the `Download ZIP`
link.

After downloading the zip-file, unpack it on your computer. Then open a terminal
(on Windows you should open a Anaconda terminal) and type

    jupyter notebook
 
This will start a local webserver, so the terminal will print some messages to
that effect. You do not need to worry about these message. Furthermore, your
default web browser will open up with a new window showing a file browser. You
can then navigate to the folder you just downloaded, and click on any of the
files to see the content.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/)
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

If you want to reuse this material, feel free to [fork](#fork-destination-box) it. If you find any
errors or have suggestions for improvements raising an [issue](issues/) or sending a
[pull request](pulls/) would be very welcome. Thank you for your interest.
