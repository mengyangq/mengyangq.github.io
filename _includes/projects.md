# Projects

### Grammatical Error Correction
**Supervisor:** Jungyeul Park, Ph.D.

**Collaborators:** Xuejiao Chen, Maggie Liu, Krishna Parvathala, Apurva Patil

__**Artificial Error Generation with Fluency Filtering**__

The quantity and quality of training data plays a crucial role in grammatical error correction (GEC). However, due to the fact that obtaining human-annotated GEC data is both time-consuming and expensive, several studies have focused on generating artificial error sentences to boost training data for grammatical error correction, and shown  significantly better performance. The present study explores how fluency filtering can affect the quality of artificial errors. By comparing artificial data filtered by different levels of fluency, we find that artificial error sentences with low fluency can greatly facilitate error correction, while high fluency errors introduce more noise.

**Qiu, M.** & Park, J. (under review). Artificial error generation with fluency filtering.

__**Improving Precision of Grammatical Error Correction with Cheat Sheet**__

In this paper, we explore two approaches of generating error-focused phrases and examine whether these phrases can lead to better performance in grammatical error correction for the restricted track of BEA 2019 Shared Task on GEC. Our results show that phrases directly extracted from GEC corpora outperform phrases from statistical machine translation phrase table by a large margin. Appending error+context phrases to the original GEC corpora yields comparably high precision. We also explore the generation of artificial syntactic error sentences using error+context phrases for the unrestricted track. The additional training data greatly facilitates syntactic error correction (e.g., verb form) and contributes to better overall performance.

**Qiu, M.**, Chen, X., Liu, M., Parvathala, K., Patil, A. & Park, J. (under review). Improving precision of grammatical error correction with cheat sheet.

__**Correlation between Fluency and Accuracy in Learners Corpus**__

Developing proficiency levels for non-native speakers has always been a difficult task. In this study, we explore the NUS learners corpus and its annotated grammatical errors to automatically assign proficiency levels to individual participants by using fluency and accuracy of the learners' text. We determine the upper bound and lower bound of learners by using statistical measurement and classify learners into levels of accuracy and fluency. We conclude that perplexity for fluency is more correlate to accuracy compared to other fluency metrics in previous works. In addition, this perplexity fluency metric is more effective in predicting proficiency.

Liu, M., Patil, A., Chawla, J. K. & Park, J. (under review). Correlation between fluency and accuracy in learners corpus.


### The Effects of Semantic Diversity on Paired-Associate Learning
**Supervisor:** Brendan Johns, Ph.D.

- The information accumulation perspective of aging proposes that it is the continual accumulation of experience in memory that leads older adults to have worse performance across a variety of psychometric tests ([Ramscar, et al., 2014](http://www.sfs.uni-tuebingen.de/~mramscar/papers//Ramscar%20et%20al%20age%20TOPICS.2014)). [Ramscar, et al. (2017)](http://www.sfs.uni-tuebingen.de/~mramscar/papers/RamscarSunHendrixBaayen2017.pdf) explicitly tested this assumption with a paired-associate learning experiment,  where it was found that people with less linguistic experience (age-matched bilinguals) perform better in paired-associate learning. 

- The goal of this study was to further evaluate the information accumulation perspective of aging using paired-associate learning, building off of the work of [Ramscar, et al. (2017)](http://www.sfs.uni-tuebingen.de/~mramscar/papers/RamscarSunHendrixBaayen2017.pdf).  The current study removed the potential confounds of bilingualism by using a within-subjects design. This was accomplished by attaining words that have either high or low levels of association to other words, but equivalent word frequency, through the use of semantic diversity ([Jones, et al., 2012](http://btjohns.com/pubs/JJR_CJEP_2012.pdf)). 

- In a simulation study, it was shown that words high in semantic diversity had a greater level of association to other words, compared with words that had low semantic diversity. Our behavioral experiment \[[code](https://github.com/mengyangq/paired-associate-learning)\] found that even though older adults had lower overall accuracy, the decrease in performance was driven by the high SD words. Older adults performed equally well as younger adults in the low SD condition. This finding demonstrates that it is the greater amount of associations that older adults have acquired through experience that causes their poorer performance on a PAL task.

<img src="../pub/pal.jpeg" width="55%" height="55%">

**Qiu, M.** & Johns, B. T. (in prep). The effects of semantic diversity on paired-associate learning: Continued evidence for the information accumulation perspective of cognitive aging.

### Memory Searching Pathway Underlying Verb Fluency
**Supervisor:** Brendan Johns, Ph.D.

- Verbal fluency is one of the most widely used measures of cognitive functioning, in which subjects produce as many different words as possible from a given criterion (e.g., animal category) within 1 minute.

- Compared to noun category fluency, there are fewer studies on verb fluency, even though verbs are thought to play a more prominent role in organizing mental lexicon and in describing events.

- The current study compares memory search pathway underlying verb fluency to noun (animal category) fluency using a cognitive modeling approach. Fluency data was collected on Amazon Mechanical Turk \[[code](https://github.com/mengyangq/Verb-Fluency)\].

- The modeling results show that animal fluency and verb fluency have distinct memory search pathways. People dynamically use semantic (context) and syntactic (order) information to organize memory retrieval in verb fluency. 

- Verb fluency may be useful in diagnosing different clinical populations (e.g., agrammatic vs. anomic aphasia) as they may exhibit different search patterns.

<img src="../pub/vf.png" width="55%" height="55%">

**Qiu, M.** & Johns, B. T. (2018). [Memory searching pathway underlying verb fluency](../pub/Qiu_Johns_ASHA_2018.pdf). Poster presented at the *2018 ASHA Convention*.

### Grammatical Aspect and the Activation of Location Information
**Supervisor:** Jean-Pierre Koenig, Ph.D.

Previous studies have found that grammatical aspect (imperfective / perfective) can modulate the activation level of various participant roles (or thematic roles, e.g., agents, patients, instruments) in online sentence processing by focusing on different stages of an event. For example, [Ferretti et al. (2007)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3228359/pdf/nihms332153.pdf) found that specific event locations (locations in which all participants are located) were more activated when verbs mark situations as ongoing (imperfective aspect) than when they mark them as completed (perfect aspect). They claimed that focusing on the ongoing part of an event would naturally lead to focusing on where the event is happening. The current study extends their findings to participant locations (locations in which not all participants are located). By manipulating aspects and verbs taking different types of participant location--highly involved through the whole event vs. only in the middle vs. only at the end, it is predicted that there will be different levels of activation of location information and distinct patterns of locative phrase generation in a sentence completion task.
