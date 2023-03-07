# This repository contains data for helping with sentence alignment and filtering of parallel corpora. The resources focus on the English-Icelandic language pair.

The data is organized in the following way:
- `classification/`: contains data for classifying sentences or sentence pairs
-- `classify-coherent-icelandic.csv`: contains 10,000 Icelandic sentences that are either annotated as acceptable Icelandic sentences or unacceptable. The sentences are sampled from ParaCrawl and WikiMatrix and manually evaluated. The first column indicates the source of the sentence, the second column if it is acceptable (1) or unacceptable (0). The sentence itself is in the last column.
