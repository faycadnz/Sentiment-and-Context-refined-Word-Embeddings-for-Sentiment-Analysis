# Sentiment and Context-refined Word Embeddings for Sentiment Analysis

In this project, we present a model that effectively combines context and sentiment information when building a text representation in order to address the shortcomings of existing word embeddings for sentiment analysis tasks. The proposed model refines word vectors with immediate context information without relying on any specific domain and can be employed with any pre-trained word embedding models. It further integrates sentiment scores obtained using a lexicon-based method when building the final word vectors of sentences to be classified. The model achieves significantly higher sentiment classification accuracy than baseline word embeddings models commonly used in sentiment analysis.

The Jupyter Notebook file in this repository consists of experiments applied on the well-known [Movie Reviews](https://www.cs.cornell.edu/people/pabo/movie-review-data/) dataset:

**Plain:** Classification on the preprocessed data.

**Context-refined:** Classification with context-refined word embeddings.

**Sentiment & context-refined:** Classification with context-refined word embeddings integrated with sentiment data.


## Citation

If you find this repository useful in your research, please cite the following [paper](https://ieeexplore.ieee.org/abstract/document/9659189):


**APA format:**

> Deniz, A., Angin, M., & Angin, P. (2021, October). Sentiment and Context-refined Word Embeddings for Sentiment Analysis. In 2021 IEEE International Conference on Systems, Man, and Cybernetics (SMC) (pp. 927-932). IEEE.


**Bibtex format:**

```
@inproceedings{deniz2021sentiment,
  title={Sentiment and Context-refined Word Embeddings for Sentiment Analysis},
  author={Deniz, Ay{\c{c}}a and Angin, Merih and Angin, Pelin},
  booktitle={2021 IEEE International Conference on Systems, Man, and Cybernetics (SMC)},
  pages={927--932},
  year={2021},
  organization={IEEE}
}
```
