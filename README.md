## Description

A repository dedicated to hosting expert-curated, normalized, and enriched datasets of the Apostolos/Apostolikon of Marcion of Sinope.

## Licenses & Terms of Re-Use

See the [Licenses](https://github.com/nauarchus/Marcion_Apostolos/blob/main/LICENSE.md) page in this repo for detailed information about dataset licenses and terms of reuse.

## File Types and Encodings

Each dataset typically has four manifestations:
* .txt file with human-readable Greek and each verse having its own row
* .txt file with words lemmatized and morphologically tagged following the BibleWorks Greek Morphology schema
* .xml file formatted according to the conventions of the Perseus Digital Library and/or Patristic Text Archive
* .csv "sprout" file that combines the three types of data above, assigning tokens to punctuation for sentence segmentation

All datasets use UTF-8 encoding and decomposed Unicode characters. When comparing these datasets with datasets that use composed unicode characters, it may be necessary to convert between composed and decomposed characters for best results.

## File Names and CTS_URN Conventions

The files in this repository all adopt the cts_urn author identifer prefix for Marcion of Sinope (tlg2958) and effectively mint new cts_urn document id for the Apostolos of Marcion (tlg003). The number after "grc" corresponds to its edition, following the historical order of the respective publications.

## Bibliography

If you make use of any of this data in publications, code, or other projects, please cite as follows.

> Bilby, Mark G., Jack Bull, and K. Lance Lotharp. "Normalized Datasets of Zahn’s, van Manen’s, and Harnack’s Greek Reconstructions of Marcion's Apostolos." *Journal of Open Humanities Data* 9.27 (2023): 1–5. [doi:10.5334/johd.122](https://doi.org/10.5334/johd.122)

> BeDuhn, Jason D., and Mark G. Bilby. "Normalized Datasets of BeDuhn's Apostolikon." (forthcoming)

> Vinzent, Markus, Mark G. Bilby, Jack Bull, and K. Lance Lotharp. Die älteste Sammlung der paulinischen Briefe und die Entstehung der kanonischen Paulusbriefsammlung. 4 vol. Tübingen: Narr Francke, 2025.
