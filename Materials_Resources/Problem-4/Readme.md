# Web crawler to connect with SignalP server

Predicting the presence and the location of cleavage sites of signal peptides is a complex problem. SignalP 4.1 Server uses a neural network to solve that problem for Gram-positive prokaryotes, Gram-negative prokaryotes, and eukaryotes. To use it, you can use a web interface by the Center for Biological Sequence Analysis at the Technical University of Denmark (DTU):

http://www.cbs.dtu.dk/services/SignalP/

In this project, we will develop a script to automate the detection of signal peptides and organize the output from SignalP in a fasta file.

ServerP 4.1 Server was originally proposed on [a Nature Methods paper](https://www.nature.com/articles/nmeth.1701) by TN Petersen, S Brunak, G von Heijne and H Nielsen.

### Goal

During the Hackathon, we will develop a Python script or module that automates the detection of cleavage sites of signal peptide in sequences of aminoacid. This module should control for how often the requests are made, and how the output files are saved.


### Technical challenges

* Automating genomics analyses based on online applications

* Dealing with a bottleneck when analyzing a large dataset

* Learning how to construct web crawlers


### Guideline

1. Read about web crawlers and look for which Python libraries you can use. The library should be able to fill forms.

2. Go to [SignalP 4.1 Server](http://www.cbs.dtu.dk/services/SignalP/). Try submitting one sequence and learn how the options in the form work. Pay attention to the

3. Make a scheme with each of the steps of your web crawler needs to perform. Note that you need to break your submission in chunks of 200 sequences.

4. Write your script and use the dataset provided below. Test your script with small examples before. When using a dataset with more than 200 sequences, set a generous delay between each of the batches - the service is offered for free, so let's not overwhelm it!.

5. **Extra:** Turn your script into a module.


### Dataset

### Resources

* More details about how the SignalP server works, H Nielson just published a [book chapter](https://link.springer.com/protocol/10.1007%2F978-1-4939-7015-5_6) this year.

* Read a little bit about [web crawlers](https://en.wikipedia.org/wiki/Web_crawler). They are extremely useful in many areas, including the automation of the use of online applications that do not offer APIs.

* [Old version](https://github.com/thmosqueiro/SignalPclient) of this project, developed back in 2014. Unfortunately, it doesn't work anymore.
