# Python Hackathon - Problem 1 dataset

<img src="../qcbCollaboratory_logo.png" height="50"/>

[Go back to the problem statement](./Readme.md)

The dataset used in this problem was kindly provided by [Dr. Julia Mack](https://www.linkedin.com/in/julia-mack-0790a52/) from the [Arispe Lab](https://arispelab.mcdb.ucla.edu/), and was used in [their recent publication on Nature Communications](https://www.nature.com/articles/s41467-017-01741-8).

### Samples of 600s calcium imaging

* [Notch1KD_JMackNatComm2017_samples.hdf5 (4.7G)](./)

This h5 file contain 4 datasets:

```
>>> f = h5py.File('Notch1KD_JMackNatComm2017.hdf5', 'r')

>>> f.keys()
[u'slide1', u'slide2', u'slide3', u'slide4']
```


### Fmin & Fmax

* [Notch1KD_JMackNatComm2017_fmaxfmin.hdf5 (65MB)](./)
