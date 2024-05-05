# Summary

UD Ancient Hebrew PTNK contains portions of the Biblia Hebraic Stuttgartensia with morphological annotations from [ETCBC](https://github.com/etcbc/bhsa).

# Introduction

This treebank contains portions of the Hebrew Bible as digitized and annotated in the [Biblia Hebraica Stuttgartensia (Amstelodamensis)](http://dx.doi.org/10.17026%2Fdans-z6y-skyh) by the [Eep Talstra Centre for Bible and Computer](http://etcbc.nl) at Vrije Universiteit Amsterdam. Those annotations are licensed under [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

The corpus can be found at [github.com/etcbc/bhsa](https://github.com/etcbc/bhsa). The dependency annotations were generated using VISL CG-3 and manually verified by Daniel Swanson. The code for generating them can be found at [https://github.com/mr-martian/hbo-UD](https://github.com/mr-martian/hbo-UD). Errors in the data should be reported to that repository.

# Data Split

The following texts are included in this treebank:

| Book    | Chapters | Split | Added |
|---------|----------|-------|-------|
| Genesis | 1-18     | Dev   | 2.10  |
|         | 19-30    | Test  | 2.10  |
|         | 31-50    | Train | 2.10  |
| Ruth    | 1-4      | Train | 2.10  |

# Acknowledgments

...

## References

```
@inproceedings{swanson-tyers-2022-universal,
    title = "A {U}niversal {D}ependencies Treebank of {A}ncient {H}ebrew",
    author = "Swanson, Daniel  and
      Tyers, Francis",
    booktitle = "Proceedings of the Thirteenth Language Resources and Evaluation Conference",
    month = jun,
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2022.lrec-1.252",
    pages = "2353--2361",
    abstract = "In this paper we present the initial construction of a Universal Dependencies treebank with morphological annotations of Ancient Hebrew containing portions of the Hebrew Scriptures (1579 sentences, 27K tokens) for use in comparative study with ancient translations and for analysis of the development of Hebrew syntax. We construct this treebank by applying a rule-based parser (300 rules) to an existing morphologically-annotated corpus with minimal constituency structure and manually verifying the output and present the results of this semi-automated annotation process and some of the annotation decisions made in the process of applying the UD guidelines to a new language.",
}
```

# Changelog

* 2022-05-15 v2.10
  * Initial release in Universal Dependencies.
  * Add Genesis and Ruth
* 2022-11-01 v2.11
  * Add FEATs `VerbForm` and `PronType`
  * Add MISC `Ref`
* 2023-11-15 v2.13
  * Add MISC `Gloss`
* v2.14
  * Add MISC `Gloss` more consistently

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.10
License: CC BY-NC 4.0
Includes text: yes
Genre: bible
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Swanson, Daniel
Contributing: elsewhere
Contact: awesomeevildudes@gmail.com
===============================================================================
</pre>
