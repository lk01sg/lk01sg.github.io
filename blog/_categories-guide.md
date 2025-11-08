---
title: "Categories"
subtitle: "Guide to blog content organization"
page-layout: full
title-block-banner: true
---

This blog uses a simple, practical tagging system to organize research documentation. Posts typically use 2-4 tags that describe the content type, technical focus, and research domain.

---

## Research Process

Tags for documenting the research workflow and progress.

**`progress`**  
Weekly updates, project milestones, and overall research progress. Use this for regular check-ins and status reports.

*Example: "Week 5: Network Analysis Pipeline Complete"*

**`project`**  
Project-specific work and documentation. Use when focusing on a particular research project or initiative.

*Example: "Immune Network Analysis: Project Overview"*

**`methods`**  
Method implementations, technique explanations, and procedural documentation. Use when describing HOW you do something.

*Example: "Implementing Louvain Clustering for Cell Communities"*

**`debugging`**  
Problem-solving stories, error resolution, and troubleshooting documentation. Use when documenting challenges and their solutions.

*Example: "Solving Scanpy Memory Errors with Large Datasets"*

---

## Knowledge Building

Tags for learning, synthesis, and theoretical exploration.

**`literature`**  
Paper summaries, literature reviews, and reading notes. Use when engaging with published research.

*Example: "Paper Notes: AlphaFold2 Applications in Drug Discovery"*

**`learning`**  
New concepts, tutorials, and skill development. Use when documenting learning process or creating educational content.

*Example: "Learning JAX for Differentiable Programming in Biology"*

**`theory`**  
Theoretical frameworks, conceptual models, and foundational concepts. Use for deeper conceptual explorations.

*Example: "Understanding Network Centrality in Drug Target Identification"*

---

## Technical

Tags for computational and technical content.

**`code`**  
Code examples, scripts, and programming solutions. Use when sharing executable code or implementation details.

*Example: "Python Script: Automated Network Visualization Pipeline"*

**`data-analysis`**  
Data analysis workflows, statistical methods, and analytical approaches. Use for analysis-focused content.

*Example: "Exploratory Data Analysis: scRNA-seq Drug Response Data"*

**`tools`**  
Software reviews, package tutorials, and tool comparisons. Use when discussing research tools and infrastructure.

*Example: "Comparing NetworkX vs igraph for Biological Networks"*

---

## Research Domains

Tags for specific scientific areas and topics.

**`systems-biology`**  
Network analysis, systems modeling, pathway analysis, and integrative approaches. Use for systems-level research.

*Example: "Modeling Immune Cell Interaction Networks"*

**`immunology`**  
Immune system research, immunological mechanisms, and immune-related projects. Use for immunology-focused work.

*Example: "T-cell Network Topology in Drug Response"*

**`pharmacology`**  
Drug discovery, drug-target interactions, and pharmacological research. Use for drug-related content.

*Example: "Network Pharmacology Approach to Polypharmacology"*

**`pk-pd`**  
Pharmacokinetics, pharmacodynamics, PKPD modeling, and dose-response analysis.

*Example: "Implementing Population PKPD Models in R"*

**`drug-discovery`**  
Drug design, target identification, lead optimization, and discovery pipelines.

*Example: "AI-Driven Drug Target Prioritization Pipeline"*

**`bioai`**  
Machine learning for biology, protein structure prediction, and AI applications in life sciences.

*Example: "Fine-tuning ESM2 for Protein Function Prediction"*

**`computational`**  
General computational biology, bioinformatics, and computational methods not specific to above domains.

*Example: "Optimizing Python Code for Large-Scale Biological Simulations"*

---

## Meta

Tags for blog-related and personal content.

**`meta`**  
Posts about the blog itself, open science practices, and knowledge management approaches.

*Example: "Starting an Open Lab Notebook: Why and How"*

**`reflection`**  
Personal insights, research reflections, and philosophical musings about science and research.

*Example: "Reflections on Reproducibility in Computational Biology"*

**`career`**  
PhD journey, academic development, professional growth, and career-related content.

*Example: "PhD Application Process: What I'm Learning"*

---

## Tagging Guidelines

### How Many Tags?

**Use 2-4 tags per post** for optimal organization:

- ✅ **Good:** `[progress, immunology, code]` — Clear and specific
- ⚠️ **Okay:** `[methods, data-analysis, systems-biology, code, learning]` — A bit much, but acceptable
- ❌ **Too many:** 6+ tags dilute meaning and make filtering less useful

### Tag Selection Strategy

**1. Start with content type** (Research Process or Knowledge Building):
- Is it a progress update? → `progress`
- Learning something new? → `learning`
- Reviewing literature? → `literature`

**2. Add technical dimension if relevant:**
- Sharing code? → `code`
- Data analysis workflow? → `data-analysis`
- Tool-focused? → `tools`

**3. Add domain tag(s):**
- Network analysis? → `systems-biology`
- Immune system? → `immunology`
- Drug-related? → `pharmacology`

**4. Add meta tag if appropriate:**
- Personal reflection? → `reflection`
- About PhD journey? → `career`

### Examples

**Example 1: Weekly Progress Post**
```yaml
categories: [progress, immunology, data-analysis]
```
*Rationale: Weekly update (progress) on immune project (immunology) involving data work (data-analysis)*

**Example 2: Problem-Solving Post**
```yaml
categories: [debugging, code, tools]
```
*Rationale: Solved a bug (debugging) with code solution (code) involving specific tools (tools)*

**Example 3: Paper Summary**
```yaml
categories: [literature, systems-biology, drug-discovery]
```
*Rationale: Paper notes (literature) about systems approaches (systems-biology) in drug discovery context (drug-discovery)*

**Example 4: Method Tutorial**
```yaml
categories: [learning, methods, code, computational]
```
*Rationale: Learning new method (learning, methods) with code implementation (code) in computational context (computational)*

---

## Browse by Category

Use the category filter on the [home page](blog.qmd) to browse posts by tag, or explore the [archive](archive.qmd) for a complete chronological view.

---

**Questions about tagging?** Feel free to reach out on [Mastodon](https://genomic.social/@lk01sg).