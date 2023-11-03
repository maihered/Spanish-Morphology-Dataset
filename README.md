# Spanish Morphology Dataset
This repository contains a dataset for Spanish Derivational Morphology and the script used to create it.<br>
The dataset can be downloaded from [here](final-dataset.zip); it contains two csv files with instances for prefixes and suffixes with the following structure:<br>

| ID | Derivative      | Base         | Sentence                                                |
|----|-----------------|--------------|---------------------------------------------------------|
| 14 | subcontratación | contratación | No teníamos [MASK] de trabajo para producción de anime. |<br>

The jupyter notebook with the code used to create the dataset is also available online in the following link: https://colab.research.google.com/drive/1Hhvx7SAtLuHxDVi_eDv0GIJ-nj0oIud1?usp=sharing <br>
This notebook expects the necessary data in the Drive directory /Colab Notebooks/spanish-morphology/data , contained in the [data folder](/data) of this repository.<br>

## References to other repositories
The dataset has been built following the English derivation generation dataset by [Hofmann et al.(2020)](https://github.com/valentinhofmann/dagobert).<br>
The Spanish suffixes have been obtained thanks to [MorphyNet](https://github.com/kbatsuren/MorphyNet), which also has datasets for a lot of other languages.<br>
The Wikipedia texts have been processed using the tool [WikiExtractor](https://github.com/attardi/wikiextractor).
