#Gaussfitter

##Installation:

   pip install https://github.com/keflavich/gaussfitter/archive/master.zip
   
or

    pip install -e git+https://github.com/keflavich/gaussfitter.git#egg=gaussfitter
 
or

   git clone https://github.com/keflavich/gaussfitter.git
   cd gaussfitter
   python setup.py install 


This code is taken from agpy, where it has resided for a long time and has had
a long, glorious history.


In short: This is a small toolkit for fitting 2D gaussians.  It makes use of mpfit.py by [Sergei Koposov](https://code.google.com/p/astrolibpy/source/browse/), and a modified versionof his code is included (by necessity) here.  It is modified primarily to
remove a scipy dependency.

Examples to come!  PRs welcome!

Tested in Python 2.7 and 3.4