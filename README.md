# IntronNeoantigen
A pipeline for calling intron retained derived neoantigens using RNA-Seq data

##  Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

##  Prerequisites
Make sure the following programs are in your `PATH`:
- [Samtools v1.19](http://www.htslib.org/)
- [bedtools v2.27.1](http://bedtools.readthedocs.io/)
- [pigz v2.3.1](https://zlib.net/pigz/)
- [Kallisto v0.44.0](https://pachterlab.github.io/kallisto/)
- Python 3.6+
- [NetMHCpan-4.0](https://services.healthtech.dtu.dk/service.php?NetMHCpan-4.0)
--arcasHLA reference --update


IntronNeoantigen requires the following Python modules:
- [HTSeq](https://pypi.org/project/HTSeq/)
- [pysam](https://pypi.org/project/pysam/)
- NumPy
- collections
- multiprocessing
