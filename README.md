# TELBE-raw-data-evaluation

The radiation source ELBE (**E**lectron **L**inac for beams with high **B**rilliance and low **E**mittance) at the Helmholtz Centre Dresden Rossendorf (HZDR) can produce several kinds of secondary radiations. THz radiation is one of them and can be used with a typical pulse frequency of 100 kHz as a stimulation source for elementary low-energy degrees of freedom in matter. It was used in the \"Phase-resolved Higgs response in superconducting cuprates\" publication (DOI: [10.1038/s41467-020-15613-1](https://doi.org/10.1038/s41467-020-15613-1)). The raw data for this publication can be accessed on RODARE (DOI: [10.14278/rodare.277](https://doi.org/10.14278/rodare.277)) and will be used to reproduce the figures from the publication

This Jupyter notebook enables the user to handle the raw data from an TELBE THz experiment. To sample the whole THz wave the laser path length is modified by moving specific mirrors. The raw data contains for each mirror position a binary file storing the signal spectra and a folder with gray scaled tiff files storing the jitter timing.

Parts of the code are parallelized and can run on multiple cores. The execution time on a single core is roughly 15 min after downloading and extracting a 20 GB zip file. 
