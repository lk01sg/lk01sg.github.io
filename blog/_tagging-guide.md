# Blog Tagging Guide
Quick reference for consistent post categorization

## Tag Decision Tree

When writing a new post, ask:

### 1. What TYPE of post is this?

**Documentation of research process:**
- Weekly/regular update → `progress`
- Specific project work → `project`  
- Method/technique explanation → `methods`
- Problem + solution story → `debugging`

**Knowledge synthesis/learning:**
- Paper summary/review → `literature`
- Learning new skill/concept → `learning`
- Theoretical exploration → `theory`

**Technical content:**
- Code-focused → `code`
- Analysis-focused → `data-analysis`
- Tool-focused → `tools`

**Personal/meta:**
- About blog/open science → `meta`
- Personal insight → `reflection`
- PhD/career related → `career`

### 2. What DOMAIN(s) does it cover?

Add 1-2 domain tags:
- Network/systems work → `systems-biology`
- Immune system → `immunology`
- Drug-related → `pharmacology`, `pk-pd`, `drug-discovery`
- AI/ML for bio → `bioai`
- General computational → `computational`

### 3. Final check: 2-4 tags total?

✅ YES → Good to go
❌ NO → Remove least relevant tags

---

## Tag Combinations (Common Patterns)

### Weekly Progress Updates
```yaml
categories: [progress, {domain}, {technical if relevant}]

Examples:
- [progress, systems-biology, data-analysis]
- [progress, immunology]
- [progress, drug-discovery, code]
```

### Problem-Solving Posts
```yaml
categories: [debugging, {technical}, {domain if relevant}]

Examples:
- [debugging, code, tools]
- [debugging, data-analysis, computational]
- [debugging, methods, immunology]
```

### Paper Summaries
```yaml
categories: [literature, {domain1}, {domain2 if relevant}]

Examples:
- [literature, systems-biology, drug-discovery]
- [literature, immunology, bioai]
- [literature, pharmacology]
```

### Method/Tutorial Posts
```yaml
categories: [methods, {technical}, {domain}, learning]

Examples:
- [methods, code, systems-biology]
- [learning, methods, data-analysis]
- [methods, tools, computational, learning]
```

### Code/Technical Posts
```yaml
categories: [code, {what kind}, {domain if relevant}]

Examples:
- [code, tools, systems-biology]
- [code, data-analysis, immunology]
- [code, methods]
```

### Reflective Posts
```yaml
categories: [reflection, {topic area}, {career if relevant}]

Examples:
- [reflection, career]
- [reflection, meta]
- [reflection, learning, career]
```

---

## Tag Definitions (Quick Reference)

### RESEARCH PROCESS
| Tag | Use When | Example |
|-----|----------|---------|
| `progress` | Regular updates, milestones | "Week 5 Progress" |
| `project` | Project-specific work | "Immune Network Project Update" |
| `methods` | Implementing/explaining methods | "Implementing Louvain Clustering" |
| `debugging` | Solving problems | "Fixing Memory Errors" |

### KNOWLEDGE BUILDING
| Tag | Use When | Example |
|-----|----------|---------|
| `literature` | Paper summaries, reviews | "Notes on AlphaFold Paper" |
| `learning` | Learning new skills/concepts | "Learning JAX" |
| `theory` | Theoretical explorations | "Network Centrality Theory" |

### TECHNICAL
| Tag | Use When | Example |
|-----|----------|---------|
| `code` | Code examples, scripts | "Python Analysis Script" |
| `data-analysis` | Analysis workflows | "scRNA-seq Analysis Pipeline" |
| `tools` | Software, packages | "NetworkX vs igraph" |

### DOMAINS
| Tag | Use When | Example |
|-----|----------|---------|
| `systems-biology` | Network/systems work | "Cell Network Analysis" |
| `immunology` | Immune system research | "T-cell Interactions" |
| `pharmacology` | Drug-related | "Drug-Target Networks" |
| `pk-pd` | PKPD modeling | "Population PKPD Model" |
| `drug-discovery` | Drug discovery pipelines | "Target Identification" |
| `bioai` | ML/AI for biology | "Protein LM Fine-tuning" |
| `computational` | General comp bio | "Optimization Techniques" |

### META
| Tag | Use When | Example |
|-----|----------|---------|
| `meta` | About blog/open science | "Why Open Notebook" |
| `reflection` | Personal insights | "Research Reflections" |
| `career` | PhD/career journey | "PhD Application Update" |

---

## DO's and DON'Ts

### ✅ DO:

- Use 2-4 tags per post
- Combine process + domain tags (e.g., `progress, immunology`)
- Add technical tag when relevant (e.g., `code`, `data-analysis`)
- Use `meta` for posts about the blog itself
- Use `reflection` for introspective posts
- Be consistent with tag spelling (lowercase, hyphens)

### ❌ DON'T:

- Use 6+ tags (dilutes meaning)
- Use just 1 tag (underspecified)
- Create new tags arbitrarily (stick to defined set)
- Use tags inconsistently (check this guide!)
- Mix up similar tags (e.g., `methods` vs `learning` — choose based on focus)

---

## Tag Priority Hierarchy

When choosing between similar tags:

**`progress` vs `project`:**
- `progress` = regular update across work
- `project` = specific project deep-dive

**`methods` vs `learning`:**
- `methods` = focus on the method itself
- `learning` = focus on your learning process

**`code` vs `tools`:**
- `code` = your code/scripts
- `tools` = reviewing/comparing existing tools

**`debugging` vs `methods`:**
- `debugging` = problem-solving story
- `methods` = method implementation/explanation

**Domain tags (when work spans multiple):**
- Choose 1-2 most central domains
- If truly interdisciplinary, use `computational` + specific domain

---

## Template for New Posts
```markdown
---
title: "[Your Title]"
author: "Lindawati Kusuma"
date: "YYYY-MM-DD"
categories: [tag1, tag2, tag3]  # 2-4 tags
description: "Brief description for preview"
---

## [Your content]
```

---

## Checklist Before Publishing

- [ ] Title is clear and descriptive
- [ ] Date is correct
- [ ] 2-4 tags selected
- [ ] Tags follow this guide
- [ ] Description written
- [ ] Content is complete
- [ ] Code blocks have language specified
- [ ] Links work
- [ ] Preview looks good

---

## Questions?

When in doubt:
1. What is the PRIMARY focus of this post?
2. What tags would help someone FIND this post?
3. Does this combination make sense?

If still unsure, default to:
- Process tag + Domain tag (e.g., `progress, immunology`)
- Add technical tag if relevant (e.g., + `code`)

---

## Updates

This guide will evolve. New tags may be added if clear need emerges, but preference is to keep set stable and simple.

Last updated: 2025-11-07