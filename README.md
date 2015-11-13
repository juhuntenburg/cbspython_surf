Here you can find the interactive notebooks we used for the cbspython surface data session. 

* For freesurfer.ipynb notebook you need to be in the MPI CBS network. All installations and data are available there.

* For the freesurfer_free.ipynb and more_interesting_applications.ipynb we need some special setup, there are two options:

#####Option A -- Inside the MPI CBS network
* Bring a laptop with remote access to your workstation
* On your workstation try the following commands beforehand (they should all succeed):

```
source /scr/ilz1/cbspython_surf/surfenv/bin/activate
export PYTHONPATH=/scr/ilz1/cbspython_surf/brainsurfacescripts:/scr/ilz1/cbspython_surf/nilearn
```
```
python
>>> from nilearn import plotting
>>> from vtk_rw import read_vtk, write_vtk
>>> from plotting import plot_surf_stat_map
>>> import numpy
>>> numpy.__version__
'1.9.1'
```

* Clone this repo to get the notebooks or download them from [dropbox](https://www.dropbox.com/sh/kzz8k70ih8s1ha3/AADTzWJzrubA3n4kwpt4oqbIa?dl=0) (no need to download the data)
  
  
  
  
#####Option B -- On your personal computer
* Make a python 2.7 virtual environment (virtualenv / anaconda) and install the following packages:
```
ipython==4.0.0
matplotlib==1.5.0
nibabel==2.0.1
notebook==4.0.6 (you might need to install functools32 as well)
numpy==1.9.1
scikit-learn==0.17
scipy==0.16.1
seaborn==0.6.0 (will also install pandas 0.17.0)
```

* Clone the following github repos and include them in your PYTHONPATH:
  * https://github.com/juhuntenburg/brainsurfacescripts.git
  * https://github.com/juhuntenburg/nilearn.git 
  
    NOTE: for nilearn you need the branch 'enh/surface_plotting', here is a good description how to clone specific branches: http://stackoverflow.com/questions/67699/clone-all-remote-branches-with-git
* Test your installations as described above
* Download the data from [dropbox](https://www.dropbox.com/sh/kzz8k70ih8s1ha3/AADTzWJzrubA3n4kwpt4oqbIa?dl=0)
* Clone this repo to get the notebooks or download them from dropbox as well
  






