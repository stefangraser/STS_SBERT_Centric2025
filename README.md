#STS_SBERT_Centric2025

The respective paper is published on arXiv: 
https://doi.org/10.48550/arXiv.2507.21722

Please cite when using it:
@misc{graser2025identificationdesignrecommendationsaugmented,
      title={Identification of Design Recommendations for Augmented Reality Authors in Corporate Training}, 
      author={Stefan Graser and Martin Schrepp and Stephan Böhm},
      year={2025},
      eprint={2507.21722},
      archivePrefix={arXiv},
      primaryClass={cs.HC},
      url={https://arxiv.org/abs/2507.21722}, 
}



Results are provided in the following data report: http://dx.doi.org/10.13140/RG.2.2.28124.71047 

@dataset{dataset,
author = {Graser, Stefan and Schrepp, Martin and Kollmorgen, Jessica and Escalona, María and Böhm, Stephan},
year = {2025},
month = {06},
pages = {},
title = {Classification of AR Design Recommendations on UX Dimensions: Preliminary Study Results: Research Report & Data},
doi = {10.13140/RG.2.2.28124.71047}
}



We want to acknowledge the work we based on: 

@inproceedings{9781450390927,
author = {Krau\ss{}, Veronika and Jasche, Florian and Sa\ss{}mannshausen, Sheree May and Ludwig, Thomas and Boden, Alexander},
title = {Research and Practice Recommendations for Mixed Reality Design – Different Perspectives from the Community},
year = {2021},
isbn = {9781450390927},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3489849.3489876},
doi = {10.1145/3489849.3489876},
booktitle = {Proceedings of the 27th ACM Symposium on Virtual Reality Software and Technology},
articleno = {24},
numpages = {13},
keywords = {User Interface Design, Mixed Reality, Guidelines, Design Theory and Practice, Design Recommendations, Augmented Reality},
location = {Osaka, Japan},
series = {VRST '21}
}


#references 
https://huggingface.co/sentence-transformers#
https://www.sbert.net/
@inproceedings{reimers-2019-sentence-bert,
  title = "Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks",
  author = "Reimers, Nils and Gurevych, Iryna",
  booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing",
  month = "11",
  year = "2019",
  publisher = "Association for Computational Linguistics",
  url = "https://arxiv.org/abs/1908.10084",
}

#model
https://huggingface.co/sentence-transformers/all-mpnet-base-v2

#library 
from sentence_transformers import SentenceTransformer

#results
provided as file in repo



