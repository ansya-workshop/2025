---
title: "Call for Papers"
# menu:
#   main:
#     weight: 10
---

__Authors are invited to submit original papers in PDF format to the [submission website](https://easychair.org/my/conference?conf=ansya2025).__

## 📃 Submission Type

The workshop provides a platform to share experimental and theoretical results, present artefacts, demos and datasets, as well as broad discussion or survey papers. Therefore, ANSyA invites researchers and practitioners to submit the following types of contribution:

1. __Full__ or __short__ papers about NeSy approaches, emphasising practical aspects, applications, or applicability to real-world problems. Full papers should be limited to __7 pages__, while short papers should be limited to __2 pages__ _(excluding references)_.

2. __Artefact papers__ presenting _software applications_ tools and libraries with proven potential to impact the NeSy domain. Artefact papers should be limited to __2 pages__ _(excluding references)_.

3. __Demo papers__ presenting in detail the _usage_ of software tools which may be relevant in the NeSy domain. Demo papers should be limited to __2 pages__ _(excluding references)_.

4. __Dataset description papers__ presenting the details of _datasets_ that can be used in the NeSy domain. Dataset description papers should be limited to __2 pages__ _(excluding references)_.

5. __Report papers__ presenting valuable lessons learned in engineering NeSy design and/or applying NeSy to specific fields. Report papers should be limited to __7 pages__ _(excluding references)_.

6. __Position papers__ concerning NeSy applications in specific fields. Position papers should be limited to __2 pages__ _(excluding references)_.

7. __Survey papers__, concerning any of the above. Survey papers should be limited to __7 pages__ _(excluding references)_.

❗ Preliminary or already-published work can be submitted, provided that the submission is clearly marked as such. ❗ 

## 📋 Submission Guidelines

- Submissions should be in [__ECAI LaTeX format__](https://ecai2025.org/wp-content/uploads/2025/04/ecai-template.zip);
- Submissions must be exported in __PDF format__;
- _Camera-ready_ versions shall include the LaTeX __source files__;
- Submissions must be anonymised for __double-blind__ review.


## 🔬 Topics of Interest

Given the broad categorization of NeSy AI systems, we welcome papers that propose applications and engineering research in various domains, including (but not limited to):

- Neuro-Symbolic integration application in cybersecurity
- Neuro-Symbolic integration and intelligent agents
- Neuro-Symbolic integration and intelligent networked systems
- Neuro-Symbolic integration application in healthcare
- Neuro-Symbolic integration and large language models
- Neuro-Symbolic integration application in robotics
- Neuro-Symbolic integration application in computer vision
- Neuro-Symbolic integration for planning
- Neuro-Symbolic integration for programming (e.g., program synthesis)
- Symbolic knowledge extraction (SKE) or injection (SKI)
- Theorem proving via Neuro-Symbolic integration
- Automated reasoning via Neuro-Symbolic integration
- AI trustworthiness (explainable, fair, etc.) via Neuro-Symbolic integration
- Symbolic regression via Neuro-Symbolic integration
- Inductive logic programming via Neuro-Symbolic integration

__Twin communities:__ We also welcome contributions from twin communities leveraging different nomenclature for similar concepts, such as informed-machine learning, symbolic knowledge extraction or injection, etc.


## 📝 Reviewing Format

ANSyA follows a 2-phase reviewing process:
1. Each submission will undergo a traditional double-blind review process. This phase applies to all papers, regardless of type, and will determine the final acceptance or rejection decision. 
2. The second phase occurs during and after the workshop: accepted contributions are presented (as posters) at the workshop, and authors may collect further comments and insights. After that, authors who are willing to publish their contribution to the workshop proceedings will be requested to produce a final version of the paper, addressing the reviewers’ suggestions and possibly integrating comments and insights from the workshop.

All papers will undergo the standard assessment in which reviewers will be asked to consider the submission focusing on its:
- __scope__: is the paper on-topic w.r.t. the workshop’s track or theme?
- __significance__: is the idea proposed in the paper meaningful for the NeSy community? Are the results relevant?
- __soundness__: is the approach proposed in the paper correct and robust? Are experiments (if any) well-designed?
- __clarity__: is the paper clear and well organized? Is the discussion complete?
- __contextualization__: is relevant background and related literature being adequately referenced?
- __novelty__: is the contribution novel either from a conceptual or technical perspective?
- __practical__ applicability: is the proposed idea applicable in practice? Can it scale? Do the authors provide convincing evidence?

Furthermore, the reviews will take into account the specific characteristics of the submitted contributions to obtain their final decision. For example, submissions proposing novel software will receive a score depending also on the quality of the shared software. Similarly, demo papers will receive a score depending on the usability and utility of the tool under demonstration.

## 📖 Camera-ready papers

> Accepted papers will be included in the workshop proceedings __only if__ the authors explicitly agree to do so. 
In this way, works which are not mature enough for publication, as well as works which have already been published elsewhere can be presented and discussed at the workshop.

### Web-site CR

__All__ papers will have to produce a _web-site_ camera-ready version addressing reviewers' comments.
Updated PDFs will have to be submitted on EasyChair by updating the original submission.

The purpose here is to create a shared folder for all accepted papers,
to be accessed by all (and only) the workshop participants.

No need to perform any big stylistic change, and no need to be strict about page limitations in this phase.

### Proceedings CR 

The workshop will publish its own proceedings as [CEUR-WS](https://ceur-ws.org/) volume.
All accepted papers' authors will be asked if they agree to include their paper in the proceedings.
Default is **yes**.

In any case, proceedings production will occur __after__ the workshop,
so that authors will be able to incorporate feedback received during the event.

#### Important details for typesetting your paper for publication

Page limitations constraints are mild on CEUR,
but the authors who are willing to include their papers in the proceedings
will have to adhere to the [formatting guidelines specified by CEUR-WS](https://ceur-ws.org/HOWTOSUBMIT.html).

1. Use the CEUR template, last version. The only admissible sources are:
    - [Overleaf template](https://www.overleaf.com/latex/templates/template-for-submissions-to-ceur-workshop-proceedings-ceur-ws-dot-org/wqyfdgftmcfw)
    - [GitHub](https://github.com/yamadharma/ceurart)

2. Use the __2 column__ layout. In other words, your class definition in LaTeX should be:
    ```latex
    \documentclass[twocolumn]{ceurart}
    ```

3. Recall to set the Copyright Clause correctly in the LaTeX source files:
    ```latex
    \copyrightyear{2025}
    \copyrightclause{Copyright for this paper by its authors.
    Use permitted under Creative Commons License Attribution 4.0 International (CC BY 4.0).}
    ```

4. Recall to set the conference name as follows:
    ```latex
    \conference{
       ANSyA 2025: $1^{st}$ International Workshop on Advanced Neuro-Symbolic Applications,
       co-located with ECAI 2025.
    }
    ```

5. Capitalize your titles (there including section titles) coherently, and capitalize all major words. Example:
    - ✅ Good Title: `A Study on the Impact of X on Y`
    - ❌ Bad Title: `A study on the impact of x on y`

6. Prefer vectorial formats for pictures (e.g., SVG, PDF) over raster formats (e.g., PNG, JPEG).

7. Pay attentions to your bibliography section: prefer DOIs over URLs, and only use one of them if both are available.

8. Let the corresponding author prepare a signed copy of the [copyright form](https://ceur-ws.org/ceur-author-agreement-ccby-ntp.pdf)
    - _do not compile it digitally_: __you must print it, sign it, and then scan it as a PDF file__.