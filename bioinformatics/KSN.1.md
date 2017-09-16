# KSN.1
It is a bioinformatics file format, to store the nucleic acids and proteins sequences with their properties.

Now, what's exactly it is?

Specifications:
---------------

i) The first line begins with <b>></b>,

ii) and thereafter, for nucleic acid; if DNA - D and if RNA - R and if Protein - P,

iii) and ends with a single semicolon,

iv) The semicolon is followed by a unique code, which is a unique sequence identifier, that is generated for a respective molecule,

v) Now, separate the name of molecular sequence and count of it with, a '|' symbol,
   
   Note:- a newline (by caraige return) is required after that and we can say, first line a syntax identifier.

vi) After above, there is a limit to store the sequence in allowed letter of molecules and length per line is 100,
    and if more than that of storage limit, we can go over the chunks of separate files,

vii) every files have to be ended with a - EOS.

File Format of KSN.1
--------------------
```
>D;P49|Gene p49|
ATGCTCTGCATGCATGCATGCAGTCAGT
TGCAGTGCATGCAGTGTCAGTGCATGCA
[P49]
```
