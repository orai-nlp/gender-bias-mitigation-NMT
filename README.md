# Gender Bias Mitigation for NMT Involving Genderless Languages

This is the data for the paper Gender Bias Mitigation for NMT Involving Genderless Languages presented in WMT 2022

https://www.statmt.org/wmt22/pdf/2022.wmt-1.10.pdf


## Abstract

It has been found that NMT systems have a strong preference towards social defaults and biases when translating certain occupations, which due to their widespread use, can unintentionally contribute to amplifying and perpetuating these patterns. In that sense, this work focuses on sentence-level gender agreement between gendered entities and occupations when translating from genderless languages to languages with grammatical gender. Specifically, we address the Basque to Spanish translation direction for which bias mitigation has not been addressed. Gender information in Basque is explicit in neither the grammar nor the morphology. It is only present in a limited number of gender specific common nouns and person proper names. We propose a template-based fine-tuning strategy with explicit gender tags to provide a stronger gender signal for the proper inflection of occupations. This strategy is compared against systems fine-tuned on real data extracted from Wikipedia biographies. We provide a detailed gender bias assessment analysis and perform a template ablation study to determine the optimal set of templates. We report a substantial gender bias mitigation (up to 50\% on gender bias scores) while keeping the original translation quality.

## Citation

If you use any of this data in your work, please cite:

```
@article{corralgender,
  title={Gender Bias Mitigation for NMT Involving Genderless Languages},
  author={Corral, Ander and Saralegi, Xabier}
}
```
