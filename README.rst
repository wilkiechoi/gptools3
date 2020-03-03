gptools
=======

Gaussian processes with arbitrary derivative constraints and predictions.

`gptools` is a Python package that provides a convenient, powerful and extensible implementation of Gaussian process regression (GPR). Central to `gptool`'s implementation is support for derivatives and their variances. Furthermore, the implementation supports the incorporation of arbitrary linearly transformed quantities into the GP.

Initially developed and tested using Python 2.7 and scipy 0.14.0. Updated to work with Python 3+ in March 2020. 

Full package documentation (written for Python 2.7) is located at http://gptools.readthedocs.org/

A printable PDF is available at https://media.readthedocs.org/pdf/gptools/latest/gptools.pdf

Releases (not updated with Python 3+ compatibility) are available in PyPI at https://pypi.python.org/pypi/gptools/

To install the Python 2.7 version, simply execute::

    pip install gptools

(You must already have NumPy and Cython installed for this to work.). The Python 3+ compatible version must be installed from source.

If you find this software useful, please be sure to cite it:

M.A. Chilenski et al. 2015 Nucl. Fusion 55 023012

http://stacks.iop.org/0029-5515/55/023012
