# hazard_susceptibility_lit_review
Literature review of hazard susceptibility mapping with Machine Learning (ML) and Deep Learning (DL).

There are two folders:

## 1. all_selected
This folder contains four (4) files which correspond to the results of the searches in Scopus and Web of Science after the removal of duplicates. There is an 'include' column where it is possible to visualise the articles which have been considered in this review and which have not.

## 2. subselected_articles
This folder includes eight (8) files. Four (4) files, one per hazard, which correspond to the manually selected articles, with columns title, abstract, keywords, affiliation, no. citations, include, ML/DL techniques, and so on. The other four (4) files correspond to the legend of the 'ML/DL techniques' column per each hazard. The legend files have the columns tag (abbreviation), full name, and category (class).

There are three Jupyter notebooks in this repository:

## 1. General_plots
This notebook includes the word cloud plots of the articles' keywords per hazard + a line chart of counts of articles per hazard and year.

## 2. Plot_countries
This notebook includes the country plots of the articles per hazard.

## 3. Statistics_script
This notebook includes the counts of ML/DL techniques per hazard and their corresponding stacked plot which is grouped per technique class according to the ad-hoc classification of techniques defined in the review.
