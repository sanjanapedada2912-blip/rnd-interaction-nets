# 📚 Literature Review

This section documents the research papers and other resources
that have contributed to our understanding of Interaction Nets
and helped shape our research direction.

The literature reviewed so far includes the foundational work
on Interaction Nets and resources that led us toward Interaction
Combinators and HVM.

---

## 📄 01 — Interaction Nets

### Yves Lafont

**Title:** *Interaction Nets*  
**Author:** Yves Lafont  
**Publication:** POPL '90  
**Type:** Research Paper  
**Status:** 🟢 Studied

### Overview

Yves Lafont's *Interaction Nets* serves as the primary
theoretical foundation of our research.

The paper introduced us to Interaction Nets as a computational
model based on local interactions between connected agents.

Our study of the paper focused on understanding the basic
structure of Interaction Nets and how computation can be
represented through interaction and reduction rules.

### Concepts Encountered

- Agents
- Ports
- Active pairs
- Interaction rules
- Reduction
- Graph rewriting
- Locality
- Confluence
- Parallelism
- Interaction Combinators

### Relevance to Our Research

This paper forms the starting point of our research journey.

It helped us establish an understanding of the underlying
computational model before exploring its connections with
Lambda Calculus, Interaction Combinators, and HVM.

### Detailed Research

For our detailed notes and current understanding:

→ [Interaction Nets Research](../research/Lafont-Interaction-Nets.md)

---

## 🎥 02 — Interaction Combinators: The Hidden Patterns of Computation?

### Marvin & Christopher

**Title:** *Interaction Combinators: The Hidden Patterns of Computation?*  
**Authors:** Marvin & Christopher  
**Type:** Video / Talk  
**Status:** 🟡 Exploring

### Overview

During our exploration of Interaction Nets and the
programming-language aspects of the topic, we encountered
this resource on Interaction Combinators.

The resource introduced us to Interaction Combinators and
their relationship with computation through local interaction.

This led us to investigate the topic further and eventually
explore **HVM (Higher-order Virtual Machine)**.

### Concepts Encountered

- Interaction Combinators
- Locality
- Strong confluence
- Parallel reduction
- Computational universality
- Relationship with Interaction Nets
- Relationship with Lambda Calculus
- HVM

### Relevance to Our Research

This resource expanded our research direction beyond the
fundamental Interaction Net model and introduced questions
about how a small set of interaction combinators can express
general computation.

It is currently being used as a starting point for our further
exploration of Interaction Combinators and HVM.

### Detailed Research

→ [Interaction Combinators](../research/Interaction-Combinators.md)

---

## 🔗 Literature → Research Direction

Our current literature exploration has contributed to the
following research path:

```text
Yves Lafont
Interaction Nets
      │
      ▼
Understanding Computation
      │
      ▼
Lambda Calculus
      │
      ▼
Interaction Combinators
      │
      ▼
HVM
      │
      ▼
Future Implementation
