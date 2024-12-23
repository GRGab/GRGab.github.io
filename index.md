---
layout: default
title: Gabriel Goren-Roig
use_math: true
---

# Gabriel Goren-Roig

Hi there! I'm Gabo, a PhD student in Mathematics at [Universidad de Buenos Aires](https://www.uba.ar/) working at the intersection between Category Theory, Logic and Computer Science.

I am part of the [Logic, Language and Computability Research Group (GLyC)](https://glyc.dc.uba.ar/), and my advisor is [Santiago Figueira](https://glyc.dc.uba.ar/santiago/). My research is funded by [CONICET](https://www.conicet.gov.ar/).

<!-- Picture of mine -->
<p style="text-align:center;">
<img src="assets/headshot.jpg" alt="Picture" width="250"/>
</p>

## Publications

- S. Figueira, G. Goren-Roig, _Modal Logic with Relations over Paths: a Theoretical Development through Comonadic Semantics_. Accepted for publication in Journal of Logic and Computation. Also [available on the arXiv](https://arxiv.org/abs/2307.09679)
- G.     Goren-Roig, J. Meyers and E. Minichiello, _Presenting Profunctors_. Accepted for publication in ACT 2024 Proceedings. Also [available on the arXiv](https://arxiv.org/abs/2404.01406)

## Research Interests

Here you will find a description of the main motivations behind my research, current and otherwise. I am always happy to discuss these topics, so feel free to get in touch!

<details>
  <summary><strong>Computational Category Theory</strong></summary>
<br>
I am interested in Computational Category Theory for both applied and theoretical reasons.<br><br>

On the applied side, being able to compute answers to categorical questions algorithmically seems fundamental to making Category Theory more applicable in the sciences.
<!-- both by allowing scientists and engineers to use categorical abstractions in their own modelling and by enabling software which does not require them to know Category Theory in order to benefit from it. -->
<a href="https://categoricaldata.net/">Categorical database theory</a> is an excellent example of application where it is crucial—if the idea is to make any sense at all—to not only develop a mathematical theory at a semantic level but also explicitly develop its syntactic and algorithmic counterpart.<br><br>

On the theoretical side, I am interested in how syntax <em>refines</em> semantics, in the sense that new phenomena arise when we become more strict with our notions of mathematical equivalence.
For instance, once we have focused on syntactic descriptions we can narrow the scope even further to the <em>finite</em> ones and analyze the classes of <em>finitely presentable</em> objects that arise.<br><br>

In my work, an interesting example of this phenomenon came up when trying to understand the syntactic representations for <a href="https://ncatlab.org/nlab/show/profunctor">profunctors</a>, which is an important point for categorical database theory. In particular, the fundamental equivalence between functors $\mathcal{C}^\text{op} \times \mathcal{D} \to \sf{Set}$ and functors $\mathcal{C}^\text{op} \to \sf{Set}^\mathcal{D}$ does not carry over to the world of finite syntactic descriptions. This is the main observation that led to the paper <a href="https://arxiv.org/abs/2404.01406">Presenting Profunctors</a>.<br><br>

</details>


<details>
  <summary><strong>Applications of Category Theory to Finite Model Theory and Databases</strong></summary>
<br>
Categorical logic can be understood as the perspective that <em>logics</em>, understood as inductively defined syntax for well-formed formulas and well-formed proofs, constitute syntactic presentations for categorical structures in a similar sense as the one described above.<br><br>

Although the field has a long history and a deep connection with type theory and the theory of programming languages, traditionally it has been disconnected from other areas of logic more connected with combinatorics and computational complexity, as is the case of finite model theory and the theory of databases.<br><br>

An intersection between these two traditions, <em>Structure</em> and <em>Power</em>, has begun to take form owing greatly to the research program of <em>game comonads</em>. Currently, I am particularly interested in using this framework to understand what kinds of logics are possible near the lower end of the expressive power spectrum as exemplified by Basic Modal Logic. In this context <a href="https://arxiv.org/abs/2307.09679">I have worked</a> on a variation of Basic Modal Logic with (non-unary) relations instead of propositional variables and developed its fundamental model theory using the framework of game comonads and arboreal categories.<br><br>

In the past I have studied a bit of coalgebraic modal logic and I would be interested in exploring the connection with this topic as well.
<br><br>
</details>

<details><summary><strong>Emergence</strong></summary>
<br>
I am interested in developing a rigorous understanding of the concept of emergence. Currently, I am trying to understand the relationship between emergence and failure of the glueing axiom as formalized by sheaf theory. Computationally, this can be seen as local consistency of data that fails to imply global consistency, as it happens in topics such as dynamic programming, constraint satisfaction and data integration.<br><br>

I am also interested in emergence from the perspective of information loss through coarse-graining. This perspective partly contributes to my interest in logical indistinguishability of models as a form of logical or language-based coarse-graining.<br><br>

Finally, going back to my Physics training, I also have a perennial interest in dynamical systems and the coarse-graining of dynamics, as exemplified by center manifolds and Crutchfield et al.'s fascinating predictive states/computational mechanics framework. Although these topics are not part of my current research, I intend to reconnect with them eventually.<br><br>

</details>

## News

### 2024

Accepted publications:
- S. Figueira, G. Goren-Roig, _Modal Logic with Relations over Paths: a Theoretical Development through Comonadic Semantics_ accepted for publication in Journal of Logic and Computation.
- G.     Goren-Roig, J. Meyers and E. Minichiello, _Presenting Profunctors_, accepted for publication in ACT 2024 Proceedings.

Talks given:
- _Presenting Profunctors_ @ ACT 2024 ([video](https://youtu.be/EnN1-ZuMEU0?si=Sx5bo4C6HMlThPIf))
- _Generalised Unions of Conjunctive Queries in the Algebraic Data Model_ @ TACL 2024 ([pdf](https://iiia.csic.es/tacl2024/abstracts/conference/book_abstracts_TACL24.pdf#page=159))

Classes taken for my PhD program:
- Differential Topology
- Homological Algebra
- Algebraic Geometry

I also attended the [TACL 2024 Summer School](https://iiia.csic.es/tacl2024/school.html), including tutorials on quantum contextuality, categorical automata theory and the theory of polymorphisms for constraint satisfaction problems.

### 2023

- Took a class on Algebraic Topology towards the fulfillment of my PhD program requirements.
- March: gave a flash talk on the concept of comonads at the local event _Día del ICC_
- July: Took a [one-week intensive tutorial](https://www.lirmm.fr/~sau/talks/ECI-2023-Ignasi.pdf) on _Algorithmic aspects_ of _minor_-closed _graph_ by Ignasi Sau
- Spent time learning about [algebraic databases](https://arxiv.org/abs/1602.03501) and about the encoding of [dynamic programming algorithms through sheaf theory](https://arxiv.org/abs/2302.05575).
- Submitted for publication the first version of the paper _Modal Logic with Relations over Paths: a Theoretical Development through Comonadic Semantics_ ([arXiv](https://arxiv.org/abs/2307.09679)).

### 2022

- Nov. 23rd - Dec. 21st: taught an [introductory, online course on Causal Inference](https://humai.com.ar/cursos/causalidad) at [Humai](https://humai.com.ar/) (in Spanish) together with [Wendy Brau](https://ar.linkedin.com/in/wendy-brau) and [Pedro Zenone](https://ar.linkedin.com/in/pedro-zenone-9018b65b).
- Organized a local reading group on basic Category Theory following Riehl's *Category Theory in Context* and Spivak & Fong's *Seven Sketches*.
- Presented a poster (available [here](/assets/poster-eci2022.pdf)) (in Spanish) giving an introductory explanation for CS/Math students of Abramsky et al.'s Comonadic Semantics program, at the [ECI 2022](https://eci.dc.uba.ar/what-is-eci/) (School of Informatic Sciences) in Buenos Aires.
- Gave a talk at the [Structure Meets Power 2022 Workshop](https://www.cst.cam.ac.uk/conference/structure-meets-power-2022) on the topic of *Path Predicate Modal Logic and its Comonadic Semantics* ([Extended Abstract](https://www.cst.cam.ac.uk/files/book-of-abstracts.pdf#page=12), [Slides](https://www.cst.cam.ac.uk/files/smp2022-1745-goren.pdf))
- Gave a lecture on Introductory Probability Theory to students of Mathematics for Machine Learning at the [Humai](https://ihum.ai/) institute.
- Attended the thematic month [Logic & Interactions 2022](https://conferences.cirm-math.fr/2507.html) at CIRM, fully funded by the [joint CIRM-CIMPA fellowship program](https://www.cimpa.info/en).
- Took a class on Galois-Grothendieck Theory by Eduardo Dubuc for my PhD program

### 2021

- Participated in the [Adjoint School 2021](https://adjointschool.com/2021.html). During the Research Week, took part in the Extensions of Coalgebraic Dynamic Logic group under the mentoring of Helle Hvid Hansen and Clemens Kupke. As culmination of the Research Week, gave a talk at the [ACT 2021 Conference](https://www.cl.cam.ac.uk/events/act2021/) together with [Amin Karamlou](https://aminkaramlou.github.io/) titled *Stochastic game logic, coalgebraically*.
- Received a [Licentiate Degree in Physics](https://www.df.uba.ar/es/futuros-estudiantes/guia-para-el-estudiante) from the Universidad de Buenos Aires.
- Defended my Licentiate Thesis, _Inferencia causal mediante correlación
sintáctica_ ([Thesis](assets/Goren_Gabriel_Tesis_Lic.pdf)) ([Slides](assets/Defensa_de_Tesis_Lic_Gabriel_Goren.pdf)) (in Spanish) conducted under the supervision of Ariel Bendersky and [Santiago Figueira](https://glyc.dc.uba.ar/santiago/).
- Received a grant from the Argentine national research council [CONICET](www.conicet.gob.ar) to pursue a PhD.