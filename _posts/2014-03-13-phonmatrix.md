---
title: "PhonMatrix"
description: "Visualizing phonological patterns such as vowel harmony and similar place avoidance from language data"
toc: false
comments: true
layout: post
image: images/phonmatrix.gif
hide: false
search_exclude: true
categories: [visualization, d3js, typology]
---

Visualizing phonological patterns such as vowel harmony and similar place avoidance from language data. The application can be accessed here: [http://phonmatrix.herokuapp.com/](http://phonmatrix.herokuapp.com/){:target="_blank"}.

# Description

PhonMatrix is a web-based visualization tool that statistically analyzes sound co-occurrences within words and displays the result in a symmetric sound matrix.

In the first step, the user has to upload the text file containing the word list that serves as the input to the analysis process. Text files have to be encoded in UTF-8 and list only one word per line. For a meaningful analysis the words should be given in some phonemic transcription (e.g., using IPA).

In the second step, the user can make changes to the automatic classification of symbols into vowels and consonants and exclude infrequent symbols from further consideration.

In the third step, the results of the statistical analysis of the co-occurrence counts are displayed in a quadratic matrix of sounds. The rows and columns of the matrix represent the individual sounds that are relevant for the selected context (e.g., vowels in the context of VCV sequences). The rows thereby stand for the first members of the relevant sound pairs, whereas the columns contain the sec- ond members. Each cell of the matrix then shows the result for the pair of sounds in the respective row and column.


![]({{ site.baseurl }}/images/phonmatrix.gif)

The final result is a visualization of the co-occurrence matrix with rows and columns sorted according to the similarity of the sound vectors and statistical values represented as colors in the matrix cells. The visualization features a number of interactive components that facilitate the detection of potential patterns in the results by the user.

The code is available on [Github](https://github.com/tmayer/phonmatrix){:target="_blank"}.

# Bibliography

Mayer, Thomas and Christian Rohrdantz. 2013. PhonMatrix: Visualizing co-occurrence constraints in sounds. In Proceedings of the ACL 2013 System Demonstration.

Mayer, Thomas, Christian Rohrdantz, Frans Plank, Peter Bak, Miriam Butt, Daniel A. Keim. 2010. Consonant co-occurrence in stems across languages: Automatic analysis and visualization of a phonotactic constraint. In Proceedings of the ACL 2010 Workshop on NLP and Linguistics: Finding the Common Ground (NLPLING 2010), 70–78.

Mayer, Thomas, Christian Rohrdantz, Miriam Butt, Frans Plank and Daniel A. Keim. 2010. Visualizing Vowel Harmony. Journal of Linguistic Issues in Language Technology (LiLT), Vol. 4 Issue 2, 1–33.

Rohrdantz, Christian, Thomas Mayer, Miriam Butt, Frans Plank and Daniel A. Keim. 2010. Comparative visual analysis of cross-linguistic features. In Proceedings of the International Symposium on Visual Analytics Science and Technology (EuroVAST 2010), 27–32.