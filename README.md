# BIMM143-Project-2-Final-
This is my Project 2 for BIMM 143 using four different bioinformatic methods. My four bioinformatic methods are pairwise sequence alignment, homology modeling, heatmap, and phylogenetic tree

In this repository you will need to download the html/rmd file and all of the files listed to run the code. Explanation of the code is done below in the Explanation of files section.

Scientific Question Are there differences in the amino acid sequence of alliin lyase and lectin in Allium cepa (onion) and Allium sativum (garlic) that make the smell and flavor of these two vegetables unique?

Scientific Hypothesis If the difference in flavor and smell profiles of Allium cepa and Allium sativum is caused by differences in the amino acid sequence of the plant’s defensive proteins against herbivores, then there will be observable differences in the amino acid sequence of key defensive proteins such as alliin lyase (alliinase) and lectin.

Explanation of Files!

1KJ1 - This is a png file that is a picture of the protein structure of lectin from Allium sativum (garlic) created from the website SWISS-MODEL.

1lk9.1 - This is a png file that is a picture of the protein structure of alliinase lyase (alliinase) from Allium sativum (garlic) created from the website SWISS-MODEL

Alliin Lyase 2.0 - This is a text file created to run the phylogenetic tree code. The data is collected from the ncbi website https://www.ncbi.nlm.nih.gov/' For the files I searched Alliin Lyase Allium and then went to proteins Then downloaded the fasta files for Allium.cepa, Allium.fistulosum, Allium.ascalonicum, Allium.ampeloprasum, Allium.sativum, Allium.chinense, and Allium.tuberosum and put them into one file which I called Alliin Lyase 2.0

Alliin_aligned.fasta - This fasta file was created through the R code writeXStringSet(aligned, file = "Alliin_aligned.fasta") If you download this file then you do not need this line of code

Allium_Cepa_Alliin_Lyase.fasta - This fasta file is necessary to run the pairwise sequence alignment code. The fasta file was downloaded from https://rest.uniprot.org/uniprotkb/P31757.fasta

Allium_Cepa_Lectin.fasta - This fasta file is necessary to run the pairwise sequence alignment code. The fasta file was downloaded from https://rest.uniprot.org/uniprotkb/C0HJM8.fasta

Allium_Sativum_Alliin_Lyase 1.fasta - This fasta file is necessary to run the pairwise sequence alignment code. The fasta file was downloaded from https://rest.uniprot.org/uniprotkb/Q01594.fasta

Allium_Sativum_Alliin_Lyase 2.fasta - This fasta file is necessary to run the pairwise sequence alignment code. The fasta file was downloaded from https://rest.uniprot.org/uniprotkb/Q41233.fasta

Allium_Sativum_Lectin.fasta - This fasta file is necessary to run the pairwise sequence alignment code. The fasta file was downloaded from https://rest.uniprot.org/uniprotkb/P83886.fasta

Lectin - This is a text file created to run the phylogenetic tree bioinformatic method. The data is collected from the ncbi website https://www.ncbi.nlm.nih.gov/' For the files I searched Lectin Allium and then went to proteins Then downloaded the fasta files for Allium.cepa, Allium.fistulosum, Allium.ascalonicum, Allium.ampeloprasum, Allium.sativum, Allium.chinense, and Allium.tuberosum and put them into one file which I called Lectin

Lectin_aligned.fasta - This fasta file was created through the R code writeXStringSet(aligned, file = "Lectin_aligned.fasta") If you download this file then you do not need this line of code

Model 1 from 1lk9 - This is a png file of the protein model created when using the protein structure template 1lk9 which is the structure of Allium sativum’s alliinase protein to create the theoretical protein structure model of Allium cepa’s alliinase protein using homology model from the website SWISS-MODEL

Model 2 from 1KJ1 - This is a png file of the protein model created when using the protein structure template 1KJ1 which is the structure of Allium sativum’s lectin protein to create the theoretical protein structure model of Allium cepa’s lectin protein using homology model from the website SWISS-MODEL

Quality of Model 1 - This is a png file of the quality of the homology modeling of Model 1 taken from the SWISS-MODEL structure analysis

Quality of Model 2 - This is a png file of the quality of the homology modeling of Model 2 taken from the SWISS-MODEL structure analysis

Ramachandran of Model 1 - This is a png file of the Ramachandran photo of Model 1 taken from the SWISS-MODEL structure analysis

Ramachandran of Model 2 - This is a png file of the Ramachandran photo of Model 2 taken from the SWISS-MODEL structure analysis
