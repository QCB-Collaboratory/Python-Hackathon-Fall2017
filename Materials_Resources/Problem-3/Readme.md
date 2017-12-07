# Processing a batch of very large images

<img src="../qcbCollaboratory_logo.png" height="50"/>

One common solution to process a batch of data (e.g. images, sequencing reads, etc) is to paralelize your pipeline and make use of multiple CPUs. There usually are multiple ways to paralelize a pipeline, and some details may depend on the specifications of your project. In this practice, we will paralelize a simple pipeline that processes a single-molecule [FISH](https://en.wikipedia.org/wiki/Fluorescence_in_situ_hybridization) dataset. The main goal is to identify candidate mRNA as diffraction limited spots in images.

The dataset used in this problem was kindly provided by [Rob Foreman](https://github.com/rfor10) from the [Wollman Lab](http://wollman.chem.ucla.edu/).


### Primary goal


### Technical challenges

* Basics of parallel processing in Python

* Automating the analysis of batches of large images

* Good practices for a memory efficient implementation of parallel processing in Python


### Guideline

1. Read the descriptions of two Python libraries: Threading and Multiprocessing. What are the main differences? Which would you use and why?

2. Load the sample image. How long did it take? Keep in mind we would eventually need to analyze hundreds of these images.

3.



### Resources
