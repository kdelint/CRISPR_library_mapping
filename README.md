# CRISPR_library_mapping
Tools and files for mapping sequencing reads to CRISPR libraries

The files TKOv3_guide_sequence_2023 and Brunello_guide_sequence_2023 (both .xlsx and .tsv) are adapted versions of the CRISPR library file from the Addgene [TKOv3](https://www.addgene.org/pooled-library/moffat-crispr-knockout-tkov3/) and [Brunello](https://www.addgene.org/pooled-library/broadgpp-human-knockout-brunello/) sites

 In these versions, 28 gene symbols that were renamed by the [HUGO Gene Nomenclature Committee](https://www.genenames.org/) have been updated. These are:
 
 DEC1 is replaced by DELEC1  
 MARC1 and MARC2 are replaced by MTARC1 and MTARC2  
 MARCH1 to MARCH11 are replaced by MARCHF1 to MARCHF11  
 SEP15 is replaced by SELENOF  
 SEPT1 to SEPT12 and SEPT14 are replaced by SEPTIN1 to SEPTIN 12 and SEPTIN14  
  
 Mapping NGS reads to these updated files will avoid excel automatically converting these gene names to dates. 
 Paper describing the issue: [Mistaken Identifiers: Gene name errors can be introduced inadvertently when using Excel in bioinformatics](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-5-80)
 
 Edit 19jun23: Added [mTKO](https://www.addgene.org/pooled-library/moffat-mouse-knockout-mtko/) and [Brie](https://www.addgene.org/pooled-library/broadgpp-mouse-knockout-brie/) mouse libraries where Marc, March, Sep and Sept genes are renamed
