Speculative Fiction in HathiTrust
=================================
This repository will be a growing resource for speculative fiction (SF) works
in the [HathiTrust Digital Library](https://www.hathitrust.org).

Data Files
---------
In the near future it will contain:
1. A list of English-language SF volumes in HathiTrust. It will focus
on works published from 1900&ndash;2010.
2. A reduced list of HathiTrust volumes that correspond to English-language SF anthologies.

Further in the future, we hope to add a list of non-English SF volumes in HathiTrust.

Metadata Fields
---------------
Each list will be represented as a `.tsv` that includes the following fields:
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

