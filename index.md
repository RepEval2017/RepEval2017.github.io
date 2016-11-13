---
layout: default
---

<h1 id="about">RepEval 2017: The Second Workshop on Evaluating Vector Space Representations for NLP</h1>


Overview
---------
This workshop deals with the evaluation of general-purpose vector representations for linguistic units (morphemes, words, phrases, sentences, etc). What distinguishes these representations (or \textit{embeddings}) is that they are not trained with a specific application in mind, but rather to capture broadly useful features of the represented units. Another way to view their usage is through the lens of transfer learning: The embeddings are trained with one objective, but applied on others. 

Evaluating general-purpose representation learning systems is fundamentally difficult. They can be trained on a variety of objectives, making simple intrinsic evaluations useless as a means of comparing methods. They are also meant to be applied to a variety of downstream tasks, which will place different demands on them, making no single extrinsic evaluation definitive. The best techniques for evaluating embedding methods in downstream tasks often require investing considerable time and resources in retraining large neural network models, making broad suites of downstream evaluations impractical. In many cases, especially for word-level embeddings, these constraints have led to the rise of dedicated evaluation tasks like similarity and analogy which are not directly related either to training objectives or to downstream tasks. Tasks like these can serve a valuable role in principle, but in practice performance on these tasks has not been highly predictive of downstream task performance.

This workshop aims foster discussion of these issues, and to support the search for high-quality general purpose representation learning techniques for NLP. The workshop will accept submissions through two tracks: a proposal track will showcase submitted proposals for new evaluation techniques, and a shared task will accept submissions of new general purpose sentence representation systems---for which standard evaluations are notably absent---which will be evaluated on a sentence understanding task.




Organizers
---------
Sam Bowman\\
Yoav Goldberg\\
Felix Hill\\
Angeliki Lazaridou\\
Omer Levy\\
Roi Reichart\\
Anders Sogaard\\

Programme Committee
---------
Omri Abend\\
Mohit Bansal\\
Jose Camacho Collados\\
Billy Chiu\\
Georgiana Dinu\\
Allyson Ettinger\\
Sahar Ghannay\\
Anna Gladkova\\
Mohit Iyyer\\
Douwe Kiela\\
Arne Kohn\\
Andras Kornai\\
Tal Linzen\\
Farhana Liza\\
Oren Melamud\\
Dmitrijs Milajevs\\
Diarmuid O’Seaghdha\\
Denis Paperno\\
Ellie Pavlick\\
Marek Rei\\
Laura Rimell\\
Naomi Saphra\\
Roy Schwartz\\
Patrice Seyed\\
Gabriel Stanovsky\\
Pontus Stenetorp\\
Karl Stratos\\
Yulia Tsvetkov\\
Peter Turney\\
Ivan Vulic\\
Torsten Zesch\\



{% comment %}
* October 2016: Our work <a href="http://clic.cimec.unitn.it/marco/publications/lazaridou-et-al-chimeras-cogsci.pdf">Multimodal word meaning induction from minimal exposure to natural text</a> with Marco Marelli and Marco Baroni got accepted at Cognitive Science Journal.

* October 2016: In January 2017 I will be joining <a href="https://deepmind.com/">Google DeepMind</a> as a research scientist. 

* September 2016: I'm spending 3 months at <a href="https://research.facebook.com/ai">Facebook AI Research</a> working on grounded multi-agent communication.

* September 2016: We are organizing <a href="https://mainatnips.github.io/">Machine Intelligence Workshop @ NIPS 2016</a>. Abstract submission deadline October 9th.

* September 2016: We released the first prototype of <a href="https://github.com/facebookresearch/CommAI-env">CommAI-env</a>, an environment meant to stimulate the development of communication-based AI.

* August 2016: Check out <a href="http://clic.cimec.unitn.it/lambada/"> LAMBADA</a>, our new text understanding dataset, with humans scoring 100% and SoA 0%. 

* May 2016: I recently gave a talk at the NLP seminal at ISI (USC) on our new work on <a href="https://arxiv.org/abs/1605.07133v1"> Multi-Agent Communication-Based Language Learning</a>.

* April 2016: Our work <a href="http://arxiv.org/abs/1603.02618">The red one!: On learning to refer to things based on their discriminative properties</a> with Nghia The Pham  and Marco Baroni will appear at ACL 2016!

* March 2016: I will be spending 3 months this fall at Facebook AI.

* March 2016: I will be spending 3 months this summer at ISI (USC).

* March 2016: Our work <a href="../resourses/vision/learning-from-childes-short-naacl2016.pdf">Multimodal Semantic Learning from Child-Directed Input</a> with Grzegorz Chrupala, Raquel Fernandez and Marco Baroni will appear at NAACL 2016!

* February 2016: Together with Douwe Kiela and Desmond Elliott, we will be giving an ACL tutorial on *Multimodal Learning and Reasoning*

* February 2016: I'm co-organizing the <a href="https://sites.google.com/site/naaclsrw2016/">NAACL SRW 2016</a> (San Diego, USA). Submission deadline: March 11, 2016.

* December 2015: I attended Women In Machine Learning (NIPS 2015). 

* September 2015: Slides on <a href="../resourses/talks/MmLL.pdf">Multimodal Language Learning</a> (Talks at IBM Watson, UPenn and Facebook AI)

* June 2015: <a href="http://arxiv.org/abs/1506.03500">What is the meaning of a word? Language-driven image generation from word embeddings</a>

* June 2015: Our work *A Multitask Objective to Inject Lexical Contrast into Distributional Semantics* with Nghia and Marco will appear at ACL 2015 (Short)!

* April 2015: <a href="http://angelikilazaridou.github.io/publications/">Two long papers</a> to appear at ACL 2015!

* April 2015: Our work *Improving Zero-shot Learning by Mitigating the Hubness Problem* with Georgiana and Marco will appear at ICLR!

* March 2015: Our work *From Visual Attributes to Adjectives through Decompositional Distributional Semantics* with Georgiana, Adam and Marco got accepted at TACL!

* February 2015: Our work *Combining Language and Vision with a Multimodal Skip-gram Model*  with Nghia and Marco, got selected for an oral presentation at NAACL!

* February 2015: I was selected as a Facebook Fellowship Finalist.

{% endcomment %}

