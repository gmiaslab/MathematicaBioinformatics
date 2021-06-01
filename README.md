# Mathematica for Bioinformatics, by George Mias.
## A Wolfram Language Approach to Omics

A Wolfram Language Approach to Omics
[Springer ISBN 978-3-319-72377-8](https://doi.org/10.1007/978-3-319-72377-8)

# Supplementary Files
This repository contains the notebooks(code) and relevant datafiles accompanying the monograph.

## Release Notes
* *V.1.1.0* Code updated form *Mathematica 12.3.0* and for database compatibility.
* *V.1.0.0* Code updated to monograph release.

## Requirements
* Code tested under *Wolfram Mathematica 12.3.0* -- check earlier releases for compatibility with *Mathematica 11*.

## Instructions
* Download either of the Assets to your computer, and use the notebooks in Mathematica as companions to  the monograph.
* All files are best to be kept in the same folder.


## FAQ
### I see a warning regarding compatibility with an older version of Mathematica
* The code has been checked for compatibility with Mathematica 12.3, so if you are using a compatible version you can safely ignore the warning.
### Some of the results I get from querying the online databases do not match the answers in the notebook
* The databases queried are updated on a regular basis, and the APIs may also be updated. The code should still work, though you may get more up-to-date responses.
### Some of the randomly generated data is different when I run it
* This is expected (unless RandomSeed is set for reporducibility), as it is highly probably you will get different results from the pseudorandom generator that creates the data in these computations
### The UniProt Web API URL used in the notebooks uses https
* The notebooks have been updated for forward compatibility, since as of release 2018_06 (June 20, 2018) UniProt web pages and services will transition from http to https.
### The code in certain chapters, particularly Chapter 4 does not match the book.
* The latest notebooks released have been updated in 2021 to reflect changes in the NCBI databases examples (e.g. changes in content of dbsnp), and updates for Mathematica 12. Early relases of the code are available for Mathematica version 11.

## Links
* [MathIOmica releases](https://github.com/gmiaslab/mathiomica/releases)
* [MathIOmica site](https://mathiomica.org)

## OTHER CONTACT INFORMATION
  * George I. Mias
  * G. Mias Lab (https://georgemias.org)
  * e-mail: gmiaslab@gmail.com
  * twitter: @gmiaslab / @georgemias
