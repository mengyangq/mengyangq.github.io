---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr. Mengyang Qiu is an Assistant Professor in the [Department of Speech-Language Pathology](https://www.steu.edu/academics/aas/speech-language-pathology/index.html) at Saint Elizabeth University. Before joining SEU, he was an Assistant Professor in the [Department of Psychology](https://www.trentu.ca/psychology/) at Trent University from 2023 to 2025. Dr. Qiu earned his PhD in Communicative Disorders and Sciences (Cognitive Science Track) from the University at Buffalo in 2024, under the supervision of Drs. [Nichol Castro](https://arts-sciences.buffalo.edu/cds/people/academicfaculty.host.html/content/shared/arts-sciences/cds/faculty-profiles/academic-faculty/castro-nichol.html) and [Brendan T. Johns](https://www.mcgill.ca/psychology/brendan-t-johns). He also holds an MS in Computational Linguistics, an MA in Linguistics, and a BA in Psychology and Linguistics (Honors in Language and Cognition) from the University at Buffalo.

Dr. Qiu’s research spans two main lines of work. The first investigates language and cognition, with a particular focus on cognitive aging. The second applies natural language processing to educational and clinical contexts, centering on grammatical error correction.

<details markdown="1">
<summary>Read more</summary>

In his research on language and cognition, Dr. Qiu uses computational modeling approaches such as distributional semantics and network science, together with behavioral experiments, to explore how differences in linguistic experience influence language and memory processing across aging. Core questions include how much variation in lexical performance, such as word recognition, can be explained by individual differences in language experience, and which types of test stimuli most accurately capture an individual’s linguistic knowledge. The long-term goal of this work is to delineate the natural changes that occur due to accumulated linguistic experience from actual cognitive decline in aging, supporting the development of more sensitive assessments for neurodegenerative disorders and their precursors, such as mild cognitive impairment.

Dr. Qiu’s research on natural language processing for educational and clinical applications covers the full pipeline of grammatical error correction (GEC). This work includes developing linguistically informed frameworks for error annotation and evaluation in English, Chinese, and other typologically diverse languages, as well as exploring how large language models can be integrated into different stages of the GEC pipeline. Across this line of research, his goal is to develop scalable and interpretable methods that better support second language learning and instruction, and the diagnosis of language disorders.

</details>

---

# News

<style>
.news-scroll {
  height: 400px;
  overflow-y: auto;
  scrollbar-gutter: stable;
  scrollbar-width: thin;
  scrollbar-color: transparent transparent;
}
.news-scroll.is-scrolling { scrollbar-color: #888 transparent; }
.news-scroll::-webkit-scrollbar { width: 6px; }
.news-scroll::-webkit-scrollbar-track { background: transparent; }
.news-scroll::-webkit-scrollbar-thumb { background: transparent; border-radius: 3px; }
.news-scroll.is-scrolling::-webkit-scrollbar-thumb { background: #888; }
.news-scroll table { display: table; width: 100%; margin: 0; font-size: inherit; border: 0; }
.news-scroll thead { display: none; }
.news-scroll td { border: 0; padding: 0.5rem; vertical-align: top; }
.news-scroll td:first-child { width: 6rem; white-space: nowrap; }
</style>

<div class="news-scroll" markdown="1" tabindex="0" role="region" aria-label="News">

| Date | News |
| :--- | :--- |
| **Oct 2026** | My forthcoming book with Jungyeul Park, [*Chinese Grammatical Error Correction, Annotation, and Evaluation*](https://link.springer.com/book/9783032459879), is now listed by Springer, with publication scheduled for 2027. |
| **May 2026** | Co-authored paper accepted for publication in *American Journal of Speech-Language Pathology*: "[Paired comparison vs. cross-sectional approaches for assessing longitudinal speech change in Parkinson’s disease following STN-DBS](https://doi.org/10.1044/2026_AJSLP-26-00092)". |
|  | Poster presented at *CMCL 2026*: "[Can LLMs Simulate Human Behavioral Variability? A Case Study in the Phonemic Fluency Task](https://mengyang.dev/publication/qiu-etal-2026-llm)". |
| **Apr 2026** | Co-authored paper accepted for publication in *Electronics*: "[Bias in Large Language Models: Origin, Evaluation, and Mitigation](https://doi.org/10.3390/electronics15091824)". |
|  | Paper accepted at *ICAIE 2026*: "Automated Writing Evaluation with Corrective Feedback". |
|  | Presented at the *2026 NJSHA Convention*: "[How Is AI Being Used Across Communication Disorders? A Review of the Research](https://mengyang.dev/presentations/sun_etal_2026_how)". |
| **Mar 2026** | Paper accepted at *CMCL 2026*: "Can LLMs Simulate Human Behavioral Variability? A Case Study in the Phonemic Fluency Task". |
|  | Abstract accepted for poster presentation at the *55th Clinical Aphasiology Conference*: "Bridging Disciplines in AI for Aphasia Research: A Network Analysis of Publication Abstracts Across CS and Non-CS Venues". |
| **Jan 2026** | Joined the Department of Speech-Language Pathology at Saint Elizabeth University as Assistant Professor. |

</div>

<script>
document.querySelectorAll('.news-scroll').forEach(function (box) {
  let hideTimer;
  box.addEventListener('scroll', function () {
    box.classList.add('is-scrolling');
    clearTimeout(hideTimer);
    hideTimer = setTimeout(function () {
      box.classList.remove('is-scrolling');
    }, 1000);
  }, { passive: true });
});
</script>

