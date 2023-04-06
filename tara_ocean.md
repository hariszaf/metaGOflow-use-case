---
layout: default
---

## TARA OCEANS sample 


Sample's accession id:


### Quality control

metaGOflow invokes [fastp](https://github.com/OpenGene/fastp) that automatically returns a `.html` report like the one below for the case of this water column sample: 

<!-- <iframe src="https://rawcdn.githack.com/hariszaf/metaGOflow-use-case/" style="width:200%; height:900px;" ></iframe> -->


### Taxonomic inventory


metaGOflow uses the [mapSEQ](https://github.com/jfmrod/mapseq) to extract taxa present on the community based on the ribosomal RNA sequences.

Here is the krona plot metaGOflow returns as a visual component of the community structure.

<!-- <iframe src="https://rawcdn.githack.com/hariszaf/metaGOflow-use-case/" style="width:200%; height:900px;" ></iframe> -->


### Functional annotation 

metaGOflow supports a functional annotation step that uses the filtered reads and a series of tools and databases to return several types of annotations. 

#### InterProScan (IPS)
 
On the first column we get the number of hits an id had among the reads, on the second the IPS id and on the third its description.

<div style="width:200%; height:900px; overflow: auto">
  <table>
    <tr>
    </tr>
  </table>
</div>

<br>


#### GO-slim 

GO slim is a cut-down version of the GO ontologies that contain only a subset of terms from the GO resource. metaGOflow provides both a full GO annotation which is not displayed here as it is rather long and a slim version like the one shown here for the water column case.
On the first column there is the GO id, 
on the second its description, 
on the third its the GO ontology it belogs to (biological process, cellular component, molecular function) and on the fourth one
we have the number of hits of the annotation on the reads.

<div style="width:200%; height:900px; overflow: auto">
  <table>
    <tr>
    </tr>
  </table>
</div>

<br>


#### KEGG terms (KOs)

Similar to the IPS case, on the first column we get the number of hits an id had among the reads, on the second the KO and on the third its description.


<div style="width:200%; height:900px; overflow: auto">
  <table>
    <tr>
    </tr>
  </table>
</div>

<br>

#### Pfam 

Like in the IPS and the KEGG cases.

[back](./)


