# Axxess-Jupyter

#### Axxess and Jupyter Notebooks

[Axxess](https://github.com/DANS-repo/axxess) is a Java library to convert MS Access databases to and from csv files. Axxess can be instructed with a java property file. With that Axxess is an excellent companion when working with MSAccess databases in [Jupyter](http://jupyter.org/). It can read MS Access databases and write data and metadata to csv files. It can also reconstruct MS Access databases from csv files. There's no need to get a Java Jupyter kernel, Java installed on the system will do.

Axxess is built on the excellent Java library [Jackcess](http://jackcess.sourceforge.net/).

### Examples

- [Access to csv](https://nbviewer.jupyter.org/github/DANS-repo/axxess-jupyter/blob/master/acc2csv.ipynb) - Convert MS Access to csv. Read data and database metadata all from the comfort of your Notebook.
- [A migration scenario](https://nbviewer.jupyter.org/github/DANS-repo/axxess-jupyter/blob/master/acc2nacc.ipynb) - Migrate (older) MS Access databases to csv, zipped csv and from csv back to a newer version of MS Access.


