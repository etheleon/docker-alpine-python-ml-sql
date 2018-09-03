Python 3.6 Docker image + SQL
=======================

This image is based on Alpine Linux 3.6 ML image, which is only a 60MB image, and contains
[Python 3.6](https://www.python.org/).

Download size of this image is only:

[![](https://images.microbadger.com/badges/image/etheleon/docker-alpine-python3.svg)](https://microbadger.com/images/etheleon/docker-alpine-python3 "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/etheleon/docker-alpine-python3.svg)](https://microbadger.com/images/etheleon/docker-alpine-python3 "Get your own version badge on microbadger.com")

Usage Example
-------------

This image is based on etheleon/alpine-python3


* numpy
* pandas
* scipy
* scikit-learn

Download size of this image is only:



Usage Example
-------------

```bash
$ docker run --rm etheleon/alpine-python-machinelearning python3 -c 'import numpy; print(numpy.arange(3))'
```

Once you have run this command you will get printed `array([0, 1, 2])` from Python!
