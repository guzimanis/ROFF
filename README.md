# ROFF
## A Romanian Offensive Language Dataset Corpus
This dataset was designed to help improve the detection of offensive language on social media for Romanian.

## Description
Dataset generated from manually collected tweets over a period of two weeks in March 2020, at beginning of the COVID-19 virus outbreak.
It consists of 5000 Romanian tweets, which were annotated by over 30 native speakers.

## Versions
[OLID_ROFF](https://github.com/guzimanis/ROFF/blob/master/OLID_ROFF.tsv)
Version is annotated using Zampieri et al. [1] three level annotation scheme with clear tags for each level of annotation.
* First level:
  * NOT - not offensive
  * OFF - offensive
* Second level:
  * UNT - not targeted
  * TIN - targeted
* Third level:
  * NULL - no target
  * IND - individual
  * GRP - group
  * OTH - other


[ROFF](https://github.com/guzimanis/ROFF/blob/master/ROFF.tsv)
Version is annotated using Zampiere et al [1] three level annotation scheme with numbers as tags.
* First level:
  * 0 - not offensive
  * 1 - offensive
* Second level:
  * 0 - not targeted
  * 1 - targeted
* Third level:
  * 0 - no target
  * 1 - individual
  * 2 - group
  * 3 - other


## Article
The paper can be found on the ACL anthology page [here](https://aclanthology.org/2021.ranlp-1.102/).

## References
<a id="1">[1]</a> 
Zampieri et al. (2019). 
Predicting the Type and Target of Offensive Posts in Social Media 
Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers), pages 1415–1420
