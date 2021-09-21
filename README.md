# Slowed canonical progress in large fields of science

This repository contains data associated with "Slowed Canonical Progress in Large Fields of Science." forthcoming in the *Proceedings of the National Academy of Sciences*. <Add link when available>

If you use ideas, data, or code presented here, please cite our paper:

Chu, Johan S. G., & James A. Evans. 2021. Slowed canonical progress in large fields of science. *Proceedings of the National Academy of Sciences*. <Cite to be added when available>

More information and figures will be added here after publication.

## Data

[Subject-year level data for producing Figs. 1 and 3](./subjectYrData.csv). The columns in the dataset are:

- subjectID - Web of Science subject ID
- yr - publication year
- lnPubs - base 10 logged number of publications in subjectID-yr
- gini - Gini coefficient of citation share inequality
- rnkCor - Spearman rank correlation of top 50 most-cited articles from current year to next
- p01Pct - Proportion of papers ever reaching the top 0.1% most-cited in subsequent years
- mdn01 - Median time in years to top 0.1% most-cited

The raw Web of Science data are available from [Clarivate Analytics](https://clarivate.com/webofsciencegroup/solutions/web-of-science/). These data were processed to create the subject-year level data linked above, as well as the by-percentile citation decay data for Fig. 2 in the paper.

To create Fig. 4, we used disruption scores previously calculated by [Lingfei Wu et al.](https://www.nature.com/articles/s41586-019-0941-9.epdf) They have made replication data for their paper available [here](https://doi.org/10.7910/DVN/JPWNNK).  
