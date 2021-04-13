# DL-BioNER-survey
List of articles on biomedical named entity identification in recent years.

## Paper Lsit
We collected almost all the paper in recent years for BioNER and divided these approaches into 4 groups based on the number of models and the way they are combined.

### Neural network for BioNER
* Recurrent neural network models for disease name recognition using domain invariant features, ACL 2016, [[paper]](https://www.aclweb.org/anthology/P16-1209.pdf)
* Deep learning with word embeddings improves biomedical named entity recognition, Bioinformatics 2017, [[paper]](https://doi.org/10.1093/bioinformatics/btx228)
* GRAM-CNN: a deep learning approach with local context for named entity recognition in biomedical text, Bioinformatics 2018, [[paper]](https://academic.oup.com/bioinformatics/article/34/9/1547/4764002?login=true) [[code]](https://github.com/valdersoul/GRAM-CNN)
* Putting hands to rest: efficient deep CNN-RNN architecture for chemical named entity recognition with no hand-crafted rules, Cheminformatics 2018, [[paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0280-0)
* A Neural Layered Model for Nested Named Entity Recognition, ACL 2018, [[paper]](https://www.aclweb.org/anthology/N18-1131.pdf), [[code]](https://github.com/meizhiju/layered-bilstm-crf)
* An Effective Transition-based Model for Discontinuous NER, ACL 2020, [[paper]](https://arxiv.org/abs/2004.13454), [[code]](https://github.com/daixiangau/acl2020-transition-discontinuous-ner)
* Combinatorial feature embedding based on CNN and LSTM for biomedical named entity, Biomedical Informatics 2020, [[paper]](https://www.sciencedirect.com/science/article/pii/S1532046420300083)

### Multi-task Learning for BioNER
* Cross-type biomedical named entity recognition with deep multi-task learning, Bioinformatics 2018, [[paper]](https://doi.org/10.1093/bioinformatics/bty869), [[code]](https://github.com/yuzhimanhua/lm-lstm-crf)
* Marginal Likelihood Training of BiLSTM-CRF for Biomedical Named Entity Recognition from Disjoint Label Sets, EMNLP 2018, [[paper]](https://www.aclweb.org/anthology/D18-1306.pdf)
* Recognizing Nested Named Entity in Biomedical Texts: A Neural Network Model with Multi-Task Learning, BIBM 2019, [[paper]](https://ieeexplore.ieee.org/abstract/document/8982966)
* Dataset-aware multi-task learning approaches for biomedical named entity recognition, Bioinformatics 2020, [[paper]](https://academic.oup.com/bioinformatics/article/36/15/4331/5838186)
* DTranNER: biomedical named entity recognition with deep learning-based label-label transition model, BCM Bioinformatics 2020, [[paper]](https://pubmed.ncbi.nlm.nih.gov/32046638/)
* An Empirical Study of Multi-Task Learning on BERT for Biomedical Text Mining, BioNLP 2020, [[paper]](https://arxiv.org/abs/2005.02799)

### Transfer Learning for BioNER
* Label-aware Double Transfer Learning for Cross-Specialty Medical Named Entity Recognition, NAACL 2018, [[paper]](https://arxiv.org/abs/1804.09021), [[code]](https://github.com/felixwzh/La-DTL)
* Transfer learning for biomedical named entity recognition with neural networks, Bioinformatics 2018, [[paper]](https://doi.org/10.1093/bioinformatics/bty449)
* LSTMVoter: chemical named entity recognition using a conglomerate of sequence labeling tools, Cheminformatics 2019, [[paper]](https://www.researchgate.net/profile/Alexander-Mehler-2/publication/330291633_LSTMVoter_Chemical_named_entity_recognition_using_a_conglomerate_of_sequence_labeling_tools/links/5c487cd192851c22a38ad105/LSTMVoter-Chemical-named-entity-recognition-using-a-conglomerate-of-sequence-labeling-tools.pdf), [[code]](https://github.com/texttechnologylab/LSTMVoter)
* Biobert: pre-trained biomedical language representation model for biomedical text mining, Bioinformatics 2020, [[paper]](https://doi.org/10.1093/bioinformatics/btz682), [[code]](https://github.com/dmis-lab/biobert)
* HUNER: Improving Biomedical NER with Pretraining, Bioinformatics 2020, [[paper]](https://doi.org/10.1093/bioinformatics/btz528), [[code]](https://hu-ner.github.io/)

### Hybrid model for BioNER
* Learning Named Entity Tagger using Domain-Specific Dictionary, EMNLP 2018, [[paper]](https://www.aclweb.org/anthology/D18-1230.pdf), [[code]](https://github.com/shangjingbo1226/AutoNER)
* Distantly Supervised Biomedical Named Entity Recognition with Dictionary Expansion, BIBM 2019, [[paper]](https://doi.org/10.1109/BIBM47256.2019.8983212), [[code]](https://github.com/xuanwang91/AutoBioNER)
* Annotating the Pandemic: Named Entity Recognition and Normalisation in COVID-19 Literature, EMNLP 2020, [[paper]](https://www.aclweb.org/anthology/2020.nlpcovid19-2.27.pdf)
