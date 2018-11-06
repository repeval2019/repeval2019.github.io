---
# layout: page
title: About
permalink: /about/
---

## The Third Workshop on Evaluating Vector Space Representations for NLP

General-purpose word embeddings have come a long way since the beginning of their boom in 2013, and they are still the most widely used way of representing words in both industrial and academic NLP systems, but the traditional intrinsic evaluation tasks such as word similarity and analogy have been shown to have limited predictive power. Since the last RepEval there also appeared a number of probing tasks and large extrinsic evaluation datasets for sentence representations, but it is not yet clear what features make a compositional representation successful. There are also no established intrinsic methods for evaluating newer kinds of representations such as ELMO, BERT, or box embeddings.

The third edition of RepEval aims to foster discussion of these issues, and to support the search for high-quality general purpose representation learning techniques for NLP. Furthermore, we hope to encourage interdisciplinary dialogue by welcoming diverse perspectives on the above issues: submissions may focus on mathematical properties of representations, on analysis of various NLP task performance, as well as approaches based on linguistic and psychological data. In particular, experts from the latter fields are encouraged to contribute analysis of linguistic/psycholinguistic claims previously made in NLP community.

RepEval 2019 will invite submissions including, but not limited to the following issues:

 * reliable intrinsic measures for task-independent meaning representations, and their ability to predict downstream task performance;
 * approaches for intrinsic evaluation of contextualized and other kinds of representations;
 * evaluations motivated with linguistic, psycholinguistic or neurological evidence, and interpretability of meaning representations vs evaluation on downstream tasks;
 * the (un)stability of vector representations, and best practices for reproducible and reliable experiments;
 * evaluation of representations at subword level, especially with regards to morphologically complex languages;
 * evaluation of phrase, sentence, paragraph and document-level representations: evidence of compositionality, further diagnostic tests, and how much the preservation of abstract syntactic information actually contributes to performance;
 * alternatives to cosine similarity and vector offsets in representation evaluation methods;
 * gauging the effect of representations themselves and other elements of pipeline in extrinsic task evaluations;
 * validation of evaluation methodology and findings in cross-lingual studies;
 * specialized vs general-purpose representations, and whether the latter have inherent limits in downstream task;
 * internal states of end-to-end systems as meaning representations, and ways to make more sense of them.

The workshop will accept submissions through three tracks. The *proposal track* will showcase proposals for new evaluation techniques for old and new representations; the submissions are expected to experimentally demonstrate the benefits of the new approach. The *analysis track* will provide critical analysis and/or negative results for the existing approaches. We welcome both theoretical analysis (especially from experts in other domains such as linguistics or psychology) and methodological caveats (reproducibility, parameters, the issue of attribution of results to the representation or the whole system).

The *MultiEval shared task* will consist of a "diagnostics challenge" for word-level models, which would be a combination of intrinsic and extrinsic methods. Participating systems will be profiled for what kinds of information they capture as vector neighborhoods (measured by [LDT library](<http://ldtoolkit.space>)), and how that correlates with their performance on a suite of downstream tasks. This hybrid intrinsic/extrinsic approach aims at discovering what intrinsic properties are actually useful for various tasks, enabling hypothesis-driven design and tuning of NLP systems.