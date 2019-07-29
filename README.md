# HSplit-corpus
Gold-Standard Sentence Splitting Corpus

If you use the corpus, please cite the following paper:

      BLEU is Not Suitable for the Evaluation of Text Simplification
      Elior Sulem, Omri Abend and Ari Rappoport
      Proc. of EMNLP 2018

**./HSplit**

Gold-standard Sentence Splitting Corpus composed by the generations made by 4 annotators, given [the complex side of the test corpus of Xu et al., 2016](https://github.com/cocoxu/simplification), following the sentence splitting guidelines.
HSplit 1 and 2 correspond to Set 1 guidelines. HSplit 3 and 4 correspond to Set 2 guidelines. The corpus includes 359 sentences.

Uniform tokenization and truecasing styles are obtained using the Moses toolkit (Koehn et al., 2007).

**./HSplit_human_evaluation**

Human evaluation scores given for the 4 elicitation questions described in the paper. Each HSplit corpus is scored by 3 annotators.
The human evaluation concerns the first 70 sentences of HSplit. The scores appear in the ods files. The corresponding sentences appear in the txt files.
The evaluation scores for the simplification systems mentioned in the paper can be found at https://github.com/eliorsulem/simplification-acl2018

**License**

[Attribution-ShareAlike 3.0 Unported license](https://creativecommons.org/licenses/by-sa/3.0/)
