# Pipelines at WEHI
This library provides utilities and wrappers to allow deployment of Toil pipelines on WEHI infrastructure.

1. `drmaaBatchSystem` provides DRMAA batch system for use with Toil. This, in turn, works well with Torque.
2. `cwlwehi` is similar to `cwltoil` or `cwltool` in that it can execute CWL.  In this case, it also hooks in the `drmaaBatchSystem`. 

To use, create and activate a virtualenv then
```
pip install git+https://github.com/WEHI-ResearchComputing/wehi-pipeline
```
The required dependencies will also be installed.

