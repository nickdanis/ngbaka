# Ngbaka [nga] Word List supplement

This is intended as a supplement to Danis (2019). The notebook [danis2019-notebook.ipynb](danis2019-notebook.ipynb) uses the same coded wordlist as the original article ([danis2019-word-list.csv](danis2019-word-list.csv)). Howevever, in the original article, the wordlist was manipulated in Excel to create the 2x2 contingency tables and these were then tested in R for significance using Fisher's exact test. Here, pandas is used to do all the manipulations in a clear and reproducible way, for posterity. 

This wordlist is extracted from [Maes 1959](https://www.worldcat.org/title/dictionnaire-ngbaka-francais-neerlandais-prec-dun-apercu-grammatical/oclc/251249793), which is a dictionary of [Ngbaka Minagende](https://glottolog.org/resource/languoid/id/ngba1285) [nga]. This dictionary was scanned, OCR'd, and converted to a database for Danis 2017 and Danis 2019. Dana Matarlo greatly assisted with the OCR process, and Paul de Lacy assisted with converting the OCR text to a structured database. For a full discussion on this particular subset of words (i.e. a CVCV shape), see the discussion in Danis 2019. 

## References

* Danis, Nick. 2019. [Long-distance major place harmony](https://www.cambridge.org/core/journals/phonology/article/abs/longdistance-major-place-harmony/7620003BF480A83F2C0A3B604989B62F). *Phonology* 36.4. 573-604.  [[doi](https://doi.org/10.1017/S0952675719000307), [lingbuzz](https://ling.auf.net/lingbuzz/004988), [ROA-1365](http://roa.rutgers.edu/content/article/files/1804_danis_1.pdf)]

* Maes, Védaste. 1959. [*Dictionnaire ngbaka-français-néerlandais; préc. d'un aperçu grammatical*](https://www.worldcat.org/title/dictionnaire-ngbaka-francais-neerlandais-prec-dun-apercu-grammatical/oclc/251249793). Tervuren Commission de Linguistique Africaine.