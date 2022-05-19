# attention-as-grounding



## Citation

  > [Nikolai Ilinykh and Simon Dobnik. 2022. Attention as Grounding: Exploring Textual and Cross-Modal Attention on Entities and Relations in Language-and-Vision Transformer. In Findings of the Association for Computational Linguistics: ACL 2022, pages 4062–4073, Dublin, Ireland. Association for Computational Linguistics.](https://aclanthology.org/2022.findings-acl.320/)

This paper can be also found [here](acl-2022/paper-1844.pdf).

If you find our models or results useful, please cite as follows:

```
@inproceedings{ilinykh-dobnik-2022-attention,
    title = "Attention as Grounding: Exploring Textual and Cross-Modal Attention on Entities and Relations in Language-and-Vision Transformer",
    author = "Ilinykh, Nikolai  and
      Dobnik, Simon",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2022",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.findings-acl.320",
    pages = "4062--4073",
    abstract = "We explore how a multi-modal transformer trained for generation of longer image descriptions learns syntactic and semantic representations about entities and relations grounded in objects at the level of masked self-attention (text generation) and cross-modal attention (information fusion). We observe that cross-attention learns the visual grounding of noun phrases into objects and high-level semantic information about spatial relations, while text-to-text attention captures low-level syntactic knowledge between words. This concludes that language models in a multi-modal task learn different semantic information about objects and relations cross-modally and uni-modally (text-only). Our code is available here: https://github.com/GU-CLASP/attention-as-grounding.",
}
```
