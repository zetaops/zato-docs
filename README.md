zato-docs
=========

Documentation for https://zato.io/docs

Each major Zato release has its own subdirectory, for instance, 1.1 or 2.0.

To build HTML documentation (here, 1.1):

```
$ cd ~
$ git clone https://github.com/zatosource/zato-docs.git
$ cd zato-docs/1.1/sphinx
$ make virtualenv
$ make html
```

Now the output HTML is in ```~/zato-docs/1.1/sphinx/_build/html/index.html```.