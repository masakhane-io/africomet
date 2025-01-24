# AfriCOMET

### We have released the following AfriCOMET models to HuggingFace

- AfriCOMET-STL-1.0 https://huggingface.co/masakhane/africomet-stl

- AfriCOMET-MTL-1.0 https://huggingface.co/masakhane/africomet-mtl

- AfriCOMET-QE-STL-1.0 https://huggingface.co/masakhane/africomet-qe-stl

- AfriCOMET-STL-1.1 https://huggingface.co/masakhane/africomet-stl-1.1

- AfriCOMET-QE-STL-1.1 https://huggingface.co/masakhane/africomet-qe-stl-1.1

# African Challenge Set - WMT 2024 Metrics Shared Tasks

## Overview

The AfriMTE-ade-devtest-v2 dataset is a challenge set designed for evaluating machine translation quality across 13 African-centric language pairs. This dataset was used in the WMT 2024 Metrics Shared Task to support research and development in African machine translation evaluation and quality estimation.

## Language Pairs

The dataset includes translations between the following language pairs:

- Darija-French (ary-fra)
- English-Egyptian Arabic (eng-arz)
- English-French (eng-fra)
- English-Hausa (eng-hau)
- English-Igbo (eng-ibo)
- English-Kikuyu (eng-kik)
- English-Luo (eng-luo)
- English-Somali (eng-som)
- English-Swahili (eng-swh)
- English-Twi (eng-twi)
- English-isiXhosa (eng-xho)
- English-Yoruba (eng-yor)
- Yoruba-English (yor-eng)

## Dataset Structure

The dataset contains four types of files for each language pair:

1. **Source Files**
   - Filename pattern: `AfriMTE-ade-devtest-v2.*.src.txt`
   - Contains source sentences

2. **Machine Translation Output Files**
   - Filename pattern: `AfriMTE-ade-devtest-v2.*.hyp-1.txt`
   - Contains machine-translated sentences

3. **Reference Translation Files**
   - Filename pattern: `AfriMTE-ade-devtest-v2.*.ref.txt`
   - Contains ground-truth reference translations

4. **Score Files**
   - Filename pattern: `AfriMTE-ade-devtest-v2.*.score.txt`
   - Contains human quality scores for machine translations

## Contact
- Jiayi Wang (jiaywang@cs.ucl.ac.uk)
- David Adelani (david.adelani@mila.quebec)

## Citations

If you use this dataset in your research or projects, please cite the following papers:

```bibtex
Copy@inproceedings{wang-etal-2024-afrimte,
    title = "{A}fri{MTE} and {A}fri{COMET}: Enhancing {COMET} to Embrace Under-resourced {A}frican Languages",
    author = "Wang, Jiayi and Adelani, David and Agrawal, Sweta and Masiak, Marek and Rei, Ricardo and Briakou, Eleftheria and Carpuat, Marine and He, Xuanli and others",
    booktitle = "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)",
    month = "jun",
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.naacl-long.334/",
    doi = "10.18653/v1/2024.naacl-long.334",
    pages = "5997--6023"
}

@inproceedings{wang2024evaluating,
  title={Evaluating WMT 2024 Metrics Shared Task Submissions on AfriMTE (the African Challenge Set)},
  author={Wang, Jiayi and Adelani, David Ifeoluwa and Stenetorp, Pontus},
  booktitle={Proceedings of the Ninth Conference on Machine Translation},
  pages={505--516},
  year={2024}
}

@inproceedings{freitag2024llms,
  title={Are LLMs breaking MT metrics? results of the WMT24 metrics shared task},
  author={Freitag, Markus and Mathur, Nitika and Deutsch, Daniel and Lo, Chi-Kiu and Avramidis, Eleftherios and Rei, Ricardo and Thompson, Brian and Blain, Frederic and Kocmi, Tom and Wang, Jiayi and others},
  booktitle={Proceedings of the Ninth Conference on Machine Translation},
  pages={47--81},
  year={2024}
}
