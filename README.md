# Introduction to random forests

Trees and forests, robust estimators for the 99%.

---

By the end you will know:

* the basics of [`scikit-learn`](http://scikit-learn.org/stable/)
* how to use Decision Trees and Random Forests
* how to use cross-validation to measure performance
* that there are many metrics by which to measure performance

Shown at [PyZurich July 2016](https://www.meetup.com/pyzurich/events/231559803/).


# Install instructions

[Anaconda](https://www.continuum.io/downloads) is a python distribution that
is easy to install and contains a large number of commonly used libraries.
Download anaconda and then from this directory run:
```
conda create -n forests-intro --file=environment.yml
```
This will create an environment with all the dependencies for these examples.


# Try it

After setting up the dependencies, activate your `conda` environment with
`source activate forests-intro`. To run the examples simply run
`jupyter notebook` from a terminal in this directory.


# Additional material

* [Visual explanation of Decision trees][visualtrees]
* [Neural network playground](http://playground.tensorflow.org/)
* [Unbiased performance estimates][unbiased]
* [Understanding Random Forests](https://github.com/glouppe/phd-thesis)

[visualtrees]: http://www.r2d3.us/visual-intro-to-machine-learning-part-1/
[unbiased]: http://betatim.github.io/posts/unbiased-performance/


# License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Geneva's Humanitarian Big Data</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/wildtreetech/ghbd" property="cc:attributionName" rel="cc:attributionURL">Tim Head</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
