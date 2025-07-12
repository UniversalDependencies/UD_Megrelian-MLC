# Summary

The Megrelian UD Treebank (UD_Megrelian-MLC) is the first syntactically annotated corpus of Megrelian, based on a collection of annotated sentences selected from the Megrelian Language Corpus (MLC) available at http://xmf.iliauni.edu.ge/ . 


# Introduction

The Megrelian UD Treebank (UD_Megrelian-MLC) serves as the first syntactically annotated corpus of the Megrelian language. It includes 150 utterances randomly selected from the MLC (Gersamia et al. 2022), providing detailed annotations encompassing the grammatical structure.

The treebank's annotations align with the Universal Dependencies (UD) specifications, allowing for greater consistency and compatibility with other UD treebanks. Although the tokenization and segmentation principles of the MLC differ slightly from those of the UD, the UD_Megrelian-MLC follows the UD approach, particularly regarding multiword tokens, to minimize differences.

Morpho-syntactic annotations, as discussed in Kartozia et al. (2010), have been automatically adapted to UD requirements. This includes annotations for lemmas (LEMMA), part-of-speech categories (UPOS; XPOS), morphological features (FEATS), transliteration, and tokenization issues (MISC). Sentences were automatically converted from the MLC and then reviewed and manually corrected.

The current version of the UD_Megrelian-MLC treebank includes 150 utterances (sentences) or approx. 2000 tokens. These sentences served as a training set, enriching the treebank and offering a more comprehensive representation of the Megrelian language. The primary objective is to provide a more comprehensive and representative dataset for training and analysis purposes in future.


# Acknowledgments

The UD_Megrelian-MLC release is based on the data from the Megrelian Language Corpus (MLC) developed with the financial support of the Shota Rustaveli National Science Foundation (Project Nos. FR-21-993). 

Special gratitudes goes to Prof. Dr. Dan Zeman for his invaluable contributions in making the dataset available on GitHub and offering valuable suggestions.

## References

* Kartozia, Guram; Gersamia, Rusudan; Lomia, Maia; Tskhadaia, Taia. (2010). _megrulis lingvisturi analizi [Linguistic analysis of Megrelian]_. Tbilisi: Meridiani.


# Changelog

* 2025-11-15 v2.17
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.17
License: CC BY-SA 4.0
Includes text: yes
Genre: conversations
Lemmas: automatic with corrections
UPOS: automatic with corrections
XPOS: automatic with corrections
Features: automatic with corrections
Relations: manual native
Contributors: Lobzhanidze, Irina
Contributing: here
Contact: irina_lobzhanidze@iliauni.edu.ge
===============================================================================
</pre>
