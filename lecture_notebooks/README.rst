Lecture Notebooks
=================

Notebooks added to this folder should have a prefix like `Session1` to keep
them in order.

View the notebooks online:

* `PSF_Photometry_Process <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/PSF_Photometry_Process.ipynb>`_
* `Session1_Astro_Demo <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session1_Astro_Demo.ipynb>`_
* `Session1_Demo <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session1_Demo.ipynb>`_

Updates for Session 1 notebook:

* IPython notebooks now do autosaving
* The Ipython project has a new future name of Jupyter (though it currently doesn't seem to be used that much)
* IPython notebooks now can access notebooks in subdirectories
* The notebook used in this lecture uses pyfits. That module is still available, but all future updates are to the version now resident in astropy.io.fits

* `Session1_Introduction <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session1_Introduction.ipynb>`_

Updates for Session 2 notebook: (22 Jan 2015, rij):

* use of pyfits changed to astropy.io.fits as fits
* plotting commands now prefixed with 'pyplot.'
* updated directory locations to refer to my Windows laptop

* `Session2_Basic <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session2_Basic.ipynb>`_
* `Session3_Phot_Phun_1 <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session3_Phot_Phun_1.ipynb>`_
* `Session4_phot_2 <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session4_phot_2.ipynb>`_
* `Session5_STIS_Spec <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session5_STIS_Spec.ipynb>`_
* `Session6_Exceptions <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session6_Exceptions.ipynb>`_
* `Session6_Various_Topics <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session6_Various_Topics.ipynb>`_

Updates for Session 3 notebook: (2, Feb 2015, mls):

* I created an alternate notebook with the updates detailed below already implemented, it has the same name but with a u appended before the suffix: `Session3_Photometry <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session3_Phot_Phun_1u.ipynb>`_

* The notebook used in this lecture uses pyfits. That module is still available, but all future updates are to the version now resident in astropy.io.fits.
* For some reason the np and plt references are not in the notebook, I've added them in the appropriate places since those functions are not implicitly imported at the top.
* astropy ascii tables with INDEF values are now read in as masked arrays. In order to removed the masked values from the table you don't need to select on the string INDEF, you can use the mask to create new arrays. The example here was updated in the new notebook to reflect that.
* An alternate notebook using `photutils <http://photutils.readthedocs.org/>`_ is available here: `Session 3 Photometry using photutils <http://nbviewer.ipython.org/urls/raw.github.com/spacetelescope/scientific-python-training-2015/master/lecture_notebooks/Session3_Phot_Phun_photutils.ipynb>`_

Updates for Session 4 notebook: (4, Feb 2015, mls):

* I created an alternate notebook with the updates detailed below already implemented, it has the same name but with a u appended before the suffix: `Session4_Photometry <http://nbviewer.ipython.org/github/spacetelescope/scientific-python-training-2015/blob/master/lecture_notebooks/Session4_phot_2u.ipynb>`_

* The notebook used in this lecture uses pyfits. That module is still available, but all future updates are to the version now resident in astropy.io.fits.
* Updated the making running scripts to specify execution in the bash shell
* Added links to PyCharm and Wing, to of the more popular IDEs to encourage that for developments purposes
* Made a minor text edit to the text explaining crashes in the Defaults and Arguments section
* Made minor edit for bash style execution on  bozo3.py run example
* Added an example of downselecting an astropy table using a combination of one columns mask values and numerical values in two other columns
* Made some minor text edits in the completeness testing section
* I updated the scripts which are associated with the lecture examples

