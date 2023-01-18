# GeoQuery Original Data

[![License: GPL v2](https://img.shields.io/badge/License-GPL_v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

Source information from the website for [GeoQuery](http://www.cs.utexas.edu/users/ml/geo.html), [Source B](http://www.cs.utexas.edu/~ml/nldata/geoquery.html).

[Made available under the GPL2.0 Licence](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) and all respective Copyright material is owned by University of Texas. I do not make a claim of ownership to any material contained within this repository. This is not my code or data, but since the original page is no longer maintained I have created this mirror resource. If you spot a mistake or submit a PR then fixes are welcome or you can [email me](mailto:tom.sherborne@ed.ac.uk).

Contains:

* GeoBase - the Knowledge Base the questions are based on
* GeoQuery880 - Most common form of the dataset (EN)
* GeoQuery250 - Subset of the data (EN)
* GeoQuery - Executable programme for logical forms to denotations (defines a Prolog function)
* eval.pl - Script for querying the KB using FUNQL logical forms.

### Papers:
* [Learning to parse database queries using inductive logic programming. Zelle & Mooney 1996](https://www.cs.utexas.edu/~ml/papers/chill-aaai-96.pdf)
```
@inproceedings{Zelle:1996:LPD:1864519.1864543,
 author = {Zelle, John M. and Mooney, Raymond J.},
 title = {Learning to Parse Database Queries Using Inductive Logic Programming},
 booktitle = {Proceedings of the Thirteenth National Conference on Artificial Intelligence - Volume 2},
 series = {AAAI'96},
 year = {1996},
 isbn = {0-262-51091-X},
 location = {Portland, Oregon},
 pages = {1050--1055},
 numpages = {6},
 url = {http://dl.acm.org/citation.cfm?id=1864519.1864543},
 acmid = {1864543},
 publisher = {AAAI Press},
} 
```


### Other links (correct as of January 2023):
* Another collection fo Geoquery resources available on GitHub at [pks/rebol](https://github.com/pks/rebol/tree/master/data/geoquery). __Note__: this repository has been archived in 12/2022 and many maintenance cannot be expected going forward.
* A survey on [Semantic Parsing from AKBC 2019](https://openreview.net/forum?id=HylaEWcTT7).
* [Learning for Semantic Parsing - Mooney 2007](https://link.springer.com/content/pdf/10.1007%2F978-3-540-70939-8.pdf).
* GeoQuery grammar used in Overnight for Lambda-DCS [here](https://worksheets.codalab.org/rest/bundles/0x40d0664a7a3c4afc853e0509e546c6c4/contents/blob/geo880.grammar).
* Instructions for installing Prolog [here](https://wwu-pi.github.io/tutorials/lectures/lsp/010_install_swi_prolog.html).
* Multilingual GeoQuery from StatNLP [here](http://www.statnlp.org/software/dataset).
* GeoQuery with query based splits and SQL queries/KB [here](https://github.com/jkkummerfeld/text2sql-data).
