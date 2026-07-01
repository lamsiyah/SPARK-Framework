# SPARK: Student-Centered NLP Pedagogy in the Age of LLMs

This repository accompanies the **SPARK framework**: **Scaffolded, Participatory, Active, Reflective Knowledge-building**. SPARK is a student-centered framework for teaching Natural Language Processing (NLP) in the age of large language models (LLMs).

The repository is connected to the AIED 2026 paper:

> **SPARK: A Student-Centered Framework for Teaching Natural Language Processing in the Age of Large Language Models**

The core problem is that many students now meet NLP through LLMs first. They can generate fluent answers, code snippets, summaries, and explanations before they understand the model, the data, the assumptions, or the evaluation. SPARK responds to this challenge by teaching students **with AI** and **about AI**, while preserving conceptual grounding, learner agency, and reflective practice.

## Why SPARK Is Needed

NLP teaching now faces a pedagogical tension:

- If we teach only classical NLP foundations, students may see them as basic or disconnected from current AI practice.
- If we jump directly to LLMs, students may learn to assemble pipelines without understanding assumptions, failure modes, grounding, or evaluation.
- The goal is not to choose between classical NLP and LLMs. The goal is to connect them.

SPARK treats foundations such as tokenization, representation, classification, and evaluation as tools for understanding modern AI systems. In this way, AI becomes a **learning partner** and an **object of inquiry**, not a shortcut around learning.

## The SPARK Framework

| Component | Meaning | Course Design Role |
| --- | --- | --- |
| **S - Scaffolded** | Learning moves from transparent models to more opaque systems. | Students build mental models before working with LLMs, RAG, and agents. |
| **P - Participatory** | Students learn through peer explanation and shared inquiry. | Student-led presentations, teamwork, and collaborative debugging redistribute responsibility for learning. |
| **A - Active** | Students learn by implementing, testing, and analyzing. | Practical notebooks, error analysis, feedback, and iteration make concepts concrete. |
| **R - Reflective** | Students justify choices and evaluate system behavior. | Assignments and projects require explanation, comparison, limitations, and revision. |
| **K - Knowledge-building** | Students build durable understanding with and about AI. | AI is used as a tool, partner, and object of critical investigation. |

## Pedagogical Foundations

SPARK is grounded in four complementary principles:

- **Social constructivism:** peer teaching, discussion, teamwork, and collaborative debugging.
- **Active learning:** guided exploration, implementation, error analysis, and feedback.
- **Project-based learning:** authentic inquiry, literature engagement, evaluation, and reflection.
- **Psychological safety:** low-pressure participation, safe-to-fail activities, and inclusive classroom dynamics.

A key design principle is that **what gets graded becomes what students optimize for**. The course therefore rewards not only final outputs, but also the process behind them: explanation, justification, evaluation, revision, and communication.

## Course Design At A Glance

The course progresses from glass-box NLP methods to AI-rich systems:

1. NLP introduction and applications
2. Text preprocessing and tokenization
3. Sparse text representations such as TF-IDF
4. N-gram language models
5. Classical text classification
6. Logistic regression and optimization
7. Neural networks for NLP
8. Word embeddings and contextual representations
9. RNNs and Transformers
10. Large language models
11. LLM evaluation and retrieval-augmented generation
12. Agentic AI and multi-agent systems
13. Project check-ins and feedback
14. Project presentations and reflection

The assessment design balances foundations, practice, projects, and public explanation:

- **30%** final written exam
- **30%** hands-on notebooks
- **30%** final project
- **10%** seminars and participation
- Optional low-stakes bonus points for selected games and competitions

## What This Repository Will Host

This repository is intended to organize and share SPARK-related material, including:

- Course structure and lecture progression
- Teaching slides and concept explanations
- Practical notebooks
- Project briefs
- Assessment design and rubrics
- Student presentation guidance
- Examples of student projects
- Supporting resources for adapting SPARK to other AI-rich courses

## Example Student Projects

The course projects show how undergraduate students can move from foundational NLP to research-oriented AI systems when learning is properly scaffolded.

### Agentic Socratic NLP Tutor

A modular agentic tutoring system combining question generation, response analysis, and dialogue management to produce adaptive Socratic follow-up questions grounded in student responses.

Repository: https://github.com/RedPill47/Agentic_Socratic_NLP_Tutor-final

### NotAI.AI: Explainable AI-Text Detection

An AI-generated text detection system based on neural, statistical, and stylometric features, paired with explanation mechanisms that support user-facing rationale and failure analysis.

Repository: https://github.com/TenderChasm/Notai.ai

### Book Recommendation Chatbot Using RAG

A retrieval-augmented generation chatbot that retrieves relevant book information from an indexed collection and conditions responses on grounded evidence.

Repository: https://github.com/BiancaGL2104/rag-book-recommender

Demo: https://drive.google.com/file/d/1kyxr2nF-k0n8jdb8afXdE98445PFeOo-/view?usp=sharing

### Multi-Agent Resume and Cover Letter Assistant

A multi-agent workflow for information extraction, skill matching, document planning, and controlled generation of resumes and cover letters.

Demo: https://drive.google.com/file/d/19dvWKpDye3bZkp2uljUpis6uL_igrJoe/view?usp=sharing

## Evidence From The Course

Across course iterations, students demonstrated growth in:

- Technical competence in foundational and modern NLP
- Critical reasoning and model evaluation
- Research readiness
- Scientific communication
- Human-AI collaboration skills

One student group summarized the experience as follows:

> "This was the only course this semester where we attended every single session, because we always felt we were learning something meaningful."

Another student reflection captured the broader learning goal:

> "It did not just teach me NLP, it taught me how to learn and explore."

## Request Course Materials

If you are interested in using or adapting SPARK materials, please fill in the GitHub issue form:

**[Request SPARK course materials](https://github.com/lamsiyah/SPARK-Framework/issues/new?template=course-material-request.yml)**

The form asks which part of the course you are interested in, why you are interested, and how to contact you.

Privacy note: this repository is public, so information submitted through GitHub issues may be publicly visible. If you prefer to share your email privately, contact:

**Dr. Salima Lamsiyah**  
University of Luxembourg  
Email: **salima.lamsiyah@uni.lu**

## Citation

If you use this repository or adapt the SPARK framework, please cite the corresponding paper.

```bibtex
@inproceedings{lamsiyah2026spark,
  title     = {SPARK: A Student-Centered Framework for Teaching Natural Language Processing in the Age of Large Language Models},
  author    = {Lamsiyah, Salima},
  booktitle = {Proceedings of AIED 2026},
  year      = {2026}
}
```
