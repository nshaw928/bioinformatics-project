# rnaseq-breastcancer-classification

## About
In this project I use RNA-seq data from TCGA to classify subtypes of breast cancer based on the expression profiles of each subtype.

## Notebooks
00) Test imports
01) Data collection and cleaning
02) Exploration of the data through various clustering techniques
03) Exploration of DEGs using DeSeq2, volcano plots, and heatmaps
04) Feature selction and classification of subtypes
05) Explanation of random forest model using SHAP values to understand gene relevance and influence on the classifier, signaling potential biological relevance

## Project Status
This project is still under construction. I am actively working on polishing this project and expanding on the analysis.
### Complete, not polished
Notebooks 00 - 04 are completed and functional
### Incomplete
Notebook 05 - structure outlined and most code done, but missing per class charts in several places
### Improvements
The following are things I would like to improve:
- create data loading function in source that's common accross notebooks (instead of copy/pasting cells)

"#todo" in files represents opportunities for improvement or additions that could be added later. (though these show up as h1s in the markdown render)
