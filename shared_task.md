---
layout: page
title: Shared Task
permalink: /shared/
navigation_weight: 3
---

## <span class="c14 c53">The RepEval 2017 Shared Task</span>

### <span class="c25">Introduction</span>

<span>RepEval 2017 features a shared task meant to evaluate natural language understanding models based on sentence encoders—that is, models that transform sentences into fixed-length vector representations and reason using those representations. The task will be natural language inference (also known as recognizing textual entailment, or RTE) in the style of</span> <span class="c2">[SNLI](http://nlp.stanford.edu/projects/snli/)</span><span class="c4">—a three-class balanced classification problem over sentence pairs. The shared task will feature a new, dedicated dataset that spans several genres of text. Participation is open and new teams may join at any time.</span>

<span class="c4"></span>

<span>The shared task includes two evaluations, a standard in-domain (matched) evaluation in which the training and test data are drawn from the same sources, and a cross-domain (mismatched) evaluation in which the training and test data differ substantially. This cross-domain evaluation will test the ability of submitted systems to learn</span> <span class="c4">representations of sentence meaning that capture broadly useful features.</span>

### <span class="c25">The data</span>

The training and development sections of the task data can be found [here](http://nyu.edu/projects/bowman/multinli/). The unlabeled test data is available through the Kaggle in Class competiton pages (<a href="https://inclass.kaggle.com/c/multinli-matched-evaluation/data"><span class="c4">matched</span></a>, <a href="https://inclass.kaggle.com/c/multinli-mismatched-evaluation/data"><span class="c4">mismatched</span></a>).

<span>The task dataset (called the Multi-Genre NLI Corpus, or MultiNLI) consist of 393k training examples drawn from five genres of text, and 40k test and development examples drawn from those same five genres, as well as five more. Data collection for the task dataset is be closely modeled on</span> <span class="c2">[SNLI](http://nlp.stanford.edu/projects/snli/)</span><span>, which is based on the genre of image captions, and may be used as additional training and development data, but will not be included in the evaluation.</span>

<span class="c4"></span>

<a id="t.65e94aab32684b27bd9c0ded893f49c4546886c0"></a><a id="t.0"></a>

<table class="c20" padding="4">

<tbody>

<tr class="c3">

<td class="c48" colspan="1" rowspan="1">

<strong>Section name</strong>

</td>

<td class="c46" colspan="1" rowspan="1">

<strong>Training pairs</strong>

</td>

<td class="c41" colspan="1" rowspan="1">

<strong>Dev pairs</strong>

</td>

<td class="c36" colspan="1" rowspan="1">

<strong>Test pairs</strong>

</td>

</tr>

<tr class="c3">

<td class="c34" colspan="1" rowspan="1">

<span class="c7">Captions (SNLI Corpus)</span>

</td>

<td class="c49" colspan="1" rowspan="1">

<span class="c7">(550,152)</span>

</td>

<td class="c44" colspan="1" rowspan="1">

<span class="c7">(10,000)</span>

</td>

<td class="c51" colspan="1" rowspan="1">

<span class="c7">(10,000)</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Fiction</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">77,348</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Government</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">77,350</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Slate</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">77,306</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Telephone Speech</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">83,348</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Travel Guides</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">77,350</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">9/11 Report</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">0</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Face-to-face Speech</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">0</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Letters</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">0</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c22" colspan="1" rowspan="1">

<span class="c5">Nonfiction Books (OUP)</span>

</td>

<td class="c30" colspan="1" rowspan="1">

<span class="c5">0</span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c9" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c31" colspan="1" rowspan="1">

<span class="c5">Magazine (Verbatim)</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">0</span>

</td>

<td class="c40" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

<td class="c50" colspan="1" rowspan="1">

<span class="c5">2,000</span>

</td>

</tr>

<tr class="c3">

<td class="c48" colspan="1" rowspan="1">

<span class="c14 c11">Total</span>

</td>

<td class="c46" colspan="1" rowspan="1">

<span class="c5">392,702</span>

</td>

<td class="c41" colspan="1" rowspan="1">

<span class="c5">20,000</span>

</td>

<td class="c36" colspan="1" rowspan="1">

<span class="c5">20,000</span>

</td>

</tr>

</tbody>

</table>

<span class="c4"></span>


<span>As in SNLI, each example will consist of two sentences and a label. The first sentence is drawn from a preexisting text source—either one of the sections of the</span> <span class="c2">[Open American National Corpus](https://www.anc.org/oanc/)</span><span> (OpenANC) or some other permissively licensed source. The second sentence is written by crowd workers as part of data collection. Data for each genre will be collected in a separate crowdsourcing task. The labels will be</span> <em>entailment</em><span>,</span> <em>neutral</em><span>, and <em>contradiction</em>, in roughly equal proportions. Some examples from the corpus can be seen below.</span>

<span class="c4"></span>

<a id="t.69933aa0e44b75a463015374d7f77f5dc897d5c8"></a><a id="t.1"></a>

<table class="c20" padding="5">

<tbody>

<tr class="c3">

<td class="c17" colspan="1" rowspan="1">

<strong>Premise</strong>

</td>

<td class="c37" colspan="1" rowspan="1">

<strong>Label</strong>

</td>

<td class="c35" colspan="1" rowspan="1">

<strong>Hypothesis</strong>

</td>

</tr>

<tr class="c0">

<td class="c38" colspan="3" rowspan="1">

<em>Fiction</em>

</td>

</tr>

<tr class="c3">

<td class="c17" colspan="1" rowspan="1">

<span>The Old One always comforted Ca'daan, except today.</span>

</td>

<td class="c37" colspan="1" rowspan="1">

<em>neutral</em>

</td>

<td class="c35" colspan="1" rowspan="1">

<span class="c4">Ca'daan knew the Old One very well.</span>

<span class="c5"></span>

</td>

</tr>

<tr class="c0">

<td class="c38" colspan="3" rowspan="1">

<em>Letters</em>

</td>

</tr>

<tr class="c3">

<td class="c17" colspan="1" rowspan="1">

<span>Your gift is appreciated by each and every student who will benefit from your generosity.</span>

</td>

<td class="c37" colspan="1" rowspan="1">

<em>neutral</em>

</td>

<td class="c35" colspan="1" rowspan="1">

<span class="c4">Hundreds of students will benefit from your generosity.</span>

<span class="c5"></span>

</td>

</tr>

<tr class="c0">

<td class="c38" colspan="3" rowspan="1">

<em>Telephone Speech</em>

</td>

</tr>

<tr class="c3">

<td class="c17" colspan="1" rowspan="1">

<span>yes now you know if if everybody like in August when everybody's on vacation or something we can dress a little more casual or</span>

</td>

<td class="c47" colspan="1" rowspan="1">

<em>contradiction</em>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c4">August is a black out month for vacations in the company.</span>

<span class="c5"></span>

</td>

</tr>

<tr class="c3">

<td class="c38" colspan="3" rowspan="1">

<em>9/11 Report</em>

</td>

</tr>

<tr class="c3">

<td class="c17" colspan="1" rowspan="1">

<span>At the other end of Pennsylvania Avenue, people began to line up for a White House tour.</span>

</td>

<td class="c37" colspan="1" rowspan="1">

<em>entailment</em>

</td>

<td class="c35" colspan="1" rowspan="1">

<span class="c4">People formed a line at the end of Pennsylvania Avenue.</span>

<span class="c5"></span>

</td>

</tr>

</tbody>

</table>

<span class="c4"></span>

<span class="c4">Data is available in the same two formats as SNLI: tab-separated values and jsonl. It will take the form of five files in each format: train, in-domain development, cross-domain development, in-domain test, and cross-domain test. Each individual example will be marked with a genre tag.</span>

<span class="c4"></span>

<span class="c4">We are also separately distributing a [small subset of the development data that has been manually annotated to facilitate error analysis](https://www.nyu.edu/projects/bowman/multinli/multinli_0.9_annotations.zip).</span>

### <span>Rules</span><span class="c25"> and evaluation</span>

<span class="c4"></span>

<span class="c14 c28 c15">Evaluation</span>

*   <span>Evaluation will be done using the Kaggle platform. During the evaluation period, participants download an unlabeled copy of the test set, use their systems to predict labels, and upload those labels. Standard Kaggle rules apply.</span>
*   <span class="c4">Participants may submit to either or both of the two evaluations (in-domain or cross-domain).</span>
*   <span class="c4">Multiple submissions from the same team are allowed, up to a limit of two per day during the two-week evaluation period. Individual participants (i.e., PIs) may join multiple teams within reason, but only when each team reflects a fully independent engineering effort, and each team has a different lead developer. (Note: Kaggle may not allow entrants to formally join multiple teams. In this case, PIs and others spanning multiple teams should join at most a single Kaggle team and only disclose their memberships in their paper submission.)</span>

<span class="c4"></span>

<span class="c14 c15 c28">Systems</span>

*   <span class="c4">This competition is meant to evaluate the quality of vector representations of sentences, and all submitted systems should include a bottleneck in which sentences are represented as fixed-length vectors with no explicitly-imposed internal structure. Typical attention and memory models that represent sentences as sets or sequences of vectors, though useful for tasks like NLI, are not eligible for inclusion in this competition. (It is allowed, should it be useful, to use two separate models to encode the two input sentences.)</span>
*   <span class="c4">The development sets are to be used for model selection and the tuning of reasonable hyperparameters. Models that are explicitly trained on the development data may be disqualified.</span>
*   <span class="c4">Models should make their predictions for each example independantly. It is the case that different pairs sharing the same premise typically have different labels (as an artificact of how we created the data), but systems are not allowed to exploit this signal to model joint distributions over multiple examples at once. (If you aren't sure whether this applies to your system, it probably doesn't.)</span>
*   <span>For inclusion in the workshop and the final leaderboard, participants will have to upload a</span> <span>code package</span><span>that can be used to reproduce the submitted results. This code package will not be used as the primary means of evaluation, but it will be made public to encourage both reproducibility and future extension of submitted models.</span>
*   <span class="c4">For inclusion in the workshop and the final leaderboard, participants will also be asked to provide the sentence vectors produced by their best performing model. When you submit your system, you will also be asked to upload a sentence vector file with lines of the form 'pairID \t p or h (for premise or hypothesis) \t sentence representation vector as whitespace-delimited (tab or space) values. For example, a line might look like:

   ```
   123	p	0.27204 -0.06203 -0.1884 0.023225 -0.018158 0.0067192 -0.13877 0.17708 0.17709 2.5882 -0.35179 -0.17312 0.43285 -0.10708 0.15006 -0.19982 -0.19093 1.1871 -0.16207 -0.23538 0.003664 -0.19156 -0.085662 0.039199 -0.066449 -0.04209 -0.19122 0.011679 -0.37138 0.21886 0.0011423 0.4319 -0.14205 0.38059 0.30654 0.020167 -0.18316 -0.0065186 -0.0080549 -0.12063 0.027507 0.29839 -0.22896 -0.22882 0.14671 -0.076301 -0.1268 -0.0066651 -0.052795 0.14258 0.1561 0.05551 -0.16149 0.09629 -0.076533 -0.049971 -0.010195 -0.047641 -0.16679 -0.2394 0.0050141 -0.049175 0.013338 0.41923 -0.10104 0.015111 -0.077706 -0.13471 0.119 0.10802 0.21061 -0.051904 0.18527 0.17856 0.041293 -0.014385 -0.082567 -0.035483 -0.076173 -0.045367 0.089281 0.33672 -0.22099 -0.0067275 0.23983 -0.23147 -0.88592 0.091297 -0.012123 0.013233 -0.25799 -0.02972 0.016754 0.01369 0.32377 0.039546 0.042114 -0.088243 0.30318 0.087747 0.16346 -0.40485 -0.043845 -0.040697 0.20936 -0.77795 0.2997 0.2334 0.14891 -0.39037 -0.053086 0.062922 0.065663 -0.13906 0.094193 0.10344 -0.2797 0.28905 -0.32161 0.020687 0.063254 -0.23257 -0.4352 -0.017049 -0.32744 -0.047064 -0.075149 -0.18788 -0.015017 0.029342 -0.3527 -0.044278 -0.13507 -0.11644 -0.1043 0.1392 0.0039199 0.37603 0.067217 -0.37992 -1.1241 -0.057357 -0.16826 0.03941 0.2604 -0.023866 0.17963 0.13553 0.2139 0.052633 -0.25033 -0.11307 0.22234 0.066597 -0.11161 0.062438 -0.27972 0.19878 -0.36262 -1.0006e-05 -0.17262 0.29166 -0.15723 0.054295 0.06101 -0.39165 0.2766 0.057816 0.39709 0.025229 0.24672 -0.08905 0.15683 -0.2096 -0.22196 0.052394 -0.01136 0.050417 -0.14023 -0.042825 -0.031931 -0.21336 -0.20402 -0.23272 0.07449 0.088202 -0.11063 -0.33526 -0.014028 -0.29429 -0.086911 -0.1321 -0.43616 0.20513 0.0079362 0.48505 0.064237 0.14261 -0.43711 0.12783 -0.13111 0.24673 -0.27496 0.15896 0.43314 0.090286 0.24662 0.066463 -0.20099 0.1101 0.03644 0.17359 -0.15689 -0.086328 -0.17316 0.36975 -0.40317 -0.064814 -0.034166 -0.013773 0.062854 -0.17183 -0.12366 -0.034663 -0.22793 -0.23172 0.239 0.27473 0.15332 0.10661 -0.060982 -0.024805 -0.13478 0.17932 -0.37374 -0.02893 -0.11142 -0.08389 -0.055932 0.068039 -0.10783 0.1465 0.094617 -0.084554 0.067429 -0.3291 0.034082 -0.16747 -0.25997 -0.22917 0.020159 -0.02758 0.16136 -0.18538 0.037665 0.57603 0.20684 0.27941 0.16477 -0.018769 0.12062 0.069648 0.059022 -0.23154 0.24095 -0.3471 0.04854 -0.056502 0.41566 -0.43194 0.4823 -0.051759 -0.27285 -0.25893 0.16555 -0.1831 -0.06734 0.42457 0.010346 0.14237 0.25939 0.17123 -0.13821 -0.066846 0.015981 -0.30193 0.043579 -0.043102 0.35025 -0.19681 -0.4281 0.16899 0.22511 -0.28557 -0.1028 -0.018168 0.11407 0.13015 -0.18317 0.1323
   ```
   You should supply vectors for every sentence (premise and hypothesis) in the test set(s) for the competition(s) you're submitting to. 
   In addition, you are also asked to submit vectors for a set of additional probe sentences. These sentences are [here](http://nyu.edu/projects/bowman/multinli/extra-sentences-needing-vectors.zip), distributed in the same format as MultiNLI, but with one sentence per line, marked as the premise, and no hypothesis. All your vectors should be concatenated into a single file.</span>

<span class="c4"></span>

<span class="c14 c28 c15">Outside data</span>

*   <span>The use of outside data is allowed, including</span><span class="c4"> raw unannotated text from any source, word vector packages, and knowledge resources like WordNet are explicitly permitted. We will provide links to unlabeled OpenANC data that reflects the target genres.</span>
*   <span class="c4">All outside data used must be publicly available to allow for reproducibility. Widely-used data with restrictive licenses or licensing fees (such as LDC-distributed corpora) may be allowed at our discretion. Please inquire at the QA forum below.</span>


### <span class="c25">Baselines</span>

*   The <a href="http://nyu.edu/projects/bowman/multinli">corpus description paper</a> presents the following baselines:


<span class="c4"></span>

<a id="t.65e94aab32684b27bd9c0ded893f49c4546886c0"></a><a id="t.0"></a>

<table class="c20" padding="4">

<tbody>

<tr class="c3">

<td class="c48" colspan="1" rowspan="1">

<strong>Model&nbsp;</strong>

</td>

<td class="c46" colspan="1" rowspan="1">

<strong>Matched Test Acc.&nbsp;</strong>

</td>

<td class="c41" colspan="1" rowspan="1">

<strong>Mismatched Test Acc.</strong>

</td>

</tr>

<tr class="c3">
<td class="c34" colspan="1" rowspan="1">
<span class="c7">Most Frequent Class</span>
</td>
<td class="c49" colspan="1" rowspan="1">
<span class="c7">36.5</span>
</td>
<td class="c44" colspan="1" rowspan="1">
<span class="c7">35.6</span>
</td>
</tr>

<tr class="c3">
<td class="c34" colspan="1" rowspan="1">
<span class="c7">CBOW</span>
</td>
<td class="c49" colspan="1" rowspan="1">
<span class="c7">65.2</span>
</td>
<td class="c44" colspan="1" rowspan="1">
<span class="c7">64.6</span>
</td>
</tr>

<tr class="c3">
<td class="c34" colspan="1" rowspan="1">
<span class="c7">BiLSTM</span>
</td>
<td class="c49" colspan="1" rowspan="1">
<strong>67.5</strong>
</td>
<td class="c44" colspan="1" rowspan="1">
<strong>67.1</strong>
</td>
</tr>

</tbody>

</table>

<span class="c4"></span>

* Note that the paper also presents results with an [ESIM](https://arxiv.org/abs/1609.06038). That model relies on attention between sentences and would be ineligible for inclusion in this competition.

* Both models are trained on a mix of MultiNLI and SNLI and use [GloVe](https://nlp.stanford.edu/projects/glove/) word vectors.

* Code (TensorFlow/Python) is available [here](https://github.com/NYU-MLL/multiNLI).

<span class="c4"></span>

### <span class="c25">Leaderboard and evaluation site</span>

<span class="c4">To participate in the competition, evaluate your system, or view the current mid-competiton leaderboard (including systems that may not qualify for the final leaderboard), use these two Kaggle in Class competitions:</span>
  *   <a href="https://inclass.kaggle.com/c/multinli-matched-evaluation"><span class="c4">MultiNLI Matched</span></a>
  *   <a href="https://inclass.kaggle.com/c/multinli-mismatched-evaluation"><span class="c4">MultiNLI Mismatched</span></a>

### <span class="c25">Paper submission</span>

<span class="c4">For inclusion in the workshop and the final leaderboard, you must submit:</span>
  *   <span class="c4">A system description paper of 2–4 pages in ACL format. System description papers will be reviewed for readability and soundness (but not novelty/technical merit) before acceptance.</span>
  *   <span class="c4">A .zip code package that can be used to reproduce the submitted results after being trained on widely-available data files.</span>

### <span class="c25">Key dates</span>

*   <strong>March 24:</strong> <span class="c4">[Training and development data and draft data description paper](http://nyu.edu/projects/bowman/multinli) available, competition begins</span>
*   <strong>By May 15:</strong> <span class="c4">[Expert-tagged development data for error analysis](https://www.nyu.edu/projects/bowman/multinli/multinli_0.9_annotations.zip) available</span>
*   <strong>June 1:</strong> <span class="c4">Unlabeled test data available, evaluation period begins, Kaggle evaluation site opens</span>
*   <strong>June 14 (GMT-11, 23:59:59):</strong> <span class="c4">Evaluation period ends, system description papers and code packages due</span>
*   <strong>June 16:</strong> <span class="c4">Winners formally announced</span>
*   <strong>July 3 (GMT-11, 23:59:59):</strong> <span class="c4">Reviews due</span>
*   <strong>July 6:</strong> <span class="c4">Notification of presentation acceptance</span>
*   <strong>July 21</strong><strong> (GMT-11, 23:59:59)</strong><strong>:</strong><span> Camera ready papers due</span>
*   <strong>September 8:</strong> <span class="c4">Workshop at EMNLP 2017, Copenhagen: shared task poster session and selected short talks</span>

### <span class="c25">Join us!</span>

*   <span>Announcements list (all participants should subscribe):</span> <span class="c2">[Google Group](https://groups.google.com/forum/#!forum/repeval17-annouce)</span>
*   <span>Discussion/FAQ forum (ask questions here first):</span> <span class="c2">[Google Forum](https://groups.google.com/forum/#!forum/repeval17-qa/)</span>
*   <span>Private questions:</span> <span class="c2">[Sam Bowman](mailto:bowman@nyu.edu)</span>
