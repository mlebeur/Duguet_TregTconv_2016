%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%  Comparison of mouse regulatory T-cells and conventional T-cells %%%%%%%%
%%%%%%                    using a Proteomic approach                    %%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


Data from Fanny Duguet.


CONCEPT OF THE STUDY:

We analysed the proteomes of mouse Foxp3+ Tregs (that include both CD25+ and CD25- Tregs) and of Foxp3- naïve T cells, refered to as regulatory T-cells (Treg) and conventional T-cells (Tconv), respectively.

ORGANISATION OF THE REPOSITORY:

- "/Figures" contains the figures for the paper.
- "/Raw/Duguet" contains the raw files from our MS study.
- "/Raw/ExpressionData" contains data from the paper "Foxp3 Transcription-Factor-Dependent and -Independent Regulation of the Regulatory T Cell Transcriptional Signature" from: Jonathan A. Hill, Markus Feuerer, Kaley Tash, Sokol Haxhinasto, Jasmine Perez, Rachel Melamed, Diane Mathis, and Christophe Benoist, DOI 10.1016/j.immuni.2007.09.010. It also contains the R scripts used for mapping probes to gene names.
- "/Raw/ProteomicsData" contains data from the paper "Transcription Factor 7 Limits Regulatory T Cell Generation in the Thymus" from:  Melanie M. Barra, David M. Richards, Jenny Hansson, Ann-Cathrin Hofer, Michael Delacher, Jan Hettinger, Jeroen Krijgsveld and Markus Feuerer J Immunol published online 31 August 2015. It also contains the tables I used for mapping protein identifiers to our data set.
- "/MappingTables" contains tables with protein informations from the literature used for colouring figures, and the table with the mapping between raw file names and biological replicates.
- "OutputTables" contains the result tables from the analysis.

The files are the following:
- "DuguetAnalysis.Rmd" and the corresponding html contain the scrips of the analysis of our data set.
- "DuguetAnalysisOtherDS.Rmd" and the corresponding html contain the scripts of the analysis of Duguet's data set together with a proteomic and a transcriptomic data set (both already published, see html for references).

I performed again the analysis with only the proteins identified by a minimum of 2 unique peptides. The corresponding files are named "..2PepOrMore" and resulting tables and figures are in the folders "..2PepOrMore".