---
layout: default
---

[metaGOflow](https://github.com/emo-bon/MetaGOflow) is a pipeline based on [MGnify](https://www.ebi.ac.uk/metagenomics/) and its [workflows](github.com/ebI-Metagenomics/pipeline-v5), 
aiming to address the challenges of the analysis of the European Marine Omics Biodiversity Observation Network (EMO BON) data. 
[EMO BON](https://www.embrc.eu/emo-bon) is a long-term omics observatory of marine biodiversity that generates hundreds of metagenomic samples periodically from a range of stations around Europe.


In the following diagram is an overview of the metaGOflow steps:

![wf](https://raw.githubusercontent.com/hariszaf/metaGOflow-use-case/gh-pages/assets/img/eosc-life-marine-gos-wf.png)


<!-- As long as our sequences seem good enough, we can investigate the taxonomic inventories returned, based on the SSU and the LSU rRNA genes.  -->

Here we show visual components accompanying the [metaGOflow publication](). 
Along with the EMO BON samples included in this use case, a TARA OCEAN sample of size similar to the EMO BON data was analysed. 
<!-- We performed all steps of metaGOflow for a marine sediment (ERR) and a water column (ERR) sample.  -->
A quality control report, the taxonomic inventories as well as some of the functional annotations returned in each case are displayed here.
metaGOflow also returned the assemblies of the samples. 
You can find all the input-output files along with the RO-crates produced by metaGOflow for those 2 samples under this [Zenodo repository]().
<!-- remember to update when zenodo ready -->


* [Here](./marine-sediment.html) are parts of the metaGOflow data products for the EMO BON **marine sediment**. 

* [Here](./water-column.html) are again parts of the metaGOflow data products for the EMO BON **water column** sample.

* Last, [here](./tara_ocean.md) is an overview on the metaGOflow data products when using the TARA OCEANS sample


<!-- > The complete data products of the last 2 cases will be displayed as such by the time the embargo of the raw data is over (September 2023). -->

<br>


**metaGOflow source code:**
[GitHub repo](https://github.com/emo-bon/MetaGOflow)


**Citation**

In case you are using metaGOflow for your analysis, please remember to cite us: 


**Contact** 

[help@embrc.org](mailto:help@embrc.org)

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)


