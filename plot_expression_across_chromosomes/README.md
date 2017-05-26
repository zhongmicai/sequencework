# plot_expression_across_chromosomes.py

> placeholder for now

Plot ratio of expression of experimental condition vs. wild-type (or 
baseline state) for genes in sequential order across chromosomes in the genome. Requires two files: 1. a 
file of a genome annotation format in order to parse the locations of genes 
and (approximate) length of chromosomes; 2. a file of expression data to plot.
The default is that the data is in a tab-delimited format.

There are several optional flags that can be supplied at the time of calling
the script to control options. These are shown if you invoke with `-help` 
flag or simply call the script with no additional arguments. Additionally, 
inside the script there are several `USER ADJUSTABLE VALUES` that can be 
edited for easy customization.
Built to be general enough to be easily modified. For example, should be 
fairly straightforward to change to plotting ratio of sequencing coverage 
across chromosomes in a genome.

The plotting approach and other aspects borrow from Brent Pedersen's awesome
`manhattan-plot.py` script [here](https://github.com/brentp/bio-playground/blob/master/plots/manhattan-plot.py)
This script should produce a plot similar to a combination of Brent Pedersen's
`manhattan-plot`and Figure 5B from Thorburn et al. 2013 (PMID: 23468524), (see [here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3639041/)).

