# Modality-Corpus
This repository contains the data used to evaluate the event-based modality task proposed by Pyatkin et al. (2021).

We use the Georgetown Gradable Modal Expressions Corpus (GME) as described by [Rubinstein et al. (2013)](https://www.aclweb.org/anthology/W13-0306.pdf). The corpus is available for search through the [ANNIS interface](http://corpling.uis.georgetown.edu/annis/) (please contact Prof. Paul Portner at Paul.Portner@georgetown.edu for access).

The GME Corpus was obtained by expert annotation of the documents included in the MPQA Opinion Corpus ([Wiebe et al., 2005](https://link.springer.com/article/10.1007/s10579-005-7880-9)).
Prior to downloading our data, you are required to first obtain access to the MPQA Corpus at https://mpqa.cs.pitt.edu/corpora/mpqa_corpus/ 

Our experiments used a subset of the GME annotations (specifically: modal triggers, associated propositional spans, and modal senses), pre-processed into the CoNLL-formatted file provided in this repository.


## Terms of Use
- By downloading the data on this page the user acknowledges that they have obtained access to the MPQA Corpus.
- By downloading the data on this page the user acknowledges that their use will be restricted to research and/or academic purposes only.
- Resources on this page are licensed CC-BY 4.0, a Creative Commons license requiring Attribution (https://creativecommons.org/licenses/by/4.0/).

## Citation Information
```
@InProceedings{pyatkin2021modality,
  author    = {Pyatkin, Valentina and Sadde, Shoval and Rubinstein, Aynat and Portner, Paul and Tsarfaty, Reut},
  title     = {The Possible, the Plausible, and the Desirable: Event-Based Modality Detection for Language Processing},
  year      = {2021},
}
```
and 
```
@inproceedings{rubinstein2013toward,
  title={Toward fine-grained annotation of modality in text},
  author={Rubinstein, Aynat and Harner, Hillary and Krawczyk, Elizabeth and Simonson, Dan and Katz, Graham and Portner, Paul},
  booktitle={Proceedings of the IWCS 2013 Workshop on Annotation of Modal Meanings in Natural Language (WAMM)},
  pages={38--46},
  year={2013},
  url={https://www.aclweb.org/anthology/W13-0306}
}
```
