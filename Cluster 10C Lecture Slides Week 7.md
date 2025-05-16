---
marp: true
theme: ucla
class: invert
style: 
math: mathjax
paginate: "true"
footer: Week 7 | Ngozi Harrison | Cluster 10C
transition: slide
---


# The Long History of Computational Reason and Algorithmic Culture - Week 7

Spring 2025
Ngozi Harrison 
ngozih@g.ucla.edu
PhD Student, Information Studies

---
# Today
- Read and Discuss NY Mag Article
- **Lecture** Values in Datasets and Machine Learning Research
- **Discuss** Questions about Investigate that Tech Writing Report
- **In class Activity** Local LLM set up
- Reading Through the AI Hype Essay Overview


---
<iframe width="1100" height="615" src="https://www.youtube.com/embed/7GGZd4zUZzE?si=rTW9jOW3r6ZClskn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---
# Critical Technical Practice

---
### Critical Technical Practice is a term developed by Phil Agre to describe a way of approaching technological work

---

> A critical technical practice will, at least for the foreseeable future, require a split identity–one foot planted in the craft work of design and the other foot planted in the reflexive work of critique. Successfully spanning these borderlands, bridging the disparate sites of practice that computer work brings uncomfortably together, will require a historical understanding of the institutions and methods of the field, and it will draw on this understanding as a resource in choosing problems, evaluating solutions, diagnosing difficulties, and motivating alternative proposals. (Agre, 1998)


---
### Reflexivity
Calls for data justice, quantitative justice, machine learning fairness. computational justice argue for the use of formal methods to pursue justice

While doing this work, we must also examine the foundations of our methods, hidden epistemologies, and resist reducing social issues to purely technical problems

---
# Note to prepare for autoethnography assignment
- During this tutorial process write notes to your self reflecting on the process

---
# Here are some questions to consider
- How does what you are currently doing connect to readings and discussions we've had in class?
- What are you curious about? What unanswered questions do you have?
- How do you feel right now?
- What do you notice about your computer?
- Is there any difference running the local model compared to using ChatGPT, Gemini, etc

---
# In Class Activity
## Setting up a Local LLM

---
# What is Ollama?

---
# What we will learn
Today we will learn how to run a LLM model locally 

---
# Step 0 Make a Note of your computer specs
- What is your current operating system
- How much free space do you have on your hard drive
- How much RAM do you have
- Does your computer have a GPU

---

# Step 1 Download and Install Ollama

---
# Make Sure Ollama installed correctly
- Open terminal or cmd on windows and type  `ollama`
- If you receive output then you are good to go
---
# Step 2 Choose a Model
- Browse the models on the ollama model library and choose a model. Make sure that the model you choose is ~7B or less

---
### As you choose  a model make note of
- how you found that model
- why you found that model interesting
- who created this model 
- what information is contained in the readme
- is there any information about how this model was trained. 

This will be helpful later for your autoethnography assignment

---
# Step 3 Download and run the model
- open the terminal
- run `ollama` followed by the name of your model 
- Example 
	- `ollama run deepseek-r1:1.5b`
	- `ollama run mistral`
	- `ollama run llama3:8b`

---
# Further Customization and development
- Can use Modelfiles to create custom models with parameters and a system message
- Ollama exposes an API on localhost and you have write applications and scripts that use the local ollama models