# CompDTURegSampleData

This repo provides sample data quantified by Salmon that contains 100 bootstrap samples for each of 10 replicates within the folder ExampleSalmonQuantifications.  The data come from the Sequencing Quality Control Project (SEQC) from two reference RNA samples, “A” and “B”. Sample A contains five replicates of the Strategene Universal Human Reference RNA (UHRR) and Sample B contains five replicates of the Ambion Human Brain Reference RNA (HBRR).  See SEQC/MAQC-III Consortium (2014), ``A comprehensive assessment of RNA-seq accuracy, reproducibility and information content by the Sequencing Quality Control Consortium,'' Nature Biotechnology, 32, 903 – 917 for more information.

This data is designed to be used with the CompDTUReg package available at https://github.com/skvanburen/CompDTUReg.  

Additionally, gene level files are provided for 10 genes in the folder GeneLevelFiles and in a convenient zipped format in the file "GeneLevelFiles.zip".  These files contain all information necessary to run the CompDTU and CompDTUme methods from the CompDTUReg package.

Sample code is provided within the package repository that shows how to process the raw quantification output (and inferential replicates) from the Salmon output as well as how to run the CompDTU and CompDTUme methods.  See the SampleCode folder within the package repository linked to above.
