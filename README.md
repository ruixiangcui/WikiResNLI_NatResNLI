# WikiResNLI_NatResNLI
WikiResNLI (a controlled
synthetic dataset) and NatResNLI (a naturally occurring dataset) are two NLI datasets for probing LLMs ability to reason about “respectively” constructions.

## Data
You can download both datasets in the [data](data) folder. 

## Citations

If you use this dataset, please cite the following:
* Ruixiang Cui, Seolhwa Lee, Daniel Hershcovich, Anders Søgaard.2023. [What does the Failure to Reason with "Respectively" in Zero/Few-Shot Settings Tell Us about Language Models?](https://aclanthology.org/2023.acl-long.489/). ACL.
``` bibtex
@inproceedings{cui-etal-2023-failure,
    title = "What does the Failure to Reason with {``}Respectively{''} in Zero/Few-Shot Settings Tell Us about Language Models?",
    author = "Cui, Ruixiang  and
      Lee, Seolhwa  and
      Hershcovich, Daniel  and
      S{\o}gaard, Anders",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.489",
    pages = "8786--8800",
    abstract = "Humans can effortlessly understand the coordinate structure of sentences such as {``}Niels Bohr and Kurt Cobain were born in Copenhagen and Seattle, *respectively*{''}. In the context of natural language inference (NLI), we examine how language models (LMs) reason with respective readings (Gawron and Kehler, 2004) from two perspectives: syntactic-semantic and commonsense-world knowledge. We propose a controlled synthetic dataset WikiResNLI and a naturally occurring dataset NatResNLI to encompass various explicit and implicit realizations of {``}respectively{''}. We show that fine-tuned NLI models struggle with understanding such readings without explicit supervision. While few-shot learning is easy in the presence of explicit cues, longer training is required when the reading is evoked implicitly, leaving models to rely on common sense inferences. Furthermore, our fine-grained analysis indicates models fail to generalize across different constructions. To conclude, we demonstrate that LMs still lag behind humans in generalizing to the long tail of linguistic constructions.",
}
```
## Contact
For questions and usage issues, please contact <rc@di.ku.dk> .

## License
WikiResNLI and NatResNLI are released under the [CC-BY license](https://creativecommons.org/licenses/by/4.0/).