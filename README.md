# Deep Learning
Supplemental files for the Deep Learning workshop, presented by the IDEA Student Center of UC San Diego.

## Requirements
- python 3.5
- numpy
- tensorflow 1.0
- jupyter

**NOTE:** Python 2.7 should work on macOS and Linux, but only Python 3.5 is supported for TensorFlow on Windows.


## Installation
If you previously installed Python using Anaconda, you can install the required packages using the following commands:

### macOS
1. open Terminal.app
2. run the following commands in the terminal (type each line and hit enter):
    1. create a new Anaconda environment: ``conda create -n tensorflow python=3.5 numpy scipy matplotlib jupyter``
    2. activate the environment: ``source activate tensorflow``
    3. install TensorFlow: ``pip install --upgrade tensorflow``

### Windows
1. open the Anaconda Command Prompt
2. run the following commands in the terminal (type each line and hit enter):
    1. create a new Anaconda environment: ``conda create -n tensorflow python=3.5 numpy scipy matplotlib jupyter``
    2. activate the environment: ``activate tensorflow``
    3. install TensorFlow: ``pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.0.0-cp35-cp35m-win_x86_64.whl``

### Linux
1. open a terminal program
2. run the following commands in the terminal (type each line and hit enter):
    1. create a new Anaconda environment: ``conda create -n tensorflow python=3.5 numpy scipy matplotlib jupyter``
    2. activate the environment: ``source activate tensorflow``
    3. install TensorFlow: ``pip install --upgrade tensorflow``


### Testing the installation
To test the installation (for macOS, Windows or Linux), run the following commands in the same terminal from above:
- start python and load TensorFlow: ``python -c "import tensorflow; print(tensorflow.__version__)"``

You should see output similar to the following:
```bash
> python -c "import tensorflow; print(tensorflow.__version__)"
1.0.0
```

### Non-Anaconda installation
If you did not previously install Python using Anaconda, then you can following the installation instructions listed in the official TensorFlow documentation: https://www.tensorflow.org/install/


## Demos
Online demos:
- ConvNetJS: https://cs.stanford.edu/people/karpathy/convnetjs/
- Caffe: http://demo.caffe.berkeleyvision.org/
- Deep playground: http://playground.tensorflow.org/

Articles:
- https://cloud.google.com/blog/big-data/2016/07/understanding-neural-networks-with-tensorflow-playground 

## Other TensorFlow tutorials
- https://github.com/aymericdamien/TensorFlow-Examples
- https://github.com/Hvass-Labs/TensorFlow-Tutorials
- https://www.oreilly.com/learning/not-another-mnist-tutorial-with-tensorflow
