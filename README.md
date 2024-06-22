# Data_Analyzer-ETL_Gene
During my research collaboration at DKFZ, I developed Toolkit (Graphical User Interface (GUI)-ETL) to calculate gene effect score and dependency score based on data provided in DepMap portal database and by Evotech company (Hamburg, Germany).

These measures are important tools in understanding the impact of gene knockout on cell viability and proliferation. 

Gene effect score quantifies the magnitude of the effect that knocking out a gene has on cell viability and proliferation. It is a continuous measure that can range from very small to very large. A higher gene effect score indicates that knocking out the gene has a more profound impact on cell growth. 

Dependency score is a binary measure that indicates whether or not a cell line is dependent on a particular gene. A score of 1 indicates that the cell line is dependent on the gene, while a score of 0 indicates that the cell line is not dependent on the gene. A dependency score of 1 means that knocking out the gene has a significant impact on cell viability and proliferation. 

Tasks performed:
- I compared viability of cells with the knockout gene to viability of control cells. The gene effect score was calculated as the difference in viability between knockout and control cells, normalized by control cell viability. I also checked CRISPR, RNA and protein scores to find the potential cell lines for the further study.
- From the DepMap portal, I was able to identify some of novel ferroptosis regulatory genes that could be useful for the study (had an insight which of the genes are necessary for the interaction and could be potentially be involved in the pathway).
- I was also able to identify some of the potential drug targets based on results above. My hypothesis is genes with a high dependency score may be good targets for new drugs.
