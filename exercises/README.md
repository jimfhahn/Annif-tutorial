# Annif tutorial outline

## 1. Introduction and overview

[![Video](/img/intro-slides-1.png)](https://www.youtube.com/watch?v=C4t1tnWslWA&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=1)

- [slides](/presentations/intro-slides.pdf)
- [transcript of video](/transcripts/intro.md)

The exercises drawn with thick borders and a blue background are **core**, the
others are optional extras.

![overview](overview.png)

## 2. Installation

Select your installation type. If you don’t know what to choose, we suggest using VirtualBox.
- [exercise](/exercises/01_install_annif.md)

### 2.1. VirtualBox install

[![Video](/img/annif-install-virtualbox-slides-1.png)](https://www.youtube.com/watch?v=l1rtJ6AO0P0&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=2)

- [slides](/presentations/annif-install-virtualbox-slides.pdf)
- [transcript of video](/transcripts/annif-install-virtualbox.md)
- [VirtualBox image download (~2GB)](https://annif.org/download/)

### 2.2. Docker install

[![Video](/img/annif-install-docker-slides-1.png)](https://www.youtube.com/watch?v=j_VeC_NeVcw&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=3)

- [slides](/presentations/annif-install-docker-slides.pdf)
- [transcript of video](/transcripts/annif-install-docker.md)

### 2.3. Linux native install

[![Video](/img/annif-install-linux-slides-1.png)](https://www.youtube.com/watch?v=5a7CJ7JF_Qk&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=4)

- [slides](/presentations/annif-install-linux-slides.pdf)
- [transcript of video](/transcripts/annif-install-linux.md)
- [Annif README file with installation instructions](https://github.com/NatLibFi/Annif/blob/master/README.md)

## 3. Data sets
This tutorial provides two example data sets; one of them should be chosen to be used in the exercises.

[![Video](/img/data-sets-slides-1.png)](https://www.youtube.com/watch?v=S4E3d3o5HWg&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=5)

- [slides](/presentations/data-sets-slides.pdf)
- [transcript of video](/transcripts/data-sets.md)

## 4. TFIDF project
The basic functionality of Annif is introduced by setting up and training a project using a TFIDF model.

[![Video](/img/tfidf-project-slides-1.png)](https://www.youtube.com/watch?v=FOdB3tJNSRM&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=6)

- [slides](/presentations/tfidf-project-slides.pdf)
- [transcript of video](/transcripts/tfidf-project.md)
- [exercise](/exercises/02_tfidf_project.md)

## 5. Algorithms
The principles of the algorithm types used by Annif models are presented.

[![Video](/img/algorithms-slides-1.png)](https://www.youtube.com/watch?v=xyobh-T6lNQ&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=7)

- [slides](/presentations/algorithms-slides.pdf)
- [transcript of video](/transcripts/algorithms.md)

#### [Optional]
Slides on associative algorithms for XMTC (by CSC's [@jmakoske](https://github.com/jmakoske) & [@mvsjober](https://github.com/mvsjober)):
- [Extreme multi-label text classification (XMTC)](/exercises/HPD-XMTC-2020-11-13.pdf)
- [Tree-based methods for XMTC](/exercises/HPD-TBM-2020-11-13.pdf)
- [Neural networks for XMTC](/exercises/HPD-NN-2020-11-13.pdf)


## 6. Web UI
The web user interface of Annif allows quick testing of projects.

[![Video](/img/web-ui-slides-1.png)](https://www.youtube.com/watch?v=unid4yNtMR0&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=8)

- [slides](/presentations/web-ui-slides.pdf)
- [transcript of video](/transcripts/web-ui.md)
- [exercise](/exercises/03_web_ui.md)

## 7. [Optional] REST API
The REST API of Annif can be used for integrating Annif with other systems.
- [exercise](/exercises/07_rest_api.md)


## 8. Metrics & evaluation
Quantitative testing and comparison of projects against standard metrics can be done using the `eval` command.

[![Video](/img/metrics-and-evaluation-slides-1.png)](https://www.youtube.com/watch?v=OhiAZ64dCUQ&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=9)

- [slides](/presentations/metrics-and-evaluation-slides.pdf)
- [transcript of video](/transcripts/metrics-and-evaluation.md)
- [exercise](/exercises/04_evaluate.md)

## 9. [Optional] Omikuji project
Omikuji is a tree-based associative machine learning model that often produces very good results, but requires more resources than the TFIDF model.
- [exercise](/exercises/08_omikuji_project.md)

## 10. Installing Maui Server
The usage of Maui projects is a bit different to other project types, because it relies on a separate service, Maui Server. If you are using the VirtualBox image, Maui Server is already installed and running, and you can continue straight away to the Maui project exercise. If you have installed Annif using Docker or as a Linux local installation, Maui Server needs to be installed separately.

### 10.1. Docker

[![Video](/img/mauiserver-install-docker-slides-1.png)](https://www.youtube.com/watch?v=F4ALM6m5_t0&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=10)

- [slides](/presentations/mauiserver-install-docker-slides.pdf)
- [transcript of video](/transcripts/mauiserver-install-docker.md)

### 10.2. Linux local install

[![Video](/img/mauiserver-install-linux-slides-1.png)](https://www.youtube.com/watch?v=cac2ULKALNA&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=11)

- [slides](/presentations/mauiserver-install-linux-slides.pdf)
- [transcript of video](/transcripts/mauiserver-install-linux.md)

## 11. Maui project
Maui is a lexical algorithm for matching terms in document text to terms in a controlled vocabulary.

[![Video](/img/maui-project-slides-1.png)](https://www.youtube.com/watch?v=YHZ9vIAN5uQ&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=12)

- [slides](/presentations/maui-project-slides.pdf)
- [transcript of video](/transcripts/maui-project.md)
- [exercise](/exercises/05_maui_project.md)

## 12. [Optional] Hogwarts Sorting Hat using fastText
Yet another algorithm you can try is fastText, which can also work on the level of individual characters.
- [exercise](/exercises/09_hogwarts.md)

## 13. Ensemble project
An ensemble project combines results from the projects set up in previous exercises.

[![Video](/img/ensemble-project-slides-1.png)](https://www.youtube.com/watch?v=v7vyU0jjOyg&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=13)

- [slides](/presentations/ensemble-project-slides.pdf)
- [transcript of video](/transcripts/ensemble-project.md)
- [exercise](/exercises/06_ensemble_project.md)

## 14. [Optional] Neural network ensemble project
A neural network ensemble can be trained to intelligently combine the results from the base projects.

- [exercise](/exercises/10_nn_ensemble_project.md)

## 15. [Optional] Incremental learning
The neural network ensemble is also capable to online incremental learning, i.e. the training can be continued while the model is in use.

- [exercise](/exercises/11_incremental_learning.md)

## 16. Closing
Summary of the material in the tutorial and some pointers to further information.

[![Video](/img/closing-slides-1.png)](https://www.youtube.com/watch?v=gIZLWqVaXAA&list=PLa9kvrI3VLf5K-bjvVDaIWMi5CACGjPUM&index=14)

- [slides](/presentations/closing-slides.pdf)
- [transcript of video](/transcripts/closing.md)
- [feedback](https://forms.gle/hrY4oxfg9MB6YiEc7)
