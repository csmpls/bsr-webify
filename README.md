
##bsr

The ***brain speed reader (bsr)*** is an experiment to understand how speed-reading through rapid visual serial presentation (RVSP) can be controlled with EEG signal as acquired through consumer grade EEG headsets. The current implementation works with Neurosky Mindwave Mobile, and a Muse connector shall be available as further develop ***bsr***.

Note that it is currently developed in a Terminal User Interface (TUI), which requires that you configure your terminal window for appropriate display (see below).

###Requirements:

The following packages are required to run ***bsr*** :

* [Beautifulsoup](https://pypi.python.org/pypi/beautifulsoup4/4.3.2) 
* [readability-lxml](https://pypi.python.org/pypi/readability-lxml)
* [numpy](https://pypi.python.org/pypi/numpy)
* [stemming](https://pypi.python.org/pypi/stemming/1.0)
* [boto](https://pypi.python.org/pypi/boto/)
* npm + node

###Instructions:
0. make sure you've installed both python and [pip](https://pypi.python.org/pypi/pip)
1. `sudo pip install beautifulsoup4 readability-lxml numpy stemming boto`
2. `npm install`
3. `node webserver.js`
4. point your browser to localhost:3000

###Supported configuration
***bsr*** has been tested with the following configuration, so far: 

* Mac OS 
* Python 
* Neurosky Mindwave Mobile 
