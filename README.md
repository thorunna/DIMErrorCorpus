# DMIErrorCorpus

The DMI error corpus is an Icelandic error corpus made from data from the [Database of Icelandic Morphology (DIM)](https://bin.arnastofnun.is/DMII/). Search queries which return no results in the database are used for making the corpus, intended for both general use and for correcting future search queries in the database.

Automatic correction is done using [ReynirCorrect](https://github.com/mideind/ReynirCorrect) and [Skrambi](http://skrambi.arnastofnun.is) and the 1000 most frequent search queries are manually corrected. The resulting corpus combines the manual correction, ReynirCorrect's correction and Skrambi's correction.

The error corpus is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
