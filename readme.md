### A database of bipolar active regions violating the Hale's law on the Sun

#### Description

Active regions on the Sun obey certain regularities. Among them is the Hale's law, which says that during an even (or odd) 11-year cycle of solar activity, leading polarities of active regions have negative (or positive) polarity in the Northern Hemisphere of the Sun, and positive (or negative) polarity in its Southern Hemisphere. The Hale's law has exceptions. The created database contains bipolar active regions that violate the Hale's law over the period of 1989-2020.

#### Database structure

The database includes 277 solar active regions violating the Hale's law. For each active region, the database contains data at the maximum of evolution (at the maximum of sunspot area). These data are presented as a table and divided into 3 blocks:
1) USAF/NOAA SRS;
2) DPD;
3) special marks.

The database is stored in formats: h5, csv, and html.

**"h5"** refers to HDF-format, see details [here](https://en.wikipedia.org/wiki/Hierarchical_Data_Format).
<br>
**"csv"** is a simple text format to store tabular data.

#### Related Publications

[Zhukova, A., Khlystova, A., Abramenko, V., Sokoloff, D. A Catalog of Bipolar Active Regions Violating the Hale Polarity Law, 1989 – 2018. Solar Physics 295, 165 (2020)](https://doi.org/10.1007/s11207-020-01734-9)
// [ArXiv](https://arxiv.org/abs/2010.14413)

#### Сitation of Database

Zhukova, A., Khlystova, A., Abramenko, V., Sokoloff, D. A Catalog of Bipolar Active Regions Violating the Hale Polarity Law, 1989 – 2018. Solar Physics 295, 165 (2020). https://doi.org/10.1007/s11207-020-01734-9

-----

#### Repository description

- Database in different formats with identical content:
  - barvhl.h5
  - barvhl.csv
  - barvhl.html
- Use cases in Python (folder 'examples'):
  - Database description (01-data-description.ipynb)
  - Plots for simple dependencies (02-simple-plots.ipynb)

Files with content in Russian have names with **"-ru"**
<br>
#### Requirements to run examples

* Python 3 (>3.6)
* Interactive Python
* [Pandas](https://pandas.pydata.org/docs/)
* [Numpy](https://github.com/numpy/numpy)
* [h5py](https://github.com/h5py/h5py)
* [Matplotlib](https://matplotlib.org/stable/users/installing.html)