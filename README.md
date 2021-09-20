Speculative Fiction in HathiTrust
=================================
This repository will be a growing resource for speculative fiction (SF) works
in the [HathiTrust Digital Library](https://www.hathitrust.org).

Data Files
---------
### english_volumes.tsv
A list of English-language SF volumes in HathiTrust. It focuses on works published from 1900&ndash;2010.

### english_anthologies.tsv
A (reduced) list of HathiTrust volumes tha correspond to English-language SF anthologies in HathiTrust.

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
