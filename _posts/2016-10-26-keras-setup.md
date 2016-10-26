1. env:
windows 7
Anaconda3-4.2.0-Windows-x86_64.exe

2. set up:
2.1 install Anaconda3-4.2.0
2.2 You can "conda install" the followings based on python 3.5, not 3.4:
mingw libpython
theano
2.3 still need to use "pip" to install keras:
pip install git+https://github.com/fchollet/keras.git
2.4 To use theano, also need to install "nose parameterized":
pip install nose_parameterized


