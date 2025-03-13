---
marp: true
theme: ucla
class: invert
style: "h 1,  p, li { text-align: left;} p { font-weight: lighter;} li {color: #fff ;}"
math: mathjax
---
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid. initialize ({ startOnLoad: true, theme: 'dark' });
</script>
# Speculating on the Black Box
## Critical Technocultural Discourse Analysis as Method for Critical AI Studies

Ngozi Harrison
IS 298B Prof Cindy Nguyen
PhD Student, Information Studies | Winter '25

---
# Overview
- CTDA as Method
- Research Statement
- Discourses of Algorithmic Culture
- Retrieval Augmented Generation Models
- Reverse Engineering as Critique/Creation
---
## What is CTDA
Critical technocultural discourse analysis is a methodology developed by Andre Brock to conduct a holistic analysis of information systems and technologies. This method uses critical cultural frameworks to understand technical artifacts as embedded in social beliefs and practices. For the past ten years, CTDA has provided a methodological framework to unsettle the normative grounds of technological discourse and techno-determinism. CTDA has primarily been used to analyze the relationship between users, content creators and social platforms. I argue that CTDA has potential as a powerful method for analyzing AI systems.

---
# Research Statement
This Project seeks to extend **Critical Technocultural Discourse analysis** alongside critical **code studies** and **Reverse Engineering** as a method to analyze AI systems as technocultural artifacts and understand how machines and algorithmic culture co-constitute each other. 

Under the technocultural framework of CTDA, technology is examined by treating computational objects as a text to read as it mediates discursive actions and community practices. I seek to extend or stretch CTDA as a methodological approach to analyze the discourse and practices that constitute algorithmic culture and inextricable linking with Blackness. 

---
# Two Components of Paper
<div class = "container">
<div class = "col">Methodology
<p>The first half of this paper will provide an overview of the theoretical framework and prior work that informs my project. Primarily this means understanding the computational system as a complex interplay of artifact, practices, and beliefs  in terms of decolonial and Black computational thought</p>
</div>
<div class = "col">
Proposed Study
<p>The second half will outline the structure for such a method and propose the operationalization of CTDA to analyze retrieval-augmented generation systems (RAG). Because this is my methods qualifying exam the end result will be in the format of an article. However, I envision the results of the actual analysis once it is conducted to live in a variety of formats.</p>
</div>
</div>

---
# Formalizing the Discourses
Algorithmic culture is constituted by a multiplicity of discourses and practices however I argue for a taxonomy of four discourses: 

make the connections between the discourses and genealogy explicit

| Discourse           | Method of investigation                                        | Mode of Discourse                                    |
| ------------------- | -------------------------------------------------------------- | ---------------------------------------------------- |
| User Discourse      | Critical Discourse Analysis                                    | Social posts, User feedback, comments                |
| Technical Discourse | Values Coding                                                  | Academic Papers, Documentation, Git Commits          |
| Critical Discourse  | Values Coding                                                  | Academic papers                                      |
| Machinic Discourse  | Critical Code Studies, Interface Analysis, Reverse Engineering | Documentation, User Interface, Source Code, Datasets |

---
# Object of Study Retreival Augmented Generation Systems
Retreival Augmented Generation (RAG) is a kind of AI system that combines a foundation model such as Lambda, GPT, or deepseek, along with a document retrieval system that extracts information from a knowledge base of documents to answer queries. The purported goal of RAG is to reduce hallucinations and increase the reliability and accuracy of AI systems. 

**RAG Pipeline** Foundation Model $+$ nano GraphRAG Indexing $+$ Kotaemon UI


---

My goal is to analyze this particular configuration of technologies, along with the values, culture and discourse associated to understand shifting perceptions of information retrieval, labor, and documents. Most AI systems are closed ecosystems and prorprietary platforms. 

---
# Reverse Engineering as Critique/Creation

By constructing my own RAG pipeline using open source tools I see this as an example of both critique and creation critically examining my own labor and the work of countless contributers.