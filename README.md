# Quantifying Community Characteristics of Maternal Mortality Using Social Media

A set of 50 pregnancy-related topics derived from a 10% Twitter sample from 2009-2015. 

Read the full publication [here](). 

## Topics

Available in both csv format and as a MySQL dump.

### maternal_mortality_topics_cp

* `id`: auto-incremented numeric row id
* `term`: unigram in topic
* `category`: Numeric topic id (from 0 to 49)
* `weight`: Conditional probability of the topic given the unigram, as derived through the LDA process. 

### maternal_mortality_topics_loglik

* `id`: auto-incremented numeric row id 
* `term`: unigram in topic
* `category`: Numeric topic id (from 0 to 49)
* `weight`: Posterior likelihood

## Citation

Please cite the following paper if you use this data. 

```
@inproceedings{AbebeGiorgi2020quantifying,
    title={Quantifying Community Characteristics of Maternal Mortality Using Social Media}, 
    author={Abebe, Rediet and Giorgi, Salvatore and Tedijanto, Anna and Buffone, Anneke and Schwartz, H. Andrew}, 
    booktitle={The World Wide Web Conference},
    year={2020}
}
```

## License

Licensed under a GNU General Public License v3 (GPLv3).

