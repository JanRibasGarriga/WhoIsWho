# WhoIsWho: exploiting Google Colab to develop a free and open-source toolbox for deep learning in microscopy

## What is this?

WhoIsWho is a collection of self-explanatory Jupyter Notebooks for [**Google Colab**][1] that features an **easy-to-use graphical user interface**. They are meant to quickly get you started on learning to use deep learning for microscopy. Google Colab itself **provides the computations resources needed at no-cost**. **WhoIsWho** is designed for researchers that have little or no coding expertise to quickly train and test models.

## Want to read the report?

This repository is part of the [**bachelor's thesis**][2] (undergraduate project) conducted by [**Jan Ribas-Garriga**][3] under the frame of Erasmus+ Traineeship in the Toledo Group at the Center for Chromosome Stability from the Department of Cellular and Molecular Medicine from October 2020 to June 2021.

### Abstract

Cell lines have long served as tools for understanding cancer at the molecular level. However, since most studies are carried out using a handful of cell lines, our ability to entirely understand the genetic heterogeneity of cancer might be reaching a plateau. A change of approach must take place in order to routinely carry out studies in a larger number of cancer cell lines, with the goal of finding new medicines and identifying genotype-specific cancer vulnerabilities. Nevertheless, replicating costly mechanistic studies or large screenings in multiple cell lines using classical imaging analysis techniques is currently unaffordable. One straightforward solution would be to pool many cell lines in a co-culture and devise a way to differentiate them from one another. Here we report a novel deep learning-based method that allows identifying cells according to the cell line they belong to in a co-culture using structural information obtained by transmitted light microscopy. This work presents a successful multi-stage pipeline consisting of a (i) segmentation of cell nuclei, (ii) localization of these nuclei by generating a bounding box around them, and (iii) classification of each nucleus. Moreover, we show the best cells' culture conditions for the pipeline's training dataset which boosts its performance yielding up to 78% classification accuracy.

## Want to see a short video demonstration?

| Running a WhoIsWho notebook |
|:-:|
| [![](https://github.com/JanRibasGarriga/WhoIsWho/master/media/Screenshot_VideoDemonstration.jpg)](https://www.youtube.com/watch?v=nmS1tkuuGYM) |

## Who is it for?

Any researcher interested in microscopy, independent of their background training. **WhoIsWho** is designed for anyone with little or no coding expertise to quickly train, test and use popular deep learning tools used to process microscopy data.

  [1]: https://colab.research.google.com/notebooks/intro.ipynb
  [2]: https://upcommons.upc.edu/handle/2117/347783
  [3]: https://www.linkedin.com/in/janribasgarriga/
