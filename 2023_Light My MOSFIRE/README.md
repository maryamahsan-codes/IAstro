# Exploring star formation in SDSS galaxies

An exploratory notebook from my 2023 online internship at the Instituto de Astrofísica e Ciências do Espaço (IA), prepared for the project *Light My MOSFIRE*. We used SDSS spectra and supplied FADO measurements to examine how low redshift galaxies in different parts of the star formation rate–stellar mass plane might differ.

**Start here:** Read [`Project_Guide.pdf`](Project_Guide.pdf) for the motivation, methods, equations, references, terminology and practical notes. The analysis is in [`IAstro 2023-Light My MOSFIRE.ipynb`](IAstro%202023-Light%20My%20MOSFIRE.ipynb).

The notebook follows six stages: join the supplied FITS tables; select emission-line galaxies; classify them on a BPT diagram; estimate fibre and total star formation rates; select subsamples of the star-forming main sequence; and prepare SDSS spectra for FADO and inspect selected outputs. Its last sections are exploratory, once you know how to read and process the files, you can adapt it to suit your needs. (yet to add another segment)

## Data and reproducibility

**The supplied starting FITS tables are not included.** They were provided for the internship, and I do not have permission to redistribute them. I have included FITS outputs I generated when their contents may be redistributed, with their origin and processing noted. The notebook also contains local paths and depends on SDSS retrieval, a dust-map export and a FADO installation.

The notebook title is the internship project name; the spectra analyzed here come from SDSS, not the MOSFIRE instrument. Code is shared as an archival record of my work, with its assumptions documented in the guide.