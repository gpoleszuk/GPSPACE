To compile the source code `gpspace.f`, please, check instruction in the document
https://github.com/aewallin/GPSPACE/blob/master/README.md

> #### Notes on github/aewallin GPSPACE repo

> The original repository at https://github.com/CGS-GIS/GPSPACE seems incomplete. Missing files relate to IERS2010 code available as 'external_sources' from e.g. https://github.com/HugoValcourt/GPSPACE/releases/tag/v1.10-beta
> >
> 2025-01 update, this repo mostly based on https://github.com/demiangomez/GPSPACE
> >
> 2025-01, SVB files from https://github.com/lahayef/GPSPACE
> 
> With these additions the gpspace.f code compiles with the command:
> `gfortran -finit-local-zero -O2 -o gpspace gpspace.f */*.F`
> 
> The original repository had svb-files with data until 2018. This repo has updated gps, gnss, gln svb-files with data until 2021, 2022, 2023, 2024, etc.
> 
> Helper-scripts to run GPSPACE are at https://github.com/aewallin/ppp-tools
> 
Source: https://github.com/aewallin/GPSPACE/blob/master/README.md
