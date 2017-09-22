# A smart format, named KSN.1
Prabhat Kumar¶</br>
Department of Information Science, Sequomics, Inc.</br>
¶ To whom correspondence should be addressed.</br></br>
## Abstract
<b>Summary:</b></br>
<b>Availability and Requirements:</b> <b>ASN.1</b> is open source bioinformatics solution, available at — https://github.com/</br>
<b>License:</b> Apache License 2.0</br>
<b>Contact:</b> prabhat.omics@gmail.com</br>
<b>Supplementary Information:</b> Supplementary data are available at <i>Bioinformatics Online</i>.</br>
<b>Issue Section:</b> Storage Format</br>
## ¶ Introduction
## ¶ Historical Perspective
## ¶ Specifications

i) The first line begins with <b>></b>,</br>
ii) and thereafter, for nucleic acid; if DNA - D and if RNA - R and if Protein - P,</br>
iii) and ends with a single semicolon,</br>
iv) The semicolon is followed by a unique code, which is a unique sequence identifier, that is generated for a respective molecule,
v) Now, separate the name of molecular sequence and count of it with, a '|' symbol,</br>
   
   Note:- a newline (by caraige return) is required after that and we can say, first line a syntax identifier.

vi) After above, there is a limit to store the sequence in allowed letter of molecules and length per line is 100,
    and if more than that of storage limit, we can go over the chunks of separate files,</br>
vii) every files have to be ended with a - EOS.</br>

## ¶ Programming and Implementation
### Pseudo Code
## ¶ Acknowledgement
## ¶ Funding
## ¶ References

Pinho, A.; Pratas, D. <i>et al.</i> (2014). "MFCompress: a compression tool for FASTA and multi-FASTA data.". <i>Bioinformatics</i>. <b>30 (1):</b> 117–118.

<i>This is an Open Access article distributed under the terms of the Creative Commons Attribution License (http://creativecommons.org/licenses/by/4.0/), which permits unrestricted reuse, distribution, and reproduction in any medium, provided the original work is properly cited.</i>

### ¶ Supplementary Data
[Supplementary Data](https://github.com/IUPANS/KSN.1/blob/master/Papers/Supplementary.Data.md) - pdf file.
