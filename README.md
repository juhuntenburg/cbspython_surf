To take part in the cbspython session please do the following:

#####Option A -- Inside the MPI CBS network
* Bring a laptop with remote access to your workstation
* On your workstation try the following commands beforehand (they should all succeed):

```
source /scr/ilz1/cbspython_surf/surfenv/bin/activate
export PYTHONPATH=/scr/ilz1/cbspython_surf/brainsurfacescripts:/scr/ilz1/cbspython_surf/nilearn
```
```
python
import seaborn
from nilearn import plotting
from vtk_rw import read_vtk, write_vtk
from plotting import plot_surf_stat_map
```

* Clone this repo to get the notebooks or download them from [dropbox](https://www.dropbox.com/sh/kzz8k70ih8s1ha3/AADTzWJzrubA3n4kwpt4oqbIa?dl=0) (no need to download the data)
  
  
  
  
#####Option B -- On your personal computer
* Make a virtual environment (virtualenv / anaconda) and install the following packages:



* Clone the following github repos and include them in your PYTHONPATH:
  * https://github.com/juhuntenburg/brainsurfacescripts.git
  * https://github.com/juhuntenburg/nilearn.git 
  
    NOTE: for nilearn you need the branch 'enh/surface_plotting', here is a good description how to clone specific branches: http://stackoverflow.com/questions/67699/clone-all-remote-branches-with-git
* Test your installations as described above
* Download the data from [dropbox](https://www.dropbox.com/sh/kzz8k70ih8s1ha3/AADTzWJzrubA3n4kwpt4oqbIa?dl=0)
* Clone this repo to get the notebooks or download them from dropbox as well
  






