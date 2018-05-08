# QIIME_analysis

This repository contains all the scripts used in the QIIME analysis of the soil samples. They were separated in different folders based on their purpose.
Preliminary analysis: the Joining ends script to join reads is in the main repository page. Demultiplexing scripts are in the demultiplexing folder.
OTU picking: Silva was used to pick OTUs, both closed and open reference, as can be found in the OTU folder.
Diveristy analysis contains scripts for alpha-diversity and rarefaction using Chao1, observed OTUs, PD, Simpson's Index, beta-diversity using weighted and unweighted UniFrac, core microbiome, core diveristy, group-significance using Kruskal-Wallis, summarise taxa and compare summaries with Pearson correlation, compare categories with adonis test, used on open reference silva OTUs only. 

Scripts say what they do in the title (for example, OTUs_24_default means closed reference OTU picking using 24 cores and the default database, and Open_OTUs_24_Silva means open OTU picking using 24 cores and the Silva database).
The scripts with a Q in front of their name used files that were quality filtered.
