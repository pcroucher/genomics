genomics
========

A collection of assorted genomics and next generation sequencing tools (mostly Python) that I have written to do an assorted (perhaps eclectic) array of tasks with genomics and ngs datafiles!

I will gradually add to this repository over-time - check back here!

Currently available tools:

1) "transcript2pe.py"
"transcript2pe" is a Python program (tested under Python 2.7.3) that takes as input a multi-fasta (.fa) format file containing a transcriptome assembly (for example as output by Trinity [1]). The assembled transcripts are then converted into 'dummy' paired end fastq (.fq) Illumina style files, using a sliding-window algorithm, that may be used for genome scaffolding (for example).

