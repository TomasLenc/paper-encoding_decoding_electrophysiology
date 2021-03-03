# Tutorials for Encoding/Decoding Models in Cognitive Neuroscience
This is a short collection of notebooks describing how to create encoding and decoding models of cognitive neuroscience. It accompanies the journal article [Encoding and Decoding in Cognitive Electrophysiology](https://www.frontiersin.org/articles/10.3389/fnsys.2017.00061/full).

The notebooks focus on auditory analysis and machine learning using electrophysiological signals recorded from the brain. Check out `index.ipynb` for a description of these materials, and see the Binder link below for an interactive version..

# Installing
* [This Binder link](http://beta.mybinder.org/v2/gh/choldgraf/paper-encoding_decoding_electrophysiology/f2d32d5?filepath=index.ipynb) is the easiest way to quickly interact with this repository. It should allow you to run all of the analyses and code. (or click the badge below)

If you'd like to run the code locally, simply clone this repository, make sure you have all the packages installed in the `requirements.txt` file, and open a jupyter notebook session from within the root folder.

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/choldgraf/paper-encoding_decoding_electrophysiology/f2d32d5?filepath=index.ipynb)

-----------

This requires old version of scikit-learn (below 0.18). 

This is a massive pain. First, create conda env with python 3.5 

`conda create --name enc_dec python=3.5`

Then, install scikit learn with the proper version :

`python -m pip install scikit-learn==0.17`

Then install rest of dependencies with pip (note, I set older version of MNE, the newest requires python >3.6)

`pip install -r requirements.txt`

Don't forget to restart terminal after doing this, it might happen that jupyter will not want to import some packages unless you restart completely everything. 