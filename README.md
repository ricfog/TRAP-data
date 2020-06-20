# TRAP data

This repo contains the data used in the paper "TRAP: A Predictive Framework for Trail Running Assessment of Performance".

If you use the data set for fun or research, please reach out to us and let us know how you are using it! We are always looking for new ideas and research projects. 

## ITRA data

The data contains information on runners' performance for all runners that took part in ITRA races between 2010 and 2018.

```Race_info``` contains data on the races. ```Runners_performance``` contains information on the results of each of the participants. The two files can be joined using the "key" variable.

We scraped the data using the <a href="https://github.com/ricfog/ScrapITRA">scrapITRA</a> Python package.


## UTMB data

The ```raw_utmb``` folder contains the raw data that used to construct the features and outcome.

The ```regression_utmb``` folder contains the data set used in the regressions in the paper (with 2 lags).

If you just want to try the data without bothering about constructing the features, then you should definitely use the data set contained in the second folder. If you would like to see the code, please reach out to us. You can find our emails in the paper below.

# How to cite

If you use the data set in a research paper/article, then you need to cite:

*Fogliato, Riccardo, Natalia L. Oliveira, and Ronald Yurko. "TRAP: A Predictive Framework for Trail Running Assessment of Performance." arXiv preprint arXiv:2002.01328 (2020).* 

Bibtex citation:

```
@article{fogliato2020trap,
  title={TRAP: A Predictive Framework for Trail Running Assessment of Performance},
  author={Fogliato, Riccardo and Oliveira, Natalia L and Yurko, Ronald},
  journal={arXiv preprint arXiv:2002.01328},
  year={2020}
}
```