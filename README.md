# data_NSIDC
Scripts for opening, read data files from the National Snow and Ice Data Center (NSIDC)


# To build matching environment:
Navigate to folder in terminal and run:
conda env create --file=environment.yml

To update environment file after modifying packages:
conda env export > environment.yml


# icedrift.py

Polar Pathfinder Daily 25 km EASE-Grid Sea Ice Motion Vectors (NSIDC-0116)
This opens nc files from the Polar Pathfinder Daily 25 km EASE-Grid Sea Ice Motion Vectors, Version 4

Data set id:
NSIDC-0116
DOI: 10.5067/INAWUWO7QH7B

https://nsidc.org/data/nsidc-0116/versions/4#anchor-data-access-tools 