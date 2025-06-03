# Fairness in Machine Learning
### A Sociotechnical Perpsective (WIP)
	Ngozi Harrison
	PhD Student, UCLA Information Studies


---

### About Me
	2nd year PhD Student in the Department of Information Studies, UCLA
	from Oakland, CA
	**Previously** Creative Effectiveness Lead @ Google



	**Areas of Interest** ML Fairness and Ethics, Social Aspects of Mathematical knowledge, Data Justice, Critical AI Studies
	**Research Interests**
	My research is focused on critically examining the mathematical and computational methods behind AI, Machine Learning, and sociotechnical systems



---
# Agenda

My research focus and interests
	1. Background and Motivation
	2. Bridging the Discipline Gap
	3. The (Unsolvable) Problem of Fairness
	4. Critical Technical Practice
	5. History of Algorithmic fairness
	6. Classifying Approaches to Fairness
	7. Discussion

Review of bodies of scholarship on Fairness
Math/Machine Learning
FAccT
Critical Tech 
Legal
Philosophy
Critical perspectives on fairness
Classification within IS and Machine Learning
Classifying formalizations and definitions of machine learning fairness
Questions

there is a gap between machine learning, computer science and applied math on one side and STS, humanities, Information Science, Critical AI studies, and Critical Data Studies

this gap is informed by differences in knowledge production practices, language, problem definition, and some other stuff formal vs interpretive

increasing need for interdisciplinary work

critical technical practice is one example

part of what is needed is increased reflection to deal with the normative way much research is conducted

talk about the long history of fairness

---
# Background and Motivation


---
	> “Part of the challenge of understanding algorithmic oppression is to understand that mathematical formulations to drive automated decisions are made by human beings. While we often think of terms such as “big data” and “algorithms” as being benign, neutral, or objective, they are anything but.” (Noble, p. 19)


---
### Tech companies and the algorithms they deploy have an outsized influence on society.


---
# A sociotechnical perspective considers the historical, social, cultural contexts and power relations in which technologies are embedded

---
### These algorithms in many cases remarkably effective but they often exacerbate issues of bias, social justice, and fairness
---
# Bridging The Discipline Gap
	There is a gap between Machine Learning, Computer Science and Applied Math on one side and STS, Humanities, Information Science/Studies, Critical AI studies, and Critical Data Studies on another side

---

# At UCLA this gap is geographical

/assets/Clipboard.png
size: contain


---




/assets/Clipboard 4.png
size: contain


---
# Reasons for this Gap
	- Differences in Knowledge Production Practices and language
	- Similar use of terms very different meaning, not always obvious  
	- Difficult to translate technical topics for non-technical audiences
	- Differences in methods
	- Normative vs Reflexive approaches
	- Pedagogy
	- Lack of spaces and incentive for interdisciplinary collaboration

this gap is informed by differences in knowledge production practices, language, problem definition, and some other stuff formal vs interpretive

---
###### How do we translate/transpose/transform across these domains
	Mathematically, fairness is an optimization problem
	From a sociotechnical perspective fairness is a moral, ethical, and societal problem

think both in a spatial and musical sense

---
# The (Unsolvable) Problem of Fairness


---
###### The Machine Learning Loop
/assets/Pasted image 20250509083059.png
size: contain
Source: (Barocas et al., p. 2)

---
#### There are Four Problems when doing fairness work
	- Technocentric solutions
	- Differences in the meaning of fairness
	- Lack of contextual, historical, and societal understanding
	- Failure to consider the legitimacy of certain applications

---
## Many approaches to ethics and fairness are techno-centric

classic sort of example here is the problem of facial recognition. 

example of facial recognition algorithms that are not good at recognizing black skin because of lack of representation in the data set. 







Relevant Scholarship to Machine Learning Fairness
- Mathematics of Machine Learning
- FAccT
- Critical Tech Scholarship
- Legal
- Philosophy (Ethics)


---
	> “The fact that machine learning is “evidence-based” by no means ensures that it will lead to accurate, reliable, or fair decisions. This is especially true when using machine learning to model human behavior and characteristics. Our historical examples of the relevant outcomes will almost always reflect historical prejudices against certain social groups, prevailing cultural stereotypes, and existing demographic inequalities. And finding patterns in these data will often mean replicating these very same dynamics.” (Barocas et al., p. 2)


---
### Lack of Contextual Understanding


---
### The Framing Trap
	Selbst et al. use the term The Framing Trap to a common problem in fair-ML work that results in ineffective and potentially dangerous solutions.

	**The Framing Trap** is a failure to model the entire system over which fairness will be enforced

“The Framing Trap Failure to model the entire system over which a social criterion, such as fairness, will be enforced” (Selbst et al., 2019, p. 60)


“The most common abstractions in machine learning consist of choosing representations (of data), and labeling (of outcomes). Once these choices are made, they constitute the description of what we call the algorithmic frame. Within this frame, the efficacy of an algorithm is evaluated as properties of the output as related to the input. For example, does the algorithm provide good accuracy on training data and good generalizability to unseen data from the same distribution? We refer to this as an end-to-end property of the frame; it is how any particular algorithm is evaluated. Yet, while in the algorithmic frame (where the vast majority of current data” ([Selbst et al., 2019, p. 60](zotero://select/library/items/FGJVUJXA)) ([pdf](zotero://open-pdf/library/items/YNTYLR99?page=2&annotation=ZEYFWIGC))

---
### Fundamentally Fairness is a moral and ethical concept for examining the decisions make by institutional and algorithmic processes.

Algorithmic Decision Making as Institutional Decision Making
Barocas et al (2023) argue that machine learning and bias should not be compared to the subjective judgements of individual humans but institutional decision making. 

---
# Algorithmic Fairness and Legitimacy


	Algorithmic fairness is not just about individual outcomes but also the overall legitimacy of algorithmic decision making and the legitimacy of the organizations and individuals deploying it


Formalizing Fairness
There are various approaches for formalizing the measurement of how fair a ML system or algorithm is using statistical techniques and causal models. 
Demographic parity, Similarity, Counterfactuals


---

# Critical Technical Practice

---

### Critical Technical Practice is a term developed by Phil Agre to describe a way of approaching technological work

---
	> A critical technical practice will, at least for the foreseeable future, require a split identity -- one foot planted in the craft work of design and the other foot planted in the reflexive work of critique. 
	
---
	> Successfully spanning these borderlands, bridging the disparate sites of practice that computer work brings uncomfortably together, will require a historical understanding of the institutions and methods of the field, and it will draw on this understanding as a resource in choosing problems, evaluating solutions, diagnosing difficulties, and motivating alternative proposals. (Agre, 1998)
	


---
### Reflexivity
	Calls for ML fairness data justice, quantitative justice, computational justice argue for the use of formal methods to pursue justice and reduce bias

	While doing this work, we must also examine the foundations of our methods, hidden epistemologies, and resist reducing social issues to purely technical problems


---
### History of Algorithmic Fairness
	Fairness work has significantly grown in prevelence within the ML research community. However algorithmic fairness as a topic has a much longer history


---


/assets/Clipboard 7.png
size: contain



---
### Pre-History of Algorithmic Fairness
	- The idea of algorithmic fairness dates back to at least the 17th centiry
	- During the enlightment much of the discussion surrounding fairness was connected to probability and statistics
	- There have been various attempts to mathematize fairness by Leibniz, Pascal, de Condorcet and Laplace 


---
### Insurance Industry and Race
	During the Transatlantic slave trade, risk classification and racial classification were intimately linked. 


---
	During this time, fairness was primarily seen as a duty to fairly adjudicate between slave traders, their financiers, and insurance providers based on laws, actuarial tables, and risk assessment algorithms

who is considered a valid person that we have a duty toward when it comes to fairness

how do we deal with power differences
---
	> Statistics tell only half of the story, and, in doing so, they become part of the problem. How to correlate the number of lashes a person's ancestor received 190 years ago with their likelihood of being unemployed in July 2020? Or being in the criminal justice system? Or dying of COVID-19? (da Silva, Unpayable Debt 2022, 166) 

---

# FAccT and the Fair-ML Community
	ACM FAccT is the Conference on Fairness, Accountability, and Transparency sponsored by the Association of Computing Machinery (ACM). This conference has become the home for researchers who are interested in ethics, fairness, accountability, bias, and transparency from a multidisciplinary perspective
	The first FAccT conference was held in New York in 2018


there is a gap between machine learning, computer science and applied math on one side and STS, humanities, Information Science, Critical AI studies, and Critical Data Studies

this gap is informed by differences in knowledge production practices, language, problem definition, and some other stuff formal vs interpretive

increasing need for interdisciplinary work

critical technical practice is one example

part of what is needed is increased reflection to deal with the normative way much research is conducted

talk about the long history of fairness



My research focus and interests
Background and motivation
Problem statement
Research questions
History of algorithmic fairness
Review of bodies of scholarship on Fairness
Math/Machine Learning
FAccT
Critical Tech 
Legal
Philosophy
Critical perspectives on fairness
Classification within IS and Machine Learning
Classifying formalizations and definitions of machine learning fairness
Questions


---

# Classifying Approaches to Fairness


---
### Classification within Information Studies
	Knowledge organization is a subarea of information studies focused on the description of documents, indexing and classification in order to provide ways of representing and organizing information objects


---
	Classification organizes information objects by considering them via a number of attributes

---
### Critical information studies argues that building classification schemes and the act of classifying is a both a technical and socio-political process


---
# Brief Survey of Relevant Work

---


/assets/Clipboard 6.png
size: contain



---


/assets/Clipboard 5.png
size: contain


---



/assets/Clipboard 8.png


---
	**Abstract:**
	This project combines a machine learning and qualitative approach to analyze definitions and mathematical formalizations of fairness within machine learning research in order to identify the values enccoded in such research, classify different approaches, and identify the opportunities and limitations of fairness as a framework. My goal with this is to build a taxonomy for classifying different approaches to fairness, along with a critical analysis of machine learning methods that can inform future approaches to machine learning research and Critical AI studies
---
# Research Questions

	- What are the definitions of Fairness in the literature across the Mathematics of Machine Learning, Machine learning/FAccT community, and Critical AI studies? 
	- What are the gaps and limitations in current literature?
	- What are the values expressed in research papers? How do these inform fairness work?

---
### Mixed Methods Approach

	**Qualitative** Values Coding
	**Computational** Topic Modelling via Non-negative Matrix Factorization
---
### Potential Key Contributions
	- Development of annotation scheme for analyzing fairness in machine learning research papers
	- Develop classifcation system for definitions and formalizations of fairness
	- Present mixed methods approach incorporating qualtiatve and NMF approaches which could be leverages in future work
	- Present framework for critically assessing in progress work on fairness


Current State of Project
- Need to Reduce scope
- Refine project direction and critical framework
- Develop deeper understanding of NMF and PCA
- Identify a more specific machine learning technique or application

---

#### Questions for Discussion
	- What canonical papers about fairness, specifically as it relates to PCA and NMF, should I be looking at
	- What would you like to know about fairness?
	- Would this work be helpful?
	- Recomendations for Implementing NMF
	- Planning to take Math 115A next quarter and would love any tips on how to prepare this summer
---
# References
	Barocas, S., Hardt, M., & Narayanan, A. (2023). Fairness and Machine Learning: Limitations and Opportunities. The MIT Press.
	Friedler, S. A., Scheidegger, C., & Venkatasubramanian, S. (2016). On the (im)possibility of fairness (No. arXiv:1609.07236). arXiv. https://doi.org/10.48550/arXiv.1609.07236
	Jr, D. M., Prabhakaran, V., Kuhlberg, J., Smart, A., & Isaac, W. S. (2020). Extending the Machine Learning Abstraction Boundary: A Complex Systems Approach to Incorporate Societal Context (No. arXiv:2006.09663). arXiv. https://doi.org/10.48550/arXiv.2006.09663
	Le Bui, M., & Noble, S. U. (2020). We’re Missing a Moral Framework of Justice in Artificial Intelligence: On the Limits, Failings, and Ethics of Fairness. In M. D. Dubber, F. Pasquale, & S. Das (Eds.), The Oxford Handbook of Ethics of AI (pp. 161–179). Oxford University Press. https://doi.org/10.1093/oxfordhb/9780190067397.013.9
	Noble, S. U. (2018). Algorithms of oppression: How search engines reinforce racism. New York University Press.
	Ochigame, R. (2020, January 30). The Long History of Algorithmic Fairness. Phenomenal World. https://www.phenomenalworld.org/analysis/long-history-algorithmic-fairness/
	Selbst, A. D., Boyd, D., Friedler, S. A., Venkatasubramanian, S., & Vertesi, J. (2019). Fairness and Abstraction in Sociotechnical Systems. Proceedings of the Conference on Fairness, Accountability, and Transparency, 59–68. https://doi.org/10.1145/3287560.3287598