prosodylab.dictionaries
=======================

A repository for dictionaries to be used with the Prosodylab-Aligner

* Kyle Gorman <gormanky@ohsu.edu>
* Michael Wagner <chael@mcgill.ca>
* Erin Olson <ekolson@mit.edu>

## Funding

* FQRSC Nouvelle Chercheur NP-132516
* SSHRC Canada Research Chair 218503
* SSHRC Digging Into Data Challenge Grant 869-2009-0004

## Usage

The above files are dictionaries that are ready for use with the Prosodylab-Aligner. In order to use them correctly, you will have to specify which dictionary you want to use, and train the Prosodylab-Aligner on a corresponding set of language data, like so:

  > $ ./align.py -d en_dictionary.txt -t training/data/directory soundfile/directory

All dictionaries have entries of the form:

  > WORD P H O N E M E S

where each word is written in all-caps and is followed by a space and the list of its phonemes.

## Contribution

If you would like to contribute a dictionary to this repository, please contact [Michael Wagner](mailto:chael@mcgill.ca).
