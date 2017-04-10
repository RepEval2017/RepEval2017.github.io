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

<span>The shared task will feature two evaluations, a standard in-domain evaluation in which the training and test data are drawn from the same sources, and a cross-domain evaluation in which the training and test data differ substantially. This cross-domain evaluation will test the ability of submitted systems to learn</span> <span class="c4">representations of sentence meaning that capture broadly useful features.</span>

### <span class="c25">The data</span>

A preliminary version of the training and development sections of the task data can be found [here](http://nyu.edu/projects/bowman/multinli/).

<span>The task dataset (called the Multi-Genre NLI corpus, or MultiNLI) consist of 393k training examples drawn from five genres of text, and 40k test and development examples drawn from those same five genres, as well as five more. Data collection for the task dataset is be closely modeled on</span> <span class="c2">[SNLI](http://nlp.stanford.edu/projects/snli/)</span><span>, which is based on the genre of image captions, and may be used as additional training and development data, but will not be included in the evaluation.</span>

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

<span class="c4">After the start of the competition, we will additionally release a small subset of the data that has been manually annotated to facilitate error analysis.</span>

### <span>Rules</span><span class="c25"> and evaluation</span>

<span class="c4"></span>

<span class="c14 c28 c15">Evaluation</span>

*   <span>Evaluation will be done using the Kaggle platform. During the evaluation period, submitters download an unlabeled copy of the test set, use their systems to predict labels, and upload those labels.</span>
*   <span class="c4">Submitters may submit to either or both of the two evaluations (in-domain or cross-domain).</span>
*   <span class="c4">Multiple submissions from the same team are allowed, up to a limit of two per day during the two-week evaluation period. Individual participants may join multiple teams within reason, but only when each team reflects a fully independent engineering effort.</span>

<span class="c4"></span>

<span class="c14 c15 c28">Systems</span>

*   <span class="c4">This competition is meant to evaluate the quality of vector representations of sentences, and all submitted systems should include a bottleneck in which sentences are represented as fixed-length vectors with no explicitly-imposed internal structure. Typical attention and memory models that represent sentences as sets or sequences of vectors, though useful for tasks like NLI, are not eligible for inclusion in this competition. (It is allowed, should it be useful, to use two separate models to encode the two input sentences.)</span>
*   <span class="c4">The development sets are to be used for model selection and the tuning of reasonable hyperparameters. Models that are explicitly trained on the development data may be disqualified.</span>
*   <span>For inclusion in the workshop and the final leaderboard, submitters will have to upload a</span> <span>code package</span><span>that can be used to reproduce the submitted results. This code package will not be used as the primary means of evaluation, but it will be made public to encourage both reproducibility and future extension of submitted models.</span> <span class="c4">Moreover, for a limited set of sentences, participants will be asked to provide the sentence vectors produced by their best performing model. These vectors will be used in our own analysis of the results.</span>

<span class="c4"></span>

<span class="c14 c28 c15">Outside data</span>

*   <span>The use of outside data is allowed, including</span><span class="c4"> raw unannotated text from any source, word vector packages, and knowledge resources like WordNet are explicitly permitted. We will provide links to unlabeled OpenANC data that reflects the target genres.</span>
*   <span class="c4">All outside data used must be publicly available to allow for reproducibility. Widely-used data with restrictive licenses or licensing fees (such as LDC-distributed corpora) may be allowed at our discretion. Please inquire at the QA forum below.</span>

### <span class="c25">Paper submission</span>

*   <span class="c4">For inclusion in the workshop and the final leaderboard, you must submit:</span>
  *   <span class="c4">A system description paper of 2–4 pages in ACL format. System description papers will be reviewed for readability and soundness (but not novelty/technical merit) before acceptance.</span>
  *   <span class="c4">A .zip code package that can be used to reproduce the submitted results after being trained on widely-available data files.</span>

### <span class="c25">Key dates</span>

*   <strong>March 24:</strong> <span class="c4">[Training and development data and draft data description paper](http://nyu.edu/projects/bowman/multinli) available, competition begins</span>
*   <strong>By May 1:</strong> <span class="c4">Expert-tagged development data for error analysis available</span>
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
