## This repository contains data for helping with sentence alignment and filtering of parallel corpora. The resources focus on the English-Icelandic language pair.

The data is organized in the following way:
- `classification/`: contains data for classifying sentences or sentence pairs
-- `classify-coherent-icelandic.csv`: contains 10,000 Icelandic sentences that are either annotated as acceptable Icelandic sentences or unacceptable. The sentences are sampled from ParaCrawl and WikiMatrix and manually evaluated. The first column indicates the source of the sentence, the second column if it is acceptable (1) or unacceptable (0). The sentence itself is in the last column.


### Not in this repository but available for download via the links, are 16501 EEA documents in [English][eea_16501_en] and [Icelandic][eea_16501_is]. The texts have been split on sentence boundaries and cleaned of HTML tags.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen.)

[eea_16501_en]: <https://www.dropbox.com/s/oolaxzn0588vtld/parice_docs_eea_en.zip?dl=0>
[eea_16501_is]: <https://www.dropbox.com/s/nk1er434a2h6okw/parice_docs_eea_is.zip?dl=0>
