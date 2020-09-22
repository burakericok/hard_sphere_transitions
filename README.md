# **Transitions Between Critical Points of the Configuration Spaces of Hard Spheres**

This is a notebook that allows one to visualize the precomputed transitions between the critical points of the configuration spaces of hard spheres. The transitions are computed using _the zero temperature string_ method proposed by [1, 2]. Currently, the transitions are available for $n=2$ spheres.

Note: This notebook can be used in conjunction with the notebook that plots the known critical points of the configuration spaces of hard spheres.

[1] W. E, W. Ren, and E. Vanden-Eijnden, [String method for the study of rare events](https://doi.org/10.1103/PhysRevB.66.052301), Phys. Rev. B: 66, 052301 (2002).

[2] W. E, W. Ren, and E. Vanden-Eijnden, [Simplified and improved string method for computing the minimum energypaths in barrier-crossing events](https://doi.org/10.1063/1.2720838), J. Chem. Phys.: 126,164103 (2007). 

## **Security Statement**
Connecting to a Jupyter notebook server running on your local machine can provide many benefits. With these benefits come serious potential risks. By connecting to a local runtime, you are allowing the Colaboratory frontend to execute code in the notebook using the local resources on your machine. This means that the notebook could:

- Invoke arbitrary commands (e.g. "rm -rf /")
- Access the local file system
- Run malicious content on your machine

Before attempting to connect to a local runtime, make sure you trust the authors of the notebook and ensure you understand what code is being executed. For more information on the Jupyter notebook server's security model, consult [Jupyter's documentation](https://jupyter-notebook.readthedocs.io/en/stable/security.html).

## **Usage**
The capabilities of this notebook are contained in two functions, `import_database` and `plot_transition`. These are defined in the `Define necessary functions` cell (double clicking expands the cell if you would like to examine the code). Run this cell first.

The next cell imports the database of transition between the critical points for the desired number of spheres, passed as the single argument to `import_database`. The transition databases are available for $n=2$. 

The next cell displays the transition between the selected critical points, passed as the second and the third argument to `plot_transition`. The values of these argument must be integers.

For example, to plot the transition between the first and the third critical point for two spheres:
- Run the `Define necessary functions` cell (only needs to be done once)
- Change the argument of `import_database` in the next cell to `2` and run the cell 
- Change the second and the third argument of `plot_transition` in the next cell to `1` and `3`, respectively and  run the cell

## **References**
Research into the topology of the configuration space of hard spheres is ongoing, but the references below provide some context for this project.

- Y. Baryshnikov, P. Bubenik, M. Kahle, [Min-type Morse theory for configuration spaces of hard spheres](https://doi.org/10.1093/imrn/rnt012), International Mathematics Research Notices 2014.9 (2014): 2577–2592.


## **Contributors**
The contributors to this project are (by alphabetical order of last name):

- Ozan Ericok (oericok@ucdavis.edu)
- Kashyap Ganesan (kganesan@ucdavis.edu)
- Jeremy Mason (jkmason@ucdavis.edu)

Please contact Jeremy Mason (jkmason@ucdavis.edu) for more information.

## **License**
The functions included in this archive are licenced under the [GNU General
Public License, Version 3](https://www.gnu.org/licenses/gpl-3.0.en.html).

## **Acknowledgements**
This material is based upon work supported by the National Science Foundation under Grant No. 1839370. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.







