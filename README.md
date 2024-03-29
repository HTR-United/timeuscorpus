<img src="./static/logo-timeus.png" width=150 align=right>

# TIMEUS CORPUS

[![CC BY 4.0][cc-by-shield]][cc-by] [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6230755.svg)](https://doi.org/10.5281/zenodo.6230755)



<!-- updated by workflow -->
![Files Badges](badges/files.svg)  ![Regions Badges](badges/regions.svg)  ![Lines Badges](badges/lines.svg)  ![Chars Badges](badges/characters.svg)

## Description
Ground Truth datasets for French 18th and 19th HTR produced by the [ANR projet TIME US](https://timeus.hypotheses.org/).

## Content

Data are stored in the `data/` folder. Each folder is organized as such:
- all the images are at the root level
- ALTO XML versions are in the `alto/` folder
- PAGE XML versions are in the `page/` folder

| # | name | nb of images | GT for segmenter? | GT for recognizer? | description |
| --- | :---- | :---: | :---: | :---: | :--- |
| 1 | cph_paris_tissage_1858 | (159) | n | y | Registers from the Prud'hommes Court for the Textile Industry in Paris, january to june 1858 |
| 2 | cph_paris_tissage_1878 | (89) | n | y | Registers from the Prud'hommes Court for the Textile Industry in Paris, january 1878 |
<!--|  |  |  |  |  |  |-->

## Annotation system

... <!-- todo -->


## How to cite

This dataset was built within the ANR project TIME US. It is maintained by Alix Chagué (@alix-tz). The original documents are copyright-free, so are the digitization and the transcription. However, digitizing archives and properly annotating a corpus takes time and it is a task that should be recognized. If you use any item from this corpus of ground truth, cite the dataset using the following information:

> Chagué, A., Champougny, K., Meissel, N., Genero, J., Skilbeck-Gaborit, E., Vanneau, L., Bey, L., Le Fourner, V., Albert, A., Riondet, C., & Martini, M. Time Us Corpus [Data set]. https://github.com/HTR-United/timeuscorpus

```
@misc{Chague_Time_Us_Corpus,
author = {Chagué, Alix and Champougny, Kévin and Meissel, Nina and Genero, Jean-Damien and Skilbeck-Gaborit, Eden and Vanneau, Laurie and Bey, Laura and Le Fourner, Victoria and Albert, Anaïs and Riondet, Charles and Martini, Manuela},
title = {{Time Us Corpus}},
url = {https://github.com/HTR-United/timeuscorpus}
}
```


This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
