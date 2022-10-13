[![DOI](https://sandbox.zenodo.org/badge/550504299.svg)](https://sandbox.zenodo.org/badge/latestdoi/550504299)

# Samoan Passage Towyo Data Archive

CTD/LADCP towyo data from the 2012 (RR1209) and 2014 (TN305) Samoan Passage cruises.

The data were collected under National Science Foundation grants OCE-1029268 and OCE-1029483.

Data are stored in human-readable format at https://osf.io/uaem3/ and can be downloaded manually from there.

A repository containing data in *git-annex* / *datalad* format is located at https://osf.io/j47pk/ and connected to this repository. To access the data this way, clone the bare dataset repository (without the data files) via:
```
datalad clone https://github.com/gunnarvoet/sp-data-archive-towyo
```
In a second step, obtain the data from the OSF repository via:
```sh
datalad get -r -d sp-data-archive-towyo/nc
```
More information on *git-annex* and *datalad* can be found in the [DataLad Handbook](https://handbook.datalad.org/en/latest/index.html).

The parent Samoan Passage Data Archive repository containing further datasets is located at https://github.com/gunnarvoet/sp-data-archive/.
