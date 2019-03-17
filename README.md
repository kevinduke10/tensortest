# tensortest

BLUF: Extremely simple way to get a Jupyter Notebook running on your local box to play with Tensorflow w/o having to install anything except Docker.
We'll use this to train Tectonix to do change/anomoly detection.

Getting Started
----------------
  1) Download Docker
  2) Run this command with the path to the notebooks from this repo replacing my ~/Tectonix/notebooks location
  
    docker run -it --rm -v ~/Tectonix/notebooks:/tf/notebooks -p 8888:8888 tensorflow/tensorflow:latest-py3-jupyter
    
  3) Open a browser to localhost:8888 with the token you see from the startup on your command line.
  
