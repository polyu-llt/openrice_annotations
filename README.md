# Openrice data for sentiment analysis

This repository contains a sentiment lexicon for Cantonese language created on the **openrice** data.   

## Openrice comments
The data were collected from the web site with reviews of food and restaurants in Hong Kong www.openrice.com. It was downloaded using python scrapper (scrapy), with the permission of the portal owner to perform scientific (non-commercial) experiments with the data. The special restriction was made on user-sensitive data, like nickname and amount of money spent. The comments are not released here (!!), only samples, annotations and the resulting sentiment lexicon.

## Sentiment lexicon via crowdsourcing
In order to get the sentiment words to form the lexicon, we asked the students from the linguistic department to annotate the evaluative words alongside with the polarity and the aspect -- a word to which the candidate word/phrase is related. The annotation giudelines are described in a paper.  

The evaluative words were collected based on the annotator agreement rate and cleaned. This was done by Yunfei Long and his team.

## ML
The machine learning experiments on sentiment analysis are described in [this](https://github.com/polyu-llt/openrice_annotations/blob/master/clf_openrice.ipynb) jupyter notebook - by Natalia Klyueva.  

## Credits
This project presents the collaboration of the two departments of PolyU (CBS and COMP), by Natalia Klyueva and Yunfei Long under the supervision of Lu Qin
