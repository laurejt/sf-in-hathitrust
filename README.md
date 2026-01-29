Speculative Fiction in HathiTrust
=================================
This repository is a growing resource for speculative fiction (SF) works
in the [HathiTrust Digital Library](https://www.hathitrust.org).

It is a continuation of the resource collected in the [HTRC ACS 2019 project](https://wiki.htrc.illinois.edu/display/COM/Advanced+Collaborative+Support+%28ACS%29+Awards#2019) "Building Large-Scale Collections of Genre Fiction" by Laure Thompson and David Mimno.
For more details, see the [Final Project Report](https://wiki.htrc.illinois.edu/download/attachments/31588360/HTRC%20ACS%20Final%20Reportv2.pdf?version=1&modificationDate=1605782898000&api=v2), as well as the [ACH 2021 presentation slides](https://laurejt.github.io/slides/2021-07-ACH.pdf) for "Finding Speculative Fiction in HathiTrust" by Laure Thompson and David Mimno.

If you have any questions, you can contact Laure Thompson at laurejt@princeton.edu

Data Files
---------
### english_volumes.tsv
A list of English-language SF volumes in HathiTrust. It focuses on works published from 1900&ndash;2010.

### english_anthologies.tsv
A list of HathiTrust volumes that correspond to English-language SF anthologies in HathiTrust.
This is a reduced list (i.e. subset of volumes) of `english_volumes.tsv`.

### Coming soon
Further in the future, we hope to add a list of non-English SF volumes in HathiTrust.

Metadata Fields
---------------
Each list is represented as a `.tsv` that includes the following fields:
- `htid`: HathiTrust volume identifier
- `HTRecord`: The volume's corresponding HathiTrust catalogue record ID. We can view
this record at `https://catalog.hathitrust.org/Record/[HTRecord]`
- WWEnd ID: The [Worlds Without End](https://worldswithoutend.com) novel ID for
this work. We can view this record at
`https://worldswithoutend.com/novel.asp?id=[WWEnd ID]`
- ISFDB ID: The [Internet Speculative Fiction Database](http://isfdb.org)
title ID for this work. We can view this record at
`http://isfdb.org/cgi-bin/title.cgi?[ISFDB ID]`  
- Title: The title of the work
- Author: The author(s) / editor(s) of the work
- Year: The initial publication year of the work

Corpus Statistics
-----------------

| List | # Volumes | # Works | # Authors / Editors |
|:- | -: | -: | -: |
| english_volumes.tsv | 5,811 | 2,235 | 1,201 |
| english_anthologies.tsv | 918 | 669 | 288 |


Acknowledgements
----------------
We would like to thank and acknowledge Michelle Paolillo, Ryan Dubnicek, and Eleanor Dickson Koehl for their contributions to the HTRC ACS project which helped make this resource possible.
