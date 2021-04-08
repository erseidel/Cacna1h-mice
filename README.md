# Cacna1h-miceBP analysis and visualization

To perform this analysis, ensure R is installed alongside packages ggplot2, lme4, lmtest, orddom, cowplot, zoo, scales, reshape2, vegan and pwr. Then run from command-line in same folder as scripts and accompanying input data as:

    Rscript testBP_mice_CACNA1H_20210320.r > output_file

which will pipe statistical test outputs to "output_file" and plot the blood pressure curves to a PDF file in the same folder.
