<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="assets/static/hero.svg">
  <img src="assets/hero.svg" width="1200" alt="Saif Shahzad — Less noise. More signal. Data science and applied AI, from research to real-world tools.">
</picture>

<p align="center">
  <a href="#selected-work">Selected work</a> &nbsp; / &nbsp;
  <a href="#how-i-work">How I work</a> &nbsp; / &nbsp;
  <a href="#tech-stack">Tech stack</a> &nbsp; / &nbsp;
  <a href="mailto:saifshahzad901@gmail.com?subject=Project%20inquiry%20from%20GitHub">Start a conversation ↗</a>
</p>

# I'm Saif. I turn complex data into useful tools.

**Data Science @ FAST-NUCES, Islamabad · Applied AI · Machine Learning**

I like the space where a good experiment becomes something someone can use. My work spans document intelligence, custom transformers, explainable machine learning, and temporal graph research, with interfaces that make the results easier to inspect.

**Have documents to process, patterns to uncover, or an AI idea to test?** Let's turn the problem into a clear first experiment, then build from the evidence.

**[Discuss a project ↗](mailto:saifshahzad901@gmail.com?subject=Project%20inquiry%20from%20GitHub)** &nbsp; · &nbsp; [Try my live application](https://invoice-intelligence-theta.vercel.app/) &nbsp; · &nbsp; [Explore my repositories](https://github.com/Saif1Shahzad?tab=repositories)

<br>

## Selected work

Four ways I explore the distance between raw data and a useful decision.

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Saif1Shahzad/invoice-intelligence"><picture><source media="(prefers-reduced-motion: reduce)" srcset="assets/static/project-invoice.svg"><img src="assets/project-invoice.svg" width="600" alt="01 — Invoice Intelligence. Applied AI, live pilot. OCR, LLM extraction, and human review."></picture></a>

### Invoice Intelligence

**From a document to a record you can verify.**

PDFs, scans, and receipts become structured data through OCR and AI extraction. Source evidence, validation checks, human confirmation, and Excel exports complete the workflow.

<sub>Python · FastAPI · React · TypeScript · PostgreSQL</sub>

**[Try the live pilot ↗](https://invoice-intelligence-theta.vercel.app/)** &nbsp; · &nbsp; [Read the code](https://github.com/Saif1Shahzad/invoice-intelligence)

</td>
<td width="50%" valign="top">

<a href="https://github.com/Saif1Shahzad/AI-Review-Analysis-with-Custom-Transformers-and-RAG"><picture><source media="(prefers-reduced-motion: reduce)" srcset="assets/static/project-transformers.svg"><img src="assets/project-transformers.svg" width="600" alt="02 — Reviews, understood. Custom transformers, retrieval, and ablation experiments."></picture></a>

### Review Understanding + RAG

**What does a review say, and what supports the explanation?**

A custom transformer encoder learns review labels and embeddings. Retrieval finds related examples; a decoder generates explanations. A RAG versus no-RAG ablation examines the contribution of retrieval.

<sub>PyTorch · Custom transformers · Embeddings · Retrieval</sub>

**[Explore the experiment ↗](https://github.com/Saif1Shahzad/AI-Review-Analysis-with-Custom-Transformers-and-RAG)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Saif1Shahzad/dmt-gnn-aml"><picture><source media="(prefers-reduced-motion: reduce)" srcset="assets/static/project-graph.svg"><img src="assets/project-graph.svg" width="600" alt="03 — Follow the transfers. Temporal graph learning for anti-money-laundering research, in progress."></picture></a>

### Temporal Graph Learning for AML

**Follow the transfers. Preserve the sequence.**

Research on directed multigraphs, temporal attention, and recurrent memory for financial transaction analysis. Streaming replay studies the trade-off between information freshness and detection quality.

<sub>PyTorch · Temporal GNNs · Streaming replay · Reproducibility</sub>

**[Inspect the research ↗](https://github.com/Saif1Shahzad/dmt-gnn-aml)**

<sub>In progress: pipeline verified on synthetic fixtures; full benchmark evaluation pending. Joint research with Shahoud Shahid.</sub>

</td>
<td width="50%" valign="top">

<a href="https://github.com/Saif1Shahzad/cardioai-heart-disease-prediction"><picture><source media="(prefers-reduced-motion: reduce)" srcset="assets/static/project-cardio.svg"><img src="assets/project-cardio.svg" width="600" alt="04 — Look beyond the prediction. Educational machine learning study with XGBoost, SHAP, and model comparison."></picture></a>

### CardioAI

**A prediction is a starting point for understanding.**

An educational heart disease modeling study connecting data preparation, classifier comparisons, SHAP analysis, and a Streamlit dashboard prototype. Includes clustering and separate neural network experiments.

<sub>scikit-learn · XGBoost · SHAP · Streamlit</sub>

**[Explore the analysis ↗](https://github.com/Saif1Shahzad/cardioai-heart-disease-prediction)**

<sub>Educational portfolio prototype.</sub>

</td>
</tr>
</table>

<details>
<summary><strong>A few more threads worth pulling ↗</strong></summary>

<br>

- **[Urdu NLP](https://github.com/Saif1Shahzad/Urdu-NLP-Pipeline-Word-Embeddings-NER-and-Text-Classification)** — Word embeddings, BiLSTM sequence labeling, named entity recognition, and transformer classification.
- **[From Clicks to Loyalty](https://github.com/Saif1Shahzad/clicks-to-loyalty-data-mining)** — Customer intelligence through FP-Growth, RFM segmentation, and sequential pattern mining.
- **[Pulse to Prediction](https://github.com/Saif1Shahzad/pulse-to-prediction)** — Patient-vitals time series, dynamic time warping similarity search, and diagnosis classification.

</details>

<br>

## How I work

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="assets/static/approach.svg">
  <img src="assets/approach.svg" width="1200" alt="Understand the decision and data → Experiment with baselines and honest evaluation → Build a usable, inspectable tool → Refine through feedback.">
</picture>

**Start with the decision.** What needs to become easier, clearer, or faster? That question shapes the data, the model, and the interface.

**Make the evidence inspectable.** I care about baselines, explanations, and the difference between a promising prototype and a verified result. You can see that in the source-linked invoice review, retrieval ablations, and documented research protocols above.

**Connect the pieces.** Data preparation, modeling, APIs, and interfaces belong to the same conversation. The goal is a tool someone can understand and use.

<details>
<summary><strong>The small details that make a tool worth trusting ↗</strong></summary>

<br>

- **Evidence beside the answer.** In [Invoice Intelligence](https://github.com/Saif1Shahzad/invoice-intelligence), extracted fields link back to their source. A person confirms the record before export.
- **The second click matters, too.** The invoice workflow accounts for repeated uploads, duplicate findings, and stale edits, so retries and concurrent work have explicit handling.
- **Time is part of the data.** In [DMT-GNN AML](https://github.com/Saif1Shahzad/dmt-gnn-aml), an event is scored before it updates memory. Histories exclude future events; preprocessing uses training data.
- **A result needs its context.** The [review understanding experiment](https://github.com/Saif1Shahzad/AI-Review-Analysis-with-Custom-Transformers-and-RAG) compares RAG with no RAG. Research progress, completed checks, and pending evaluation are documented separately.

</details>

<br>

## Tech stack

From the first notebook to the API, interface, and deployment.

<picture>
  <source media="(max-width: 600px)" srcset="assets/tech-stack-mobile.svg">
  <img src="assets/tech-stack.svg" width="1200" alt="My tech stack: Python, PyTorch, scikit-learn, pandas, NumPy, FastAPI, React, TypeScript, PostgreSQL, Streamlit, Git, and GitHub Actions.">
</picture>

| Focus | Tools and methods I've used |
| :--- | :--- |
| **Data & modeling** | [Python](https://www.python.org/) · [pandas](https://pandas.pydata.org/) · [NumPy](https://numpy.org/) · [scikit-learn](https://scikit-learn.org/) · XGBoost · [PyTorch](https://pytorch.org/) |
| **Language & intelligence** | Transformers · RAG · Embeddings · OCR · LLM APIs · SHAP |
| **Applications & delivery** | [FastAPI](https://fastapi.tiangolo.com/) · [React](https://react.dev/) · [TypeScript](https://www.typescriptlang.org/) · [Streamlit](https://streamlit.io/) · [PostgreSQL](https://www.postgresql.org/) · Vercel |
| **Experiments & verification** | Jupyter · Model comparisons · Ablation studies · Regression tests · [GitHub Actions](https://github.com/features/actions) |

<br>

## Let's build something useful

I'm open to **project work, research collaborations, and building with people who care about the details.**

Bring me a document workflow that needs less manual work, a dataset with an unanswered question, or an AI idea that needs a prototype. Tell me **what you're trying to achieve, what you have so far, and your timeline**. That's enough to start.

<a href="mailto:saifshahzad901@gmail.com?subject=Project%20inquiry%20from%20GitHub"><picture><source media="(prefers-reduced-motion: reduce)" srcset="assets/static/contact.svg"><img src="assets/contact.svg" width="1200" alt="Have a hard problem? Let's make it useful. Email Saif Shahzad at saifshahzad901@gmail.com."></picture></a>

<p align="center">
  <strong><a href="mailto:saifshahzad901@gmail.com?subject=Project%20inquiry%20from%20GitHub">saifshahzad901@gmail.com</a></strong>
  <br>
  <sub>Based in Islamabad, Pakistan · Open to remote collaboration</sub>
</p>
