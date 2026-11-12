# Cross-language alignment with shared and disjoint vocabularies

The figure compares raw representations and tokenwise novelty in transformers trained on the multilingual Random Hierarchy Model (mRHM). The two languages use independent lower-level substitution rules that draw on either a shared terminal vocabulary or two disjoint terminal vocabularies.

Both vocabulary settings show qualitatively similar behaviour. For raw representations and novelty alike, information imbalance (II) reaches its minimum and mutual k-nearest-neighbour overlap (mKNN, k = 10) reaches its maximum at intermediate transformer depths.

[Vector PDF](mrhm-shared-vs-disjoint-vocabulary-alignment.pdf) · [PNG](mrhm-shared-vs-disjoint-vocabulary-alignment.png)

![Raw and tokenwise novelty alignment across transformer depth for shared and disjoint vocabularies, measured by II and mKNN.](mrhm-shared-vs-disjoint-vocabulary-alignment.png)
