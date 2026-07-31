# AI Campus Champions — Program Summary & Study Notes

> **University of Arizona AI Campus Champions** program (Summer 2026): a module-by-module recap, with summaries of every assigned reading and the course's own content graphics for each week.

This README summarizes the coursework in the [UA AI Campus Champions](https://github.com/UA-AI2S/AI-Champions/wiki) program run by the Arizona Institute for Artificial Intelligence (AI2S) and the Office of Responsible AI (ORAI). It is a personal study reference — the original course materials, tasks, and rubrics live in the [program wiki](https://github.com/UA-AI2S/AI-Champions/wiki).

![6-Week AI Leadership Roadmap](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/6-Week_AI_Leadership_Roadmap.png)

---

## About the Program

The program develops **AI Campus Champions**: practitioners who don't merely use AI tools but understand them deeply enough to make principled decisions about their use, evaluate outputs critically, articulate their risks, and guide colleagues doing the same. It was designed for faculty and staff at an early-to-intermediate stage of AI adoption, with no assumption of technical background.

| | |
|---|---|
| **Institution** | University of Arizona — AI2S / Office of Responsible AI |
| **Instructor** | Carlos Lizárraga |
| **Format** | 6 modules · 1 h synchronous + 3 h independent each · 24 h total |
| **Pedagogical spine** | Bloom's Revised Taxonomy — from *Remember* (Module 1) to *Create* (Module 6) |
| **Duration** | June 16 – July 28, 2026 |

The six modules are sequenced along the cognitive dimension, moving from lower-order to higher-order thinking across the six-week arc:

| Module | Focus |
|---|---|
| 1 | **AI Foundations** — vocabulary, history, and the current landscape |
| 2 | **Generative AI** — capabilities, limitations, and prompting |
| 3 | **AI for Productivity** — workflow integration and academic practice |
| 4 | **Critical Thinking About AI** — bias, fairness, and epistemic limits |
| 5 | **AI Governance** — policy and responsible use |
| 6 | **AI Campus Champion** — initiative design and leadership |

---

## Table of Contents

- [About the Program](#about-the-program)
- [Module 1 — AI Foundations](#module-1--ai-foundations)
  - [Learning objectives](#learning-objectives)
  - [Key topics](#key-topics)
    - [What a foundation model is](#what-a-foundation-model-is)
    - [Emergence](#emergence)
    - [Homogenization](#homogenization)
    - [The AI → ML → Deep Learning → LLM hierarchy](#the-ai--ml--deep-learning--llm-hierarchy)
    - [Next-token prediction](#next-token-prediction)
  - [Assigned readings](#assigned-readings)
    - [Reading 1 · On the Opportunities and Risks of Foundation Models (Bommasani et al., 2021)](#reading-1--on-the-opportunities-and-risks-of-foundation-models-bommasani-et-al-2021)
    - [Reading 2 · Stanford HAI AI Index 2025 (Executive Summary)](#reading-2--stanford-hai-ai-index-2025-executive-summary)
- [Module 2 — Generative AI](#module-2--generative-ai)
  - [Learning objectives](#learning-objectives-1)
  - [Key topics](#key-topics-1)
    - [Chain-of-thought prompting](#chain-of-thought-prompting)
    - [Zero-shot vs. few-shot prompting](#zero-shot-vs-few-shot-prompting)
    - [Hallucinations and their taxonomy](#hallucinations-and-their-taxonomy)
    - [Diffusion models](#diffusion-models)
    - [Retrieval-augmented generation (RAG)](#retrieval-augmented-generation-rag)
  - [Assigned readings](#assigned-readings-1)
    - [Reading 1 · Chain-of-Thought Prompting Elicits Reasoning in LLMs (Wei et al., 2022)](#reading-1--chain-of-thought-prompting-elicits-reasoning-in-llms-wei-et-al-2022)
    - [Reading 2 · Survey of Hallucination in Natural Language Generation (Ji et al., 2023)](#reading-2--survey-of-hallucination-in-natural-language-generation-ji-et-al-2023)
- [Module 3 — AI for Productivity](#module-3--ai-for-productivity)
  - [Learning objectives](#learning-objectives-2)
  - [Key topics](#key-topics-2)
    - [The jagged technological frontier](#the-jagged-technological-frontier)
    - [Centaurs, cyborgs, and self-automators](#centaurs-cyborgs-and-self-automators)
    - [Academic integrity and disclosure](#academic-integrity-and-disclosure)
    - [Designing a personal AI workflow](#designing-a-personal-ai-workflow)
  - [Assigned readings](#assigned-readings-2)
    - [Reading 1 · Experimental Evidence on the Productivity Effects of Generative AI (Noy & Zhang, 2023)](#reading-1--experimental-evidence-on-the-productivity-effects-of-generative-ai-noy--zhang-2023)
    - [Reading 2 · Navigating the Jagged Technological Frontier (Dell'Acqua et al., 2023)](#reading-2--navigating-the-jagged-technological-frontier-dellacqua-et-al-2023)
- [Module 4 — Critical Thinking About AI](#module-4--critical-thinking-about-ai)
  - [Learning objectives](#learning-objectives-3)
  - [Key topics](#key-topics-3)
    - [Types of algorithmic bias](#types-of-algorithmic-bias)
    - [Intersectional bias](#intersectional-bias)
    - [The stochastic parrot critique](#the-stochastic-parrot-critique)
    - [Fairness evaluation frameworks](#fairness-evaluation-frameworks)
  - [Assigned readings](#assigned-readings-3)
    - [Reading 1 · Gender Shades (Buolamwini & Gebru, 2018)](#reading-1--gender-shades-buolamwini--gebru-2018)
    - [Reading 2 · On the Dangers of Stochastic Parrots (Bender et al., 2021)](#reading-2--on-the-dangers-of-stochastic-parrots-bender-et-al-2021)
- [Module 5 — AI Governance](#module-5--ai-governance)
  - [Learning objectives](#learning-objectives-4)
  - [Key topics](#key-topics-4)
    - [The NIST AI Risk Management Framework](#the-nist-ai-risk-management-framework)
    - [The UNESCO Recommendation on AI Ethics](#the-unesco-recommendation-on-ai-ethics)
    - [Principles-based vs. rules-based governance](#principles-based-vs-rules-based-governance)
  - [Assigned readings](#assigned-readings-4)
    - [Reading 1 · NIST AI Risk Management Framework (AI RMF 1.0) (2023)](#reading-1--nist-ai-risk-management-framework-ai-rmf-10-2023)
    - [Reading 2 · UNESCO Recommendation on the Ethics of AI (2021)](#reading-2--unesco-recommendation-on-the-ethics-of-ai-2021)
- [Module 6 — Becoming an AI Campus Champion](#module-6--becoming-an-ai-campus-champion)
  - [Learning objectives](#learning-objectives-5)
  - [Key topics](#key-topics-5)
    - [Communities of practice](#communities-of-practice)
    - [Bloom's revised taxonomy](#blooms-revised-taxonomy)
    - [The AI adoption initiative canvas](#the-ai-adoption-initiative-canvas)
  - [Assigned readings](#assigned-readings-5)
    - [Reading 1 · Cultivating Communities of Practice (Wenger, McDermott & Snyder, 2002)](#reading-1--cultivating-communities-of-practice-wenger-mcdermott--snyder-2002)
    - [Reading 2 · A Revision of Bloom's Taxonomy (Krathwohl, 2002)](#reading-2--a-revision-of-blooms-taxonomy-krathwohl-2002)
- [Complete Reading List](#complete-reading-list)
- [Credits & License](#credits--license)

---

## Module 1 — AI Foundations

**What is AI and why does it matter now?** The opening module builds a shared, accurate vocabulary for AI and situates the current moment within the field's history — from symbolic AI through the Transformer architecture to foundation models.

![AI Foundations — Student Revision Guide](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/AI_Foundations_Student_Revision_Guide.png)

### Learning objectives

1. Define AI, machine learning, deep learning, LLM, and generative AI accurately and in my own words.
2. Summarize the historical arc from symbolic AI through the Transformer to foundation models.
3. Explain, conceptually, how LLMs are trained via next-token prediction on large text corpora.
4. Construct a concept map linking core AI concepts with correctly labeled directional relationships.
5. Identify at least one plausible AI impact on a specific recurring task in my professional role.

### Key topics

#### What a foundation model is
A *foundation model* is a single model trained on broad data at scale that can be adapted (via fine-tuning or prompting) to a wide range of downstream tasks. The definition rests on two properties: the training approach (self-supervised learning on massive unlabeled corpora) and the adaptation range (one base model serving many applications). GPT-4o, Claude, and Gemini are all foundation models.

#### Emergence
Emergence describes capabilities that appear unpredictably at scale and were never explicitly trained — abilities that are absent in smaller models but present in larger ones. Emergence is central to why foundation models are difficult to predict even for the teams that build them: you cannot always tell in advance what a bigger model will be able to do.

#### Homogenization
Homogenization is the consolidation of methods so that one model architecture powers many applications. The course frames this as a double-edged property: it concentrates improvements (a better base model lifts everything built on it) but also concentrates risk (a single flaw, bias, or failure propagates to every downstream system).

#### The AI → ML → Deep Learning → LLM hierarchy
A core Module 1 exercise is drawing the nested relationships correctly: **AI ⊃ Machine Learning ⊃ Deep Learning**, with neural networks as the substrate of deep learning and LLMs as a deep-learning application. Machine learning is *not* a synonym for AI — symbolic/rule-based systems are AI without being ML. Generative AI (an output type) and foundation models (a training paradigm) overlap but are not the same thing.

#### Next-token prediction
LLMs are trained to predict the next token in a sequence given the prior context. They generate text that statistically matches patterns in their training data — which explains both why they are fluent *and* why they hallucinate. This differs fundamentally from human knowledge, which involves conceptual understanding, embodied experience, and intentionality.

### Assigned readings

#### Reading 1 · On the Opportunities and Risks of Foundation Models (Bommasani et al., 2021)

*Assigned: Section 1 (Introduction, pp. 1–12) + Section 2 overview (pp. 12–19) · ~35 min · [PDF](https://arxiv.org/pdf/2108.07258)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![Foundation Model Paradigm Shift Notes](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Foundation_Model_Paradigm_Shift_Notes.png)
</details>

This Stanford report is the first systematic academic treatment of the "foundation model" paradigm, coining the term itself. It argues that a new class of models — trained on broad data at scale and adaptable to many tasks — has become the organizing reality of modern AI. The authors define the paradigm around two intertwined properties, **emergence** (capabilities arising unpredictably with scale) and **homogenization** (the same model underpinning diverse applications), and argue these make foundation models simultaneously powerful and hazardous: gains and defects both propagate widely. The paper surveys capabilities (language, vision, robotics, reasoning) and the full sweep of societal stakes — inequity, misuse, economic and environmental costs, and the concentration of power among the few organizations able to train such models. Its enduring contribution is giving practitioners precise vocabulary — *foundation model, emergence, homogenization, in-context learning* — that distinguishes rigorous discussion from popular-press hand-waving. *Why it mattered for the course:* it supplies the conceptual substrate every later module builds on.

#### Reading 2 · Stanford HAI AI Index 2025 (Executive Summary)

*Assigned: Executive Summary (Top Takeaways) + Chapter 4 (Economy) and Chapter 7 (Education) · ~25 min · [PDF](https://hai.stanford.edu/assets/files/hai_ai_index_report_2025.pdf)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![2026 Global AI Report Summary](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/2026_Global_AI_Report_Summary.png)
</details>

The AI Index is the most comprehensive annual empirical benchmark of AI's state — spanning technical performance, economics, education, policy, and responsible-AI incidents. The 2025 Executive Summary documents rapidly narrowing gaps between models (including open-weight vs. closed, and US vs. international systems), sharp performance gains on hard reasoning benchmarks, falling inference costs, and accelerating adoption of generative AI among knowledge workers. Crucially, it reports *both* progress and caution — safety incidents, evaluation gaps, and uneven benefits — which is why the course insists on reading it critically rather than dismissing it as advocacy. The education and economy chapters ground abstract trends in the participants' own institutional context: how students and faculty are actually using AI, and where measurable productivity effects appear. The module even points to the newer [2026 edition](https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf) to illustrate how quickly the landscape shifts year to year. *Why it mattered for the course:* it turns opinion about "AI's impact" into citable evidence.

---

## Module 2 — Generative AI

**Capabilities, limitations, and prompting.** Module 2 moves from *what AI is* to *how to work with it*: comparing tools systematically, engineering prompts deliberately, and auditing outputs for the failure mode that most affects professional use — hallucination.

![Generative AI — Capabilities and Prompting](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Generative_AI_Capabilities_and_Prompting.png)

### Learning objectives

1. Compare two LLM tools against identical prompts using a structured rubric, identifying capability and limitation patterns.
2. Apply zero-shot, few-shot, and chain-of-thought prompting to improve an output on a real professional task.
3. Detect and classify hallucinations in AI-generated text using the Ji et al. (2023) taxonomy.
4. Explain how diffusion models generate images and how retrieval-augmented generation (RAG) grounds LLM outputs.
5. Annotate an AI tool landscape map with access status, use cases, and institutional concerns specific to my role.

### Key topics

#### Chain-of-thought prompting
Chain-of-thought (CoT) prompting asks a model to produce explicit intermediate reasoning steps before its final answer. Because the model models the reasoning process rather than jumping straight to a conclusion, accuracy improves markedly on multi-step arithmetic, commonsense, and symbolic tasks. Understanding *why* CoT works lets you apply it deliberately — on genuinely multi-step problems — rather than as a superstitious ritual.

#### Zero-shot vs. few-shot prompting
*Zero-shot* prompting gives the model an instruction with no examples; *few-shot* prompting includes a handful of worked examples in the prompt to demonstrate the desired format or reasoning pattern. Few-shot examples exploit in-context learning to steer output style and structure without any retraining.

#### Hallucinations and their taxonomy
A hallucination is fluent, plausible text that is factually wrong. The course uses the Ji et al. taxonomy to make the concept auditable: **intrinsic** hallucinations contradict the provided source, while **extrinsic** ones add unverifiable claims not grounded in any source — and errors can be factual, relational, or temporal. Naming the type turns "that looks off" into a systematic check.

#### Diffusion models
Diffusion models generate images by learning to reverse a gradual noising process: starting from random noise and iteratively denoising toward an image consistent with a text prompt. They are the engine behind modern text-to-image systems and behave very differently from the autoregressive next-token generation of text LLMs.

#### Retrieval-augmented generation (RAG)
RAG grounds an LLM's output by retrieving relevant documents from an external knowledge source at query time and feeding them into the prompt as context. This reduces hallucination and lets a model cite current or proprietary information it was never trained on — the architecture behind most "chat with your documents" tools.

### Assigned readings

#### Reading 1 · Chain-of-Thought Prompting Elicits Reasoning in LLMs (Wei et al., 2022)

*Assigned: Abstract, Section 1, Section 2, and Figure 1 · [PDF](https://proceedings.neurips.cc/paper_files/paper/2022/file/9d5609613524ecf4f15af0f7b31abca4-Paper-Conference.pdf)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![Guide to Chain-of-Thought Prompting](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Guide_to_Chain-of-Thought_Prompting.png)
</details>

This Google Research paper introduced chain-of-thought prompting and showed that simply prompting a large model to "think step by step" — by including a few exemplars that spell out intermediate reasoning — dramatically improves performance on arithmetic, commonsense, and symbolic reasoning tasks. The headline finding is that this reasoning ability is *emergent*: it barely helps small models but produces large gains once models pass roughly 100B parameters, so scale and technique interact. The authors demonstrate state-of-the-art results on benchmarks like GSM8K math word problems using only prompting — no fine-tuning or task-specific training. The paper's importance for the course is conceptual as much as practical: it reframes prompting from a formatting trick into a way of eliciting latent capabilities, and it explains *why* the CoT technique participants apply in the prompt-engineering lab actually works. *Why it mattered for the course:* it is the empirical foundation for deliberate, structured prompting.

#### Reading 2 · Survey of Hallucination in Natural Language Generation (Ji et al., 2023)

*Assigned: Abstract, Section 1, and Section 2 · [PDF/HTML](https://dl.acm.org/doi/full/10.1145/3571730)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![Guide to Large Model Hallucinations](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Guide_to_Large_Model_Hallucinations.png)
</details>

This ACM Computing Surveys paper is the definitive academic taxonomy of hallucination in natural language generation. It defines hallucination as generated content that is unfaithful to or unsupported by the source input, and separates it into **intrinsic** hallucination (output that contradicts the source) and **extrinsic** hallucination (output that cannot be verified against the source — neither supported nor contradicted). The survey traces contributing causes across the whole pipeline — from noisy or biased training data to decoding strategies that favor fluency over faithfulness — and reviews metrics and mitigation methods across tasks like summarization, dialogue, and translation. For AI Champions the value is operational: knowing the *types* of hallucination lets you audit AI outputs systematically rather than impressionistically, checking specifically for fabricated facts, invented citations, and false temporal or relational claims. *Why it mattered for the course:* it converts a vague worry into a repeatable quality-control checklist.

---

## Module 3 — AI for Productivity

**Practical integration in academic work.** Module 3 grounds AI use in evidence: what the best experiments actually show about productivity gains, where AI helps versus hurts, and how to document and disclose AI-assisted work responsibly.

![AI for Productivity — Technology Guide](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/AI_Productivity_Technology_Guide.png)

### Learning objectives

1. Audit five recurring professional tasks for AI integration potential using a structured multi-dimensional matrix.
2. Complete one real work task using AI with full documentation of prompts, outputs, edits, time, and quality.
3. Apply a disclosure reasoning framework to four academic-integrity scenarios using institutional policy references.
4. Design a personal AI workflow with input classification, prompt strategy, verification checkpoint, and disclosure decision.
5. Interpret the Noy & Zhang (2023) and Dell'Acqua et al. (2023) findings in the context of my own workflow.

### Key topics

#### The jagged technological frontier
AI's capabilities form a *jagged* frontier, not a smooth one: tasks of similar apparent difficulty can fall on opposite sides of what current models do well. Inside the frontier, AI assistance sharply boosts quality and speed; just outside it, the same assistance can *degrade* performance because the model produces confident but wrong output that users accept. The practical lesson is to learn where the frontier lies for your own tasks rather than assuming uniform helpfulness.

#### Centaurs, cyborgs, and self-automators
A supplementary reading distinguishes modes of human-AI collaboration: **centaurs** divide labor cleanly between human and machine (each doing what it's best at), while **cyborgs** interweave the two continuously within a task. A later framing adds **self-automators**, who delegate whole tasks. The distinctions matter for skilling and for preserving human expertise as AI takes on more.

#### Academic integrity and disclosure
The module treats disclosure as a reasoning process, not a rule to memorize: when should AI assistance be acknowledged, to whom, and in what form? Participants apply a disclosure framework to concrete scenarios (drafting, editing, analysis, ideation), weighing institutional policy, the nature of the contribution, and the expectations of the audience.

#### Designing a personal AI workflow
A well-designed workflow for a recurring task specifies four things: **input classification** (is this task inside or outside the frontier?), a **prompt strategy**, a **verification checkpoint** (how the output is checked before use), and a **disclosure decision**. This turns ad-hoc AI use into a repeatable, auditable process.

### Assigned readings

#### Reading 1 · Experimental Evidence on the Productivity Effects of Generative AI (Noy & Zhang, 2023)

*Assigned: Full paper · ~20 min · [PDF](https://economics.mit.edu/sites/default/files/inline-files/Noy_Zhang_1_0.pdf)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![AI Productivity Study Summary Notes](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/AI_Productivity_Study_Summary_Notes.png)
</details>

This MIT study (published in *Science*) is the highest-quality experimental evidence on AI's effect on professional writing. In a randomized controlled trial, 453 college-educated professionals completed realistic writing tasks; half were given access to ChatGPT. The treated group finished **37% faster** and produced work rated *higher* in quality — and, notably, the gains were largest for initially lower-performing writers, compressing the skill gap between weaker and stronger workers. The experiment also found that time was reallocated from drafting toward idea generation and editing, and that participants who used the tool reported higher job satisfaction and greater interest in using AI again. Because it is a controlled experiment rather than a survey or anecdote, it anchors the module's claims about productivity in causal evidence. *Why it mattered for the course:* it is the empirical benchmark against which participants interpret their own documented workflow experiments.

#### Reading 2 · Navigating the Jagged Technological Frontier (Dell'Acqua et al., 2023)

*Assigned: Abstract, Sections 1, 2, 4, and 6 (~20 pages) · ~25 min · [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4573321)*

<details>
<summary><b>Course content graphics (NotebookLM infographics)</b></summary>

![Navigating the Jagged AI Frontier](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Navigating_the_Jagged_AI_Frontier.png)

![Guide to Human-AI Co-Creation](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Guide_to_Human-AI_Co-Creation.png)
</details>

This Harvard Business School field experiment, run with 758 Boston Consulting Group consultants, produced the module's central mental model: the **jagged technological frontier**. For tasks *inside* AI's capability frontier, consultants using GPT-4 completed about 12% more tasks, roughly 25% faster, with quality more than 40% higher than the control group — and, as in Noy & Zhang, the boost was largest for lower-performing consultants. But for a carefully designed task *outside* the frontier — one where the AI gave plausible but wrong guidance — AI-assisted consultants were **19 percentage points more likely to reach the wrong answer**, because they deferred to confident but flawed output. The paper also surfaces the *centaur* and *cyborg* patterns of the most effective users. Its lesson is precisely why the frontier is "jagged, not smooth": the boundary is invisible and doesn't track human intuitions about difficulty, so over-reliance is dangerous exactly where it feels safe. *Why it mattered for the course:* it is the most operationally useful framework for deciding *when* to trust AI assistance.

---

## Module 4 — Critical Thinking About AI

**Bias, fairness, and epistemic limits.** Module 4 develops the analytical muscle to trace AI harms to their sources — in data, design, or deployment — and to engage seriously with the strongest critiques of large language models.

![Critical Thinking About AI — Fairness](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Critical_Thinking_About_AI_Fairness.png)

### Learning objectives

1. Analyze two landmark bias cases using a structured four-section form, tracing each bias to its origin in data, design, or deployment.
2. Distinguish among at least four types of algorithmic bias — historical, representation, measurement, and aggregation — with higher-education examples.
3. Design and execute a 10-prompt bias audit of an AI tool relevant to my professional context.
4. Critically annotate Bender et al. (2021), identifying three compelling arguments and one well-reasoned counter-argument.
5. Apply a fairness evaluation framework to an AI-generated output from my own prior work.

### Key topics

#### Types of algorithmic bias
The module separates bias by where it enters the pipeline: **historical bias** (the world's existing inequities are captured in the data), **representation bias** (some groups are under-sampled), **measurement bias** (proxies and labels distort what's actually measured), and **aggregation bias** (one model applied to distinct groups fits none of them well). Naming the type points to the right remedy.

#### Intersectional bias
Intersectional analysis measures performance at the *intersection* of attributes (e.g., darker-skinned women) rather than one axis at a time — revealing disparities that single-axis reporting hides. This is the analytical core of the *Gender Shades* study.

#### The stochastic parrot critique
The "stochastic parrot" argument holds that an LLM stitches together linguistic forms it has observed, "haphazardly" and without reference to meaning — coherent-seeming text produced without genuine comprehension. The course treats engaging with this argument on its merits (rather than accepting or dismissing it wholesale) as a core AI-Champion skill.

#### Fairness evaluation frameworks
Participants apply a structured fairness framework to a real AI output, asking who could be harmed, which groups the system performs unevenly across, what the appropriate fairness criterion is for the context, and what remediation would look like — moving from "this feels biased" to a documented assessment.

### Assigned readings

#### Reading 1 · Gender Shades (Buolamwini & Gebru, 2018)

*Assigned: Full paper (15 pages) — read Methods §3.4 before Results · ~35 min · [PDF](https://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![Intersectional AI Bias Revision Notes](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Intersectional_AI_Bias_Revision_Notes.png)
</details>

*Gender Shades* is the single most cited empirical demonstration of intersectional bias in a commercial AI system. Buolamwini and Gebru built a new, phenotypically balanced benchmark of faces (labeled by Fitzpatrick skin type) and evaluated three commercial gender-classification products from IBM, Microsoft, and Face++. They found accuracy was consistently worst for darker-skinned women and best for lighter-skinned men — an **accuracy gap of up to 34.7 percentage points** between those two groups. The study's power comes from its method: by disaggregating results along intersecting attributes rather than reporting a single overall accuracy, it exposed disparities that aggregate metrics concealed entirely. It walks through the full analytical pipeline the module teaches — measurement design, finding, causal attribution, and remediation — and it had real-world consequences, prompting the vendors to revise their systems. *Why it mattered for the course:* it is the archetype of rigorous, consequential bias analysis.

#### Reading 2 · On the Dangers of Stochastic Parrots (Bender et al., 2021)

*Assigned: Abstract, Section 1, Section 5, and Section 6 · [PDF](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922)*

<details>
<summary><b>Course content graphics (NotebookLM infographics)</b></summary>

![Stochastic Parrots AI Research Critique](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Stochastic_Parrots_AI_Research_Critique.png)

![LLM Harms Taxonomy Revision Notes](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/LLM_Harms_Taxonomy_Revision_Notes.png)
</details>

This FAccT paper is the most influential critical analysis of large language models to date. Its central metaphor — the *stochastic parrot* — argues that an LLM is "a system for haphazardly stitching together sequences of linguistic forms… according to probabilistic information about how they combine, but without any reference to meaning." From this the authors build a multi-pronged case against ever-larger models: escalating **environmental and financial costs** that fall hardest on marginalized communities; training data so large it is **undocumented and unauditable**, encoding and amplifying bias; the risk that fluent, human-seeming text is mistaken for genuine understanding and used to mislead; and the opportunity cost of a research agenda fixated on scale. The course asks participants to identify the paper's strongest arguments *and* a well-reasoned counter-argument — practicing exactly the critical engagement (neither uncritical acceptance nor reflexive dismissal) that defines an AI Champion. *Why it mattered for the course:* it models how to hold rigorous, good-faith skepticism about tools you also use. (The paper is famous partly for the controversy around its publication, which itself illustrates the stakes of AI critique inside industry.)

---

## Module 5 — AI Governance

**Policy and responsible use at the university.** Module 5 gives participants the vocabulary and frameworks to evaluate institutional AI policy — and to draft their own — using the two dominant governance instruments.

![AI Governance — Student Revision Notes](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/AI_Governance_Student_Revision_Notes.png)

### Learning objectives

1. Evaluate three peer-institution AI policies using a six-dimension rubric, identifying the strongest provision and the most common gap.
2. Apply NIST AI RMF and UNESCO principles to at least three specific scenarios in my institutional context.
3. Formulate a 300-word evidence-grounded position on a contested AI policy question, rebutting the strongest counterargument.
4. Draft a practical 150–200 word AI Acceptable Use Guideline for my specific unit, team, or course.
5. Distinguish principles-based from rules-based governance and assess the trade-offs of each for higher education.

### Key topics

#### The NIST AI Risk Management Framework
The NIST AI RMF organizes AI risk management into four functions: **GOVERN** (cultivate a culture and structure for managing risk), **MAP** (establish context and identify risks), **MEASURE** (analyze and track risks), and **MANAGE** (prioritize and act on them). Learning the four-function structure gives you a lens for spotting when an institutional policy covers only some functions — say, rules for use (MANAGE) with no governance culture (GOVERN) behind them.

#### The UNESCO Recommendation on AI Ethics
Where NIST is operational and sector-neutral, UNESCO grounds AI governance in **human rights**, and addresses cross-border, equity, and environmental dimensions NIST leaves out. Adopted by all 193 member states in 2021, it was the first global normative instrument on AI ethics. The two frameworks are complementary: one procedural, one values-based.

#### Principles-based vs. rules-based governance
*Rules-based* governance specifies concrete permitted and prohibited actions — clear but brittle and quickly outdated. *Principles-based* governance sets high-level values and requires judgment to apply — flexible and durable but harder to enforce consistently. The module weighs the trade-offs of each for the fast-moving, heterogeneous environment of a university.

### Assigned readings

#### Reading 1 · NIST AI Risk Management Framework (AI RMF 1.0) (2023)

*Assigned: AI RMF Core (GOVERN / MAP / MEASURE / MANAGE), Fig 5 §5, pp. 20–21 · ~20 min · [PDF](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf) · [Online Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![AI Risk Management Revision Notes](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/AI_Risk_Management_Revision_Notes.png)
</details>

The NIST AI RMF is the primary U.S. federal framework for organizational AI risk management — voluntary, sector-neutral, and explicitly designed to be adaptable to organizations like universities. Its heart is the **Core**, four functions that structure the entire risk lifecycle: **GOVERN** (a cross-cutting culture of risk management, policies, and accountability that runs through everything), **MAP** (understand the context and intended use, and surface the risks and impacts of a given AI system), **MEASURE** (use quantitative and qualitative methods to assess and monitor those risks, including trustworthiness characteristics like validity, safety, fairness, and transparency), and **MANAGE** (prioritize risks and act — allocating resources, responding, and recovering). The framework also defines the characteristics of *trustworthy AI* that these functions serve. For AI Champions its value is diagnostic: the four-function vocabulary lets you read any institutional AI policy and pinpoint what it addresses and what it silently omits. *Why it mattered for the course:* it is the backbone of the module's policy-analysis rubric.

#### Reading 2 · UNESCO Recommendation on the Ethics of AI (2021)

*Assigned: Preamble (3 pages) + Section III Values and Principles, pp. 18–23 (recommended) · ~20 min · [Document](https://unesdoc.unesco.org/ark:/48223/pf0000381137)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![UNESCO AI Ethics Revision Notes](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/UNESCO_AI_Ethics_Revision_Notes.png)
</details>

The UNESCO Recommendation is the first global normative instrument on AI ethics, adopted by all 193 member states in November 2021. Unlike the operational, sector-neutral NIST framework, it grounds AI governance in **human rights and human dignity**, and foregrounds dimensions NIST largely omits: cross-border cooperation, equity between and within nations, environmental and ecosystem impact, and the protection of cultural diversity. It sets out core values (human rights, environmental flourishing, diversity and inclusiveness, peaceful societies) and actionable principles (proportionality and do-no-harm, safety and security, fairness and non-discrimination, sustainability, privacy, human oversight, transparency and explainability, accountability). It also translates these into policy-action areas covering data governance, education, and the environment. Reading it alongside NIST gives participants two complementary lenses — a procedural risk framework and a values-based rights framework — for evaluating and drafting institutional policy. *Why it mattered for the course:* it supplies the ethical and human-rights vocabulary that a purely operational framework cannot.

---

## Module 6 — Becoming an AI Campus Champion

**Design, leadership, and action — the capstone.** The final module synthesizes everything into an original AI adoption initiative: a concrete plan the participant will lead in their own unit, communicated to stakeholders and designed to sustain itself.

![Becoming an AI Campus Champion](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Becoming_an_AI_Campus_Champion.png)

### Learning objectives

1. Design an original AI adoption initiative using a seven-section canvas, grounded in evidence from across the workshop.
2. Produce a professional stakeholder communication introducing the initiative to a skeptical but open-minded colleague.
3. Provide structured, evidence-grounded peer review of a peer's initiative design using a four-dimension rubric.
4. Formulate a specific, achievable 90-day action plan with named collaborators, milestones, and barrier-response strategies.
5. Revise my Module 1 concept map to document my learning trajectory across the full six-week workshop.

### Key topics

#### Communities of practice
A community of practice (CoP) is a group that deepens its knowledge and expertise through sustained interaction. The framework identifies three structural elements — **domain** (the shared area of concern), **community** (the relationships and mutual engagement), and **practice** (the shared repertoire of tools, cases, and methods). Designing an initiative around all three is what lets it outlast the initial burst of enthusiasm.

#### Bloom's revised taxonomy
Bloom's Revised Taxonomy arranges cognitive processes from lower to higher order — **Remember → Understand → Apply → Analyze → Evaluate → Create** — across a second "knowledge" dimension (factual, conceptual, procedural, metacognitive). The entire six-week program is built on this spine, from *Remember* in Module 1 to *Create* here in Module 6; reading the framework lets participants design AI-literacy experiences for colleagues and articulate *why* the module sequence is ordered as it is.

#### The AI adoption initiative canvas
The capstone is organized as a seven-section canvas — problem statement, stakeholders, evidence base, proposed intervention, success metrics, risks/ethics, and sustainability plan — that forces the participant to connect a concrete institutional problem to the evidence, ethics, and governance ideas from Modules 1–5.

### Assigned readings

#### Reading 1 · Cultivating Communities of Practice (Wenger, McDermott & Snyder, 2002)

*Assigned: Chapter 1 excerpt — definition, three structural elements, and why CoPs transfer knowledge · ~20 min · [PDF](https://facilitateadultlearning.pbworks.com/f/7Principles_CoP.pdf)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![Communities of Practice Cultivation Principles](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Communities_of_Practice_Cultivation_Principles.png)
</details>

Wenger, McDermott, and Snyder's book is the foundational management text on **communities of practice** — groups of people who share a concern and deepen their expertise by interacting regularly. The assigned excerpt defines a CoP through its three structural elements: the **domain** (the shared area of interest that gives the community identity and purpose), the **community** (the members, their relationships, and their mutual engagement and trust), and the **practice** (the shared body of knowledge, tools, stories, and methods the community develops over time). The authors argue CoPs are uniquely effective vehicles for transferring tacit knowledge — the kind that resists being written down — which is exactly what spreading responsible AI practice across a campus requires. The companion "seven principles for cultivating communities of practice" (design for evolution, open a dialogue between inside and outside perspectives, invite different levels of participation, and so on) gives participants a practical design toolkit. *Why it mattered for the course:* it is the blueprint for making an AI Champion initiative durable rather than a one-off event.

#### Reading 2 · A Revision of Bloom's Taxonomy (Krathwohl, 2002)

*Assigned: The Taxonomy Table · ~15 min · [PDF](https://www.ou.edu/content/dam/assessment/docs/Theory%20Into%20Practice.pdf)*

<details>
<summary><b>Course content graphic (NotebookLM infographic)</b></summary>

![Mastering the 2D Learning Matrix](https://raw.githubusercontent.com/UA-AI2S/AI-Champions/main/images/Mastering_the_2D_Learning_Matrix.png)
</details>

Krathwohl's article gives a concise overview of the 2001 revision of Bloom's classic taxonomy of educational objectives. The revision reframes the original single hierarchy into a **two-dimensional matrix**. The *cognitive process* dimension runs from lower to higher order — Remember, Understand, Apply, Analyze, Evaluate, Create (the revision renames the categories as verbs and, notably, moves *Create* above *Evaluate* at the top) — while the *knowledge* dimension distinguishes factual, conceptual, procedural, and **metacognitive** knowledge (the last being new to the revision). Any learning objective can be located in a cell of this grid, which makes objectives, activities, and assessments easier to align. The reading matters here because the whole workshop was *designed* on this spine, marching from Remember (Module 1) to Create (Module 6); understanding the framework lets participants build AI-literacy learning experiences for their own colleagues and articulate the pedagogical logic behind them. *Why it mattered for the course:* it hands participants the design language to become teachers, not just users, of AI literacy.

---

## Complete Reading List

| Module | Reading | Authors (Year) |
|---|---|---|
| 1 | [On the Opportunities and Risks of Foundation Models](https://arxiv.org/pdf/2108.07258) | Bommasani et al. (2021) |
| 1 | [Stanford HAI AI Index 2025 — Executive Summary](https://hai.stanford.edu/assets/files/hai_ai_index_report_2025.pdf) | Maslej et al. (2025) |
| 2 | [Chain-of-Thought Prompting Elicits Reasoning in LLMs](https://proceedings.neurips.cc/paper_files/paper/2022/file/9d5609613524ecf4f15af0f7b31abca4-Paper-Conference.pdf) | Wei et al. (2022) |
| 2 | [Survey of Hallucination in Natural Language Generation](https://dl.acm.org/doi/full/10.1145/3571730) | Ji et al. (2023) |
| 3 | [Experimental Evidence on the Productivity Effects of Generative AI](https://economics.mit.edu/sites/default/files/inline-files/Noy_Zhang_1_0.pdf) | Noy & Zhang (2023) |
| 3 | [Navigating the Jagged Technological Frontier](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4573321) | Dell'Acqua et al. (2023) |
| 4 | [Gender Shades](https://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf) | Buolamwini & Gebru (2018) |
| 4 | [On the Dangers of Stochastic Parrots](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922) | Bender et al. (2021) |
| 5 | [NIST AI Risk Management Framework (AI RMF 1.0)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf) | NIST (2023) |
| 5 | [UNESCO Recommendation on the Ethics of AI](https://unesdoc.unesco.org/ark:/48223/pf0000381137) | UNESCO (2021) |
| 6 | [Cultivating Communities of Practice](https://facilitateadultlearning.pbworks.com/f/7Principles_CoP.pdf) | Wenger, McDermott & Snyder (2002) |
| 6 | [A Revision of Bloom's Taxonomy](https://www.ou.edu/content/dam/assessment/docs/Theory%20Into%20Practice.pdf) | Krathwohl (2002) |

---

## Credits & License

Course content, module structure, and all content graphics are from the **[AI Campus Champions program](https://github.com/UA-AI2S/AI-Champions/wiki)** created by **Carlos Lizárraga** for the [Arizona Institute for Artificial Intelligence (AI2S)](https://responsibleai.arizona.edu/ai2s) and the [Office of Responsible AI (ORAI)](https://responsibleai.arizona.edu/), University of Arizona, 2026. Graphics are embedded from the [course repository](https://github.com/UA-AI2S/AI-Champions).

The original course materials are released under a **Creative Commons BY-NC-SA** license. This summary was prepared as a personal study record of my participation in the program.
