# Geoparsing Pliny the Elder's Natural History

*The **Geoparsing Pliny Natural History** is the first workpackage of my PhD project 'Greek Spaces in Roman Times. The construction of Greek geography in Pliny's Naturalis Historia' that aims at analyzing the geographic description of Greece in Pliny's encyclopedia. The scope of this package is to identify place names in the NH and disambiguate them by stable IDs.*

---

## Authors 
* Laura Soffiantini, KU Leuven, [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0003-4932-7912) https://orcid.org/0000-0002-7991-0466

## Description 

The jupiternotebooks contain the code to extract the annotations for places and people present in the ToposText's online version of the Natural History, evaluate the quality of the annotation against a manually curated Gold Standard, and enhance the annotation thought Named Entity Recognition. A text alignment technique between English and Latin based on string similarity is described and a ruled-based disambiguation system through online gazetteers is developed. Preliminary investigations of content modelling based on co-occurrence are performed by SNA.

## Data Sources
### NH annotated text

ToposText (https://topostext.org) is an online repository of Classical texts in translation. Texts are annotated by a ruled-based method using tags for places and people. Each entity is associated with a stable ID and place-tags also contain geographic coordinates, region and country labels.

### NH Latin text

The edition of the NH is available on LacusCurtius (https://penelope.uchicago.edu/Thayer/E/Roman/Texts/Pliny_the_Elder/home.html).

### Gazetteers

Pleiades (https://pleiades.stoa.org/) is a community-built gazetteer and graph of ancient places and reference website. It provides different download formats, including the the JavaScript Object Notation (JSON), that is the a comprehensive dump containing the attributes of place, name, name variants, location, and connection objects in the database.
