# nlp-ner-tagging
Implemented a [NER Tagging](https://en.wikipedia.org/wiki/Named-entity_recognition) algorithm with [Hidden Markov Model](https://en.wikipedia.org/wiki/Hidden_Markov_model):

- Implementing Learning (Counting) and Decoding (Viterbi)
- Training the system on Wikipedia ENG and ITA
  - https://github.com/Babelscape/wikineural/tree/master/data/wikineural/en
  - https://github.com/Babelscape/wikineural/tree/master/data/wikineural/it
- Evaluate the system, using different strategies of smoothing for ENG and ITA
- Evaluate against an easy baseline and a difficult one

### Results
96.32% accuracy for IT and 97.44% for ENG.

For more details see the [report](https://github.com/lorenzofavaro/nlp-ner-tagging/blob/main/docs/report.pdf).
