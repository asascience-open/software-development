# Python

# Start here
[Hitchier's Guide to Python - When you're done you can come back](http://docs.python-guide.org/en/latest/)

- Every builtin function: [Python Builtins for 2.7](https://docs.python.org/2/library/functions.html)
- Object Oriented Programming: 
  - [Classes in Python](https://docs.python.org/2/tutorial/classes.html)
  - [Wikipedia on OOP](http://en.wikipedia.org/wiki/Object-oriented_programming)
  - [Jeff Knupp's Article on OOP for Python](http://www.jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/)
  - [Understanding Python's with statement](http://effbot.org/zone/python-with-statement.htm)

## Python Projects

- Project Structure
- [Packages vs Modules](http://programmers.stackexchange.com/questions/111871/module-vs-package)
- [Project Skeleton BLOG](http://learnpythonthehardway.org/book/ex46.html)
- [PEP-8](https://www.python.org/dev/peps/pep-0008/)

> One of Guido's key insights is that code is read much more often than it is
> written. The guidelines provided here are intended to improve the readability
> of code and make it consistent across the wide spectrum of Python code. As PEP
> 20 says, "Readability counts".
> 
> A style guide is about consistency. Consistency with this style guide is
> important. Consistency within a project is more important. Consistency within
> one module or function is most important.
> 
> But most importantly: know when to be inconsistent -- sometimes the style guide
> just doesn't apply. When in doubt, use your best judgment. Look at other
> examples and decide what looks best. And don't hesitate to ask!
> 
> In particular: do not break backwards compatibility just to comply with this
> PEP!

## Testing

[Unit Tests](http://en.wikipedia.org/wiki/Unit_testing)

### Unit Testing in Python

- [Python unittest](https://docs.python.org/2/library/unittest.html)
- [nosetests](https://nose.readthedocs.org/en/latest/)
- [pytest](http://pytest.org/latest/)

### Continuous Integration

- [Python CI](http://docs.python-guide.org/en/latest/scenarios/ci/)

## Numerical Applications

- [numpy](http://wiki.scipy.org/Tentative_NumPy_Tutorial)
- [numpy for MATLAB users](http://wiki.scipy.org/NumPy_for_Matlab_Users)
- [matplotlib](http://matplotlib.org/users/pyplot_tutorial.html)
- [jupyter and IPython](http://matplotlib.org/users/pyplot_tutorial.html)

Vector math:

What's the difference between a and b in the following

```
import numpy as np
a = [1,2,3] + [1,2,3]
b = np.array([1,2,3]) + np.array([1,2,3])
```

- [Floating-point arithmetic](http://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)

## IPython Notebooks

- [QARTOD Example](http://nbviewer.ipython.org/github/Bobfrat/QARTOD/blob/qartod_nb/notebooks/plot_QARTOD_results.ipynb)
- [Working with Images](http://nbviewer.ipython.org/github/lukecampbell/notebooks/blob/master/Image%20Processing/Working%20with%20Images.ipynb)
- [Math Example](http://nbviewer.ipython.org/github/lukecampbell/notebooks/blob/master/Math/Lerping%20Functions.ipynb)
- [Computational Geometry](http://nbviewer.ipython.org/github/lukecampbell/notebooks/blob/master/Computational%20Geometry/Notes%20on%20Range%20Structures%20and%20Searches.ipynb)
- [Signal Processing](http://nbviewer.ipython.org/github/unpingco/Python-for-Signal-Processing/tree/master/)
- [Lagrangian Particle Transport on GPU](http://nbviewer.ipython.org/github/lukecampbell/gpu-processing/blob/master/notebooks/OpenCL%20Test.ipynb)

## Web Development
- [Flask](http://flask.pocoo.org/)
  - [The flask authentication problem](https://stormpath.com/blog/part-one-flask-authentication-problem/)
  - [The flask authentication problem part 2](https://stormpath.com/blog/part-two-solving-flask-authentication-problem/)
  - [Flask environments](https://pythonhosted.org/Flask-Environments/)
  - [Flask-restless](https://flask-restless.readthedocs.org/en/latest/)
  - [Flask SQLAlchemy](https://pythonhosted.org/Flask-SQLAlchemy/)
- [Django](https://www.djangoproject.com/)

### Links

- [PyCon 2012](http://pyvideo.org/category/17/pycon-us-2012)
- [Ugh... lxml](http://lxml.de/tutorial.html)
- [Performance in Python](http://blog.explainmydata.com/2012/07/expensive-lessons-in-python-performance.html)
- [LRU/LFU Cache Decorators](http://code.activestate.com/recipes/498245-lru-and-lfu-cache-decorators/)
- [Memoization Decorator](http://code.activestate.com/recipes/578231-probably-the-fastest-memoization-decorator-in-the-/)
- [Scipy intro page](http://www-pord.ucsd.edu/~cjiang/python.html)
- [Distributed systems with ZeroMQ](http://java.dzone.com/articles/distributed-systems-zeromq)
- [Just read it, you'll thank me later - 7 python libraries you should know about](http://doda.co/7-python-libraries-you-should-know-about/)
- [Python's super is nifty, but you can't use it](https://fuhm.net/super-harmful/)
- [FFT in Python](http://jeremykun.com/2012/07/18/the-fast-fourier-transform/)
- [Python's memory management](http://deeplearning.net/software/theano/tutorial/python-memory-management.html)
- [Memory leaks in Python](http://www.lshift.net/blog/2008/11/14/tracing-python-memory-leaks/)
- [CPython - Make an iterator](http://stackoverflow.com/questions/1815812/how-to-create-a-generator-iterator-with-the-python-c-api)
- [Fast non-standard data structures for Python](http://kmike.ru/python-data-structures/)
- [Blaze](http://continuum.io/blog/blz-format)
- [Why Python, Ruby, and Javascript are Slow](https://speakerdeck.com/alex/why-python-ruby-and-javascript-are-slow) _hint: they're not_
- [Python scientific lecture notes](http://scipy-lectures.github.io/#)
- [numpy scalars](http://docs.scipy.org/doc/numpy/reference/arrays.scalars.html#arrays-scalars-built-in)
- [numba vs cython](http://jakevdp.github.io/blog/2013/06/15/numba-vs-cython-take-2/)
- [Graphics with Matplotlib](http://kestrel.nmt.edu/~raymond/software/python_notes/paper004.html)
- [So you'd like to make a map with python](http://sensitivecities.com/so-youd-like-to-make-a-map-using-python-EN.html#.VVzb4JNVhBc)
- [Cython slides](https://python.g-node.org/python-summerschool-2011/_media/materials/cython/cython-slides.pdf)
- [Generators](http://www.dabeaz.com/finalgenerator/FinalGenerator.pdf)
- [What this wiki should be - Hitchiker's guide to Python](http://docs.python-guide.org/en/latest/)
- [Ocean Python](http://oceanpython.org/)
- [Matplotlib Stylesheets](http://nbviewer.ipython.org/github/jakevdp/PyData2014/blob/master/notebooks/06_mpl_Stylesheets.ipynb)
