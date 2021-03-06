docker-keras
============

***docker-keras*** is a minimal [*Docker*](http://www.docker.com/) image built from *Debian 9* (amd64) for reproducible deep learning based on [*Keras*](http://keras.io/). It features minimal images for *Python 2 or 3*, [*TensorFlow*](http://www.tensorflow.org/) or [*Theano*](http://deeplearning.net/software/theano/) backends, processing on CPU or GPU, and uses only Debian and Python packages (no manual installations).

Open source project:

- <i class="fa fa-fw fa-home"></i> home: <http://gw.tnode.com/docker/keras/>
- <i class="fa fa-fw fa-github-square"></i> github: <http://github.com/gw0/docker-keras/>
- <i class="fa fa-fw fa-laptop"></i> technology: *debian*, *keras*, *tensorflow*, *theano*, *openblas*, *cuda toolkit*, *python*, *numpy*, *h5py*, *matplotlib*
- <i class="fa fa-fw fa-database"></i> docker hub: <https://hub.docker.com/r/gw000/keras/>

Available tags:

- `1.1.1-py2`, `1.1.1-cpu`, `1.1.1`, `latest` points to `1.1.1-py2-tf-cpu`
- `1.1.1-py3` points to `1.1.1-py3-tf-cpu`
- `1.1.1-gpu` points to `1.1.1-py2-tf-gpu`
- `1.1.1-py2-tf-cpu`/`1.1.1-py2-tf-gpu` [2016-10-31]: *Python 2* + *Keras* <small>(1.1.1)</small> + *TensorFlow* <small>(0.10.0)</small> on CPU/GPU ([*Dockerfile.py2-tf-cpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py2-tf-cpu)/[*.py2-tf-gpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py2-tf-gpu))
- `1.1.1-py2-th-cpu`/`1.1.1-py2-th-gpu` [2016-10-31]: *Python 2* + *Keras* <small>(1.1.1)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU ([*Dockerfile.py2-th-cpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py2-th-cpu)/[*.py2-th-gpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py2-th-gpu))
- `1.1.1-py3-tf-cpu`/`1.1.1-py3-tf-gpu` [2016-10-31]: *Python 2* + *Keras* <small>(1.1.1)</small> + *TensorFlow* <small>(0.10.0)</small> on CPU/GPU ([*Dockerfile.py3-tf-cpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py3-tf-cpu)/[*.py3-tf-gpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py3-tf-gpu))
- `1.1.1-py3-th-cpu`/`1.1.1-py3-th-gpu` [2016-10-31]: *Python 2* + *Keras* <small>(1.1.1)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU ([*Dockerfile.py3-th-cpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py3-th-cpu)/[*.py3-th-gpu*](http://github.com/gw0/docker-keras/blob/master/Dockerfile.py3-th-gpu))
- `1.1.0-py2-tf-cpu`/`1.1.0-py2-tf-gpu` [2016-09-20]: *Python 2* + *Keras* <small>(1.1.0)</small> + *TensorFlow* <small>(0.10.0)</small> on CPU/GPU
- `1.1.0-py2-th-cpu`/`1.1.0-py2-th-gpu` [2016-09-20]: *Python 2* + *Keras* <small>(1.1.0)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.1.0-py3-tf-cpu`/`1.1.0-py3-tf-gpu` [2016-09-20]: *Python 2* + *Keras* <small>(1.1.0)</small> + *TensorFlow* <small>(0.10.0)</small> on CPU/GPU
- `1.1.0-py3-th-cpu`/`1.1.0-py3-th-gpu` [2016-09-20]: *Python 2* + *Keras* <small>(1.1.0)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.0.8-py2-tf-cpu`/`1.0.8-py2-tf-gpu` [2016-08-28]: *Python 2* + *Keras* <small>(1.0.8)</small> + *TensorFlow* <small>(0.9.0)</small> on CPU/GPU
- `1.0.8-py2-th-cpu`/`1.0.8-py2-th-gpu` [2016-08-28]: *Python 2* + *Keras* <small>(1.0.8)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.0.8-py3-tf-cpu`/`1.0.8-py3-tf-gpu` [2016-08-28]: *Python 2* + *Keras* <small>(1.0.8)</small> + *TensorFlow* <small>(0.9.0)</small> on CPU/GPU
- `1.0.8-py3-th-cpu`/`1.0.8-py3-th-gpu` [2016-08-28]: *Python 2* + *Keras* <small>(1.0.8)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.0.6-py2-tf-cpu`/`1.0.6-py2-tf-gpu` [2016-07-20]: *Python 2* + *Keras* <small>(1.0.6)</small> + *TensorFlow* <small>(0.9.0)</small> on CPU/GPU
- `1.0.6-py2-th-cpu`/`1.0.6-py2-th-gpu` [2016-07-20]: *Python 2* + *Keras* <small>(1.0.6)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.0.6-py3-tf-cpu`/`1.0.6-py3-tf-gpu` [2016-07-20]: *Python 2* + *Keras* <small>(1.0.6)</small> + *TensorFlow* <small>(0.9.0)</small> on CPU/GPU
- `1.0.6-py3-th-cpu`/`1.0.6-py3-th-gpu` [2016-07-20]: *Python 2* + *Keras* <small>(1.0.6)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.0.4-py2-tf-cpu`/`1.0.4-py2-tf-gpu` [2016-06-16]: *Python 2* + *Keras* <small>(1.0.4)</small> + *TensorFlow* <small>(0.8.0)</small> on CPU/GPU
- `1.0.4-py2-th-cpu`/`1.0.4-py2-th-gpu` [2016-06-16]: *Python 2* + *Keras* <small>(1.0.4)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.0.4-py3-tf-cpu`/`1.0.4-py3-tf-gpu` [2016-06-16]: *Python 2* + *Keras* <small>(1.0.4)</small> + *TensorFlow* <small>(0.8.0)</small> on CPU/GPU
- `1.0.4-py3-th-cpu`/`1.0.4-py3-th-gpu` [2016-06-16]: *Python 2* + *Keras* <small>(1.0.4)</small> + *Theano* <small>(0.8.2)</small> on CPU/GPU
- `1.0.1-py2-th-cpu`/`1.0.1-py2-th-gpu` [2016-04-16]: *Python 2* + *Keras* <small>(1.0.1)</small> + *Theano* <small>(0.8.1)</small> on CPU/GPU
- `0.3.3-py2-th-cpu`/`0.3.3-py2-th-gpu` [2016-03-31]: *Python 2* + *Keras* <small>(0.3.3)</small> + *Theano* <small>(0.8.1)</small> on CPU/GPU


Usage
=====

Quick experiment with latest Keras (with TensorFlow backend on CPU) and your Python 2 code in `/srv/ai`:

```bash
$ docker run -it --rm -v /srv/ai:/srv/ai gw000/keras /srv/ai/run.py
```

Or using TensorFlow backend on GPUs (see [docker-debian-cuda](http://gw.tnode.com/docker/debian-cuda/)) in Python 2:

```bash
$ docker run -it --rm $(ls /dev/nvidia* | xargs -I{} echo '--device={}') -v /srv/ai:/srv/ai gw000/keras:1.0.4-py2-tf-gpu /srv/ai/run.py
```

Or using Theano backend on GPUs (see [docker-debian-cuda](http://gw.tnode.com/docker/debian-cuda/)) in Python 3:

```bash
$ docker run -it --rm $(ls /dev/nvidia* | xargs -I{} echo '--device={}') -v /srv/ai:/srv/ai gw000/keras:1.0.4-py3-th-gpu /srv/ai/run.py
```

Or specify a fixed version in your `Dockerfile` for reproducible deep learning:

```
FROM gw000/keras:1.0.8-py2-th-cpu

ADD ai/ /srv/ai/
RUN chmod +x /srv/ai/run.py

CMD ["/srv/ai/run.py"]
```

If you are looking for a full deep learning research environment based on *Keras* and *Jupyter*, check out [docker-keras-full](http://gw.tnode.com/docker/keras-full/).


Feedback
========

If you encounter any bugs or have feature requests, please file them in the [issue tracker](http://github.com/gw0/docker-keras/issues/) or even develop it yourself and submit a pull request over [GitHub](http://github.com/gw0/docker-keras/).


License
=======

Copyright &copy; 2016 *gw0* [<http://gw.tnode.com/>] &lt;<gw.2016@tnode.com>&gt;

This library is licensed under the [GNU Affero General Public License 3.0+](LICENSE_AGPL-3.0.txt) (AGPL-3.0+). Note that it is mandatory to make all modifications and complete source code of this library publicly available to any user.
