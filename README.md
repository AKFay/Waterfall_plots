# Waterfall_plots

Making Waterfall Plots with Altair
By Alyson Freeman
For this assignment, I'm going to show you how to make and use waterfall plots using the python library Altair. This is a great way of comparing experimental data across samples; for example, treating a panel of cell lines in the same way and comparing the effect.

The data that I'm going to use is from a screen performed at the Broad Institute. One of the main purposes of the screen was to look across cancer cell lines and identify any new drug targets that could have clinical impact. To do this, they used shRNA directed at a gene to decrease the amount of that gene's corresponding protein in the cell. If a cell line's growth decreased due to having less of a certain protein, that protein could be a good target for a drug. Researchers then took hundreds of cancer cell lines and used shRNA to knockdown hundreds of genes in each cell line. In this way, they could compare the effect of losing expression of each gene across all cell lines. Ideally, a protein would make a good target if it is important not just in one cell line but in a significant patient population.

When working with large datasets in the biological sciences, visualizations are an indespensible way to analyze and communicate results of experiments. The goal of the following demonstration is to show what waterfall plots are, how they can be used, and how to make them.
