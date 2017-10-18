---
bibliography: bibliography.bib
link-citations: true
csl: apa2.csl
---


#### Current Project

![Diagram from Sampling to Bins](images/20171006-experimental_plan_diagram_noSDP.jpg)

I have been working on binnning genomes from Crystal Bog and Mary Lake over the past year.
One of my current challenges is de-replicating these bins, since we likely have recovered the same genomes from multiple timepoints.  Additionally I am working on methods to classify them, as past methods did not scale up.
I will also bin additional genomes from Trout Bog using new assemblies of the individual time points.
The previously binned genomes from TB were done on a coassembly of all of the timepoints.  
Binning and assembling each sample separately provides several advantages which I hope will help to recover more MAG reference genomes.
One such advantage is the lower strain heterogeneity in individual samples which can interfere with assembly.
Individual assemblies can also better recover genomes from bacteria that were only abundant in one sample but might have been relatively rare in the coassembly which can make assembly difficult.
Additionally I hope to be able to recover more of the flexible genome by assembling the same organism in different timepoints.

*Questions: Are there ecologically distinct strains/genotypes within previously defined sequence-discrete populations?  What stage of speciation are these distinct strains/genotypes at in their separation? Is there a barrier to recombination between such strains?*

@Shapiro2014 proposed 5 stages of microbial speciation under differing recombination/selection regimes.
In past work we looked for evidence of the two major models of bacterial speciation using the MAGs binned from Trout Bog [@Bendall].
We used mapped reads from the metagenomic timeseries back to these MAGs and identified operational taxonomic units(OTUs) by delineating sequence-discrete populations at the percent identity threshold where the coverage dropped off.
While this method revealed a genome-wide sweep and evidence for past gene-specific sweeps, we could not separate the strains within the sequence-discrete populations since we could not link single nucleotide variants(SNVs) together.
New statistical methods have been developed [@Quince2017; @Costea; @Nayfach2016] that use models to find linked SNVs and identify haplotypes.
Using these methods we can identify strains within the sequence discrete populations and look for ecological differentiation and perhaps catching a variety of stages of speciation put forth by [@Shapiro2014].
In capturing many stages of speciation we hope to better understand the principles of diversification and how sequence discrete populations emerge and separate from one another.

Since we have multiple metagenomic timeseries from isolate lakes this also allows for some study of allopatric speciation.


### References