# slippy
Slip inversion in Python

This is a bare-bones code at the moment, but can load in a best-fitting single rectangular dislocation (a fault geometry) and solve for slip on an expanded version of it. It takes okinv-format input (as produced by [my quadtree workflow](https://github.com/geniusinaction/prepareInSARdata).

I am very slowly adding improvements, but probably at the rate of one every two years!

Dependencies:
- [okada_wrapper](https://github.com/tbenthompson/okada_wrapper)
- [okapy](https://github.com/geniusinaction/okapy)
- numpy
- SciPy
- matplotlib
