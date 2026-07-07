<!-- #region -->
# XMM- Newton pySAS Documentation

This repository contains instruction documents, example scripts, and example Jupyter Notebooks associated with [XMM-Newton's pySAS](https://github.com/XMMGOF/pysas). You can clone this repository onto your local machine by using the command,

```
git clone https://github.com/XMMGOF/pysas_docs.git
```

To use these Jupyter Notebooks you will need to install HEASoft, SAS, and pySAS. See the [README for pySAS](https://github.com/XMMGOF/pysas) for further instructions.

If you would like to contribute a notebook please contact us! Either through the <a href="https://heasarc.gsfc.nasa.gov/docs/xmm/xmm_helpdesk.html">XMM Newton GOF Helpdesk</a> or by emailing Ryan Tanner directly (ryan.tanner@nasa.gov). If you would like to showcase your science please let us know. We can work with you to turn your science results into an excellent tutorial.

<div class="alert alert-block alert-info">
<b>Note:</b> These notebooks have been updated to work with pySAS v2.5.0 or higher.</div>

# pySAS/SAS Tutorial Notebooks

Each tutorial has a level of difficulty:

- `Beginner`
- `Intermediate`
- `Advanced`

The Obs ID used for the tutorial will also be noted.

## 1. Basic pySAS

&#9672; [pySAS Introduction -- Short Version](./Jupyter_Notebooks/analysis-xmm-short-intro.ipynb) (`Beginner` - Obs ID: 0802710101): A short introduction to pySAS.

&#9672; [pySAS Introduction -- Long Version](./Jupyter_Notebooks/analysis-xmm-long-intro.ipynb) (`Beginner` - Obs ID: 0802710101): A long introduction to pySAS.

&#9672; [The Absolute Beginner's Guide to XMM-Newton (pdf)](./The_Absolute_Beginners_Guide_to_XMM.pdf) (`Beginner` - Obs ID: N/A): The Absolute Beginner's Guide to XMM-Newton.

&#9672; [First Time using pySAS on Fornax](./Fornax_simple_config.ipynb) (`Beginner` - Obs ID: N/A): Notebook to help set pySAS user defaults on Fornax.

## 2. ABC Guide Notebooks

&#9672; [ABC Guide for XMM-Newton -- EPIC Image Creation and Basic Filtering](./Jupyter_Notebooks/analysis-xmm-ABC-guide-EPIC-image-filtering.ipynb) (`Beginner` - Obs ID: 0123700101): XMM-Newton ABC Guide, EPIC Image Creation and Basic Filtering.

&#9672; [ABC Guide for XMM-Newton -- EPIC Source Extraction and Spectrum Creation](./Jupyter_Notebooks/analysis-xmm-ABC-guide-EPIC-image-filtering.ipynb) (`Beginner` - Obs ID: 0123700101): XMM-Newton ABC Guide, EPIC Source Extraction and Spectrum Creation.

&#9672; [ABC Guide for XMM-Newton -- Fitting an EPIC Spectrum in XSPEC](./Jupyter_Notebooks/analysis-xmm-ABC-guide-spectra-fitting.ipynb) (`Beginner` - Obs ID: 0123700101): XMM-Newton ABC Guide, Fitting an EPIC Spectrum in XSPEC.

&#9672; [ABC Guide for XMM-Newton -- Timing Mode Data Processing](./Jupyter_Notebooks/analysis-xmm-ABC-guide-timing-mode.ipynb) (`Beginner` - Obs ID: 0400550201): XMM-Newton ABC Guide, Timing Mode Data Processing.

&#9672; [ABC Guide for XMM-Newton -- RGS Data Processing](./Jupyter_Notebooks/analysis-xmm-ABC-guide-RGS-data.ipynb) (`Beginner` - Obs ID: 0153950701): XMM-Newton ABC Guide, RGS Data Processing.

&#9672; [ABC Guide for XMM-Newton -- Optical Monitor (OM)](./Jupyter_Notebooks/analysis-xmm-ABC-guide-optical-monitor.ipynb) (`Beginner` - Obs ID: 0123700101, 0411081601, 0125320801): XMM-Newton ABC Guide, Introduction to Optical Monitor Data.

### 2.1 ABC Guide Notebooks -- Using PPS Files

&#9672; [ABC Guide (PPS) for XMM-Newton -- EPIC Image Creation and Basic Filtering - Using PPS Files](./Jupyter_Notebooks/analysis-xmm-ABC-PPS-guide-EPIC-image-filtering.ipynb) (`Beginner` - Obs ID: 0123700101): XMM-Newton ABC Guide, EPIC Image Creation and Basic Filtering, using PPS Files.

&#9672; [ABC Guide (PPS) for XMM-Newton -- EPIC Source Extraction and Spectrum Creation - Using PPS Files](./Jupyter_Notebooks/analysis-xmm-ABC-PPS-guide-EPIC-source-spectrum.ipynb) (`Beginner` - Obs ID: 0123700101): XMM-Newton ABC Guide, EPIC Source Extraction and Spectrum Creation, using PPS Files.

&#9672; [ABC Guide (PPS) for XMM-Newton -- Timing Mode Data Processing - Using PPS Files](./Jupyter_Notebooks/analysis-xmm-ABC-PPS-guide-timing-mode.ipynb) (`Beginner` - Obs ID: 0123700101): XMM-Newton ABC Guide, EPIC Source Extraction and Spectrum Creation, using PPS Files.


## 3. Specific Topics

&#9672; [Generating EPIC Event Lists](./Jupyter_Notebooks/analysis-xmm-epic-reprocessing.ipynb) (`Beginner` - Obs ID: 0104860501): A guide for processing data from all EPIC cameras on XMM.

&#9672; [Combining the Spectra of the 3 EPIC Cameras -- Part 1: Filtering the Observation](./Jupyter_Notebooks/analysis-xmm-combining-spectra-pt1.ipynb) (`Intermediate` - Obs ID: 0111240101): Step-by-step guide to combine the spectra of all three EPIC camera exposures into one single spectrum with corresponding rmf, arf and bkg files.

&#9672; [Combining the Spectra of the 3 EPIC Cameras -- Part 2: Applying XSPEC Models to the Spectra](./Jupyter_Notebooks/analysis-xmm-combining-spectra-pt2.ipynb) (`Intermediate` - Obs ID: 0111240101): Applying various XSPEC models to the spectra using pyXSPEC and evaluating the fitness of the models.

&#9672; [Combining the Spectra of the 3 EPIC Cameras -- Part 2 (Short Version): Applying XSPEC Models to the Spectra](./Jupyter_Notebooks/analysis-xmm-combining-spectra-pt2-short.ipynb) (`Intermediate` - Obs ID: 0111240101): Applying various XSPEC models to the spectra using pyXSPEC and evaluating the fitness of the models. (Short Version)

&#9672; [Dealing with Pile-up in an EPIC Source](./Jupyter_Notebooks/analysis-xmm-dealing-with-pile-up.ipynb) (`Intermediate` - Obs ID: 0112880701): Introduction on how to deal with pile-up from a bright source.

&#9672; [Dealing with EPIC Out-of-Time Events -- Part 1: Images](./Jupyter_Notebooks/analysis-xmm-dealing-with-out-of-time-events-pt1.ipynb) (`Intermediate` - Obs ID: 0111240101): This thread will allow the user to create an image cleaned from out-of-time events.

&#9672; [Dealing with EPIC Out-of-Time Events -- Part 2: Spectra](./Jupyter_Notebooks/analysis-xmm-dealing-with-out-of-time-events-pt2.ipynb) (`Intermediate` - Obs ID: 0111240101): This thread will allow the user to create a spectrum cleaned from out-of-time events.

&#9672; [Source Detection with edetect_chain -- Part 1](./Jupyter_Notebooks/analysis-xmm-source-detection-p1.ipynb) (`Intermediate` - Obs ID: 0123700101): Using `edetect_chain` to automatically detect sources.

&#9672; [Source Detection with edetect_chain -- Part 2](./Jupyter_Notebooks/analysis-xmm-source-detection-p2.ipynb) (`Intermediate` - Obs ID: 0123700101): Using `edetect_chain` to simultaneously detect sources in all three EPIC cameras.

&#9672; [EPIC Source Finding Thread: Step-by-Step](./Jupyter_Notebooks/analysis-xmm-step-by-step-source-detection.ipynb) (`Advanced` - Obs ID: 0123700101): A step-by-step recipe to run the source detection chain (`edetect_chain`) in SAS.

&#9672; [How to Use EPIC Instrumental Background Files -- Part 1: Images](./Jupyter_Notebooks/analysis-xmm-how-to-use-EPIC-background-files-pt1.ipynb) (`Intermediate` - Obs ID: 0555630101): The tutorial shows how to produce a Filter Wheel Closed image, and illustrates how it can be used to correct the science data for instrumental background.

&#9672; How to Use EPIC Instrumental Background Files -- Part 2: Spectra (Coming soon!) (`Intermediate` - Obs ID: 0693741001): The tutorial shows how to produce a Filter Wheel Closed spectrum, and illustrates how it can be used to correct the science data for instrumental background.

&#9672; [RGS+EPIC Joint Spectral Fitting Part 1: Data Processing](./Jupyter_Notebooks/analysis-xmm-RGS-EPIC-Joint-Fitting-Part-1.ipynb) (`Advanced` - Obs ID: 0601390201): XMM-Newton - RGS+EPIC Joint Spectral Fitting.

&#9672; [RGS+EPIC Joint Spectral Fitting Part 2: Fitting the Spectra](./Jupyter_Notebooks/analysis-xmm-RGS-EPIC-Joint-Fitting-Part-2.ipynb) (`Advanced` - Obs ID: 0601390201): XMM-Newton - RGS+EPIC Joint Spectral Fitting.

## 4. Science Examples

&#9672; [Imaging a Flare from Sagittarius A*](./Jupyter_Notebooks/science-xmm-Sag-A-Star-Flare.ipynb) (`Intermediate` - Obs ID: 0112972101): Creating images of a flare from Sagittarius A*. Based on Goldwurm et al. (2003) (DOI [10.1086/345749](https://doi.org/10.1086/345749)). 

&#9672; [Comparing Changes in Tycho's Supernova Remnant Across Time](./Jupyter_Notebooks/science-xmm-comparing-changes-in-Tycho-SN.ipynb) (`Advanced` - Obs ID: Multiple): Tutorial on comparing changes in Tycho's Supernova Remnant over many years.

## 5. Miscellaneous Notebooks

&#9672; [Using PyVO to Find Observations for Analysis](./Jupyter_Notebooks/misc-xmm-using-pyvo-to-find-obsids.ipynb) (`Beginner` - Obs ID: Multiple): A tutorial on using PyVO to find Obs IDs for Analysis.

&#9672; [Merging Event Lists From Multiple Obs IDs](./Jupyter_Notebooks/analysis-xmm-Merging-Different-Obs-IDs.ipynb) (`Intermediate` - Obs ID: Multiple): Merging event lists from multiple Obs IDs to create a mosaiced image.

&#9672; [XMM-Newton Event List Structure](./Jupyter_Notebooks/misc-xmm-event-list-structure.ipynb) (`Intermediate` - Obs ID: 0079570201): A basic guide to the internal structure of an XMM-Newton event list.

&#9672; [Introduction to Pipeline Processing System (PPS) Files](./Jupyter_Notebooks/misc-xmm-PPS-Files.ipynb) (`Intermediate` - Obs ID: 0653860101): This tutorial explains the basics of Pipeline Processing System (PPS) files for XMM-Newton.



<!-- #endregion -->
