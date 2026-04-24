# Introduction to Critical AI Studies - Week 4
	Ngozi Harrison
	ngozih@g.ucla.edu
	Spring 2026
	**Cluster 10C**  


---
# Today
	- Lecture
	- Technical Workshop
	- Reflection and Discussion
	- Prep for next week's Writing Workshop (If we have time)


---
# Machine Learning and Critical Technical Practice
	For the next several week we will learn about the mathematical and technical aspects of machine learning while engaging in something called critical technical practice

---
# Data, algorithms, and mathematics are fundamentally social
	> “Part of the challenge of understanding algorithmic oppression is to understand that the mathematical formulations which drive automated decisions are made by human beings.” 
	(Noble, 2018, p. 1)


---
# Critical Technical Practice
	> A critical technical practice will, at least for the foreseeable future, require a split identity -- one foot planted in the craft work of design and the other foot planted in the reflexive work of critique. 
---
	> Successfully spanning these borderlands, bridging the disparate sites of practice that computer work brings uncomfortably together, will require a historical understanding of the institutions and methods of the field, and it will draw on this understanding as a resource in choosing problems, evaluating solutions, diagnosing difficulties, and motivating alternative proposals. (Agre, 1998)

---
# Machine Learning as a Paradigm


---
# AI is a large discipline containing many paradigms, approaches, and techniques

/assets/Clipboard 50.png
size: contain

---
# What is a Paradigm
	Thomas Kuhn defines paradigms as "the entire constellation of beliefs, values, techniques, and so on shared by the members of a given community.” (Kuhn, 1970, p. 175) [^] 

/assets/Clipboard 49.png
size: contain


---
# Paradigms and Normal Science
	Kuhn defines normal science as the research conducted under a shared settled paradigm 
	**A paradigm contains severals things:**
	A collection of **facts**, a class of **instruments** for measurement, and a set of **problems** that are considered by most to be in scope and legitimate


---
# Paradigms come with their own set of assumptions, normative practices, and settled questions that function as background to research and practice creating what Mimi Onuoha calls *unknowable things*

---


/assets/Clipboard 48.png
size: contain


---

/assets/Clipboard 51.png
size: contain

# Machine Learning was first coined in 1959 by Arthur Samuel

/assets/Clipboard 52.png
size: contain


---

# Machine Learning combines computation and mathematical methods in order to predict, classify, extract knowledge from large amounts of data


/assets/Clipboard 12 1.png
size: contain




---
# Overview of Approaches to Machine Learning

---
# There are two main kinds of AI Systems

	**Predictive AI**
	AI systems that can make decisions or predictions about new unseen data 
	**Generative AI**
	Generative AI generates new content by training a model on existing datasets


---
# Within Machine Learning there are three core paradigms
	- Supervised Learning
	- Unsupervised Learning
	- Reinforcement Learning


---
# Supervised Learning uses labelled data to train a model that can reliably make predictions about unseen data
	These models fit within two broad categories
	- **Regression** models predict continuous values
		- Linear regression
		- Polynomial regression
	- **Classification** models predict categorical values
		- Logistic regression
		- Support vector machines
		- K-Nearest neighbors (KNN)

---

# Unsupervised learning uses unlabelled data and seeks to discover latent (hidden) patterns or structures
	Two important categories include
	- **Clustering models** used to group datapoints based on some definition of similarity
		- K-means
	- **Dimensionality Reduction** models which simplify high dimensional data by projecting into a lower dimensional vector space that captures the dimensions along which the data varies the most
		- Principal Component Analysis (PCA)
		- Linear Discriminant Analysis (LDA)
		- Non-negative Matrix Factorization (NMF)


---
# Reinforcement Leearning models learn through trial and error and a system of rewards and penalties. The agent takes actions in an environment with the goal of maximizing a reward function. 

/assets/Clipboard 54.png
size: contain

---
# How Machine Learning works


---
	
# There are three major aspects to machine learning ==data==, ==model==, and ==learning==. 



/assets/Pasted image 20250509083059.png
size: contain

	Data is at the core of machine learning and provides the information for the process. Models are used to generate data that is hopefully close to the original dataset. The learning aspect is the most crucial and involves the automatic tweaking of the many parameters of the model in order to evaluate and optimize how well the model can predict the training data



---

# Data
	Data is computationally tractable information that purports to represent some phenomenon. This data has been collected and structured for some purpose


---
# Data Preprocessing and Cleaning
	- Gather data, if using supervised learning need labelled data
	- Clean data to fix missing values, duplicates, errors, irregularities
	- Normalize and standardize numerical values, convert categorical variables to numerical format

---
# Data in Tabular Format
/assets/Clipboard 55.png
size: contain


---

# Data in numerical format
/assets/Clipboard 56.png
size: contain



---
# Features and Labels
/assets/Clipboard 61.png
size: contain


---
# Data as vectors
	Collect a dataset $\mathscr D$ to be used as the training set
	$\mathscr D$ is composed of $(x_n,y_n)$ pairs $x_n$ refers to a datapoint or example or sample [^Examples are rows in the tabular representation of the dataset]  and $y_n$ refers to the ground truth label, the value we are hoping to predict.


---
	Each example is a $D$ dimensional vector of real numbers that contains $D$ features
	Features refers to the properties or attributes of an example in the origianl dataset


---
# What is a model?

	A machine learning model is a formalization and abstract representation of a concrete system of real world phenomenon that once trained on a given dataset can make predictions


---
# Model can have at least two meanings
	- Can refer to a class of models and their learning algorithms
	- A fully trained model with tuned parameters

---
# Questions to ask about models (Cui bono)
	- Who gets to define how models are built?
	- Who gets reaps the benefits?
	- Who's data is used to train models?
	- Who bears the costs?
	- Who gets to decide how they are used?

---
# Components of a Machine Learning Model
	- Parameters
	- Hyperparameters
	- Loss Function
	- Optimization Algorithms
	- Evaluation Metrics


---
	We can think of a model as a predictive function $f$ that takes the example $x_n$ as input and produces an output $$\hat{y}_n=f(x_n,\theta)$$
	$\theta$ are the weights or parameters, the goal of the learning process is to find good parameters


---
# A brief note on hyperparameters
	hyperparameters are parameters that define configurable parts of the model/learning process. They can be either model hyperparameters (size of a neural network) or algorithm hyperparameters (learning rate)

	The configuration of hyperparameters are often based on best practices, norms, and constraints

---
# How do we know if a model is good?

---
# Learning


---
# Error
	Once we have our predictor we can test it using labelled data and measure how far our prediction is from our ground truth data
	Error is the differnce between our prediction $\hat{y}$ and our ground truth label $y$
	$$\text{Error}=y- \hat{y}$$


---
# Loss Function/Cost Function
	In order to quantify this error we create a loss function. A standard loss function for predicting continuous values is Means Squared Error (MSE)
	$$\mathscr L = \frac{1}{N}\sum^{n}_{i=1}(y_n-\hat{y}_n)^2$$
	Reminder $\hat{y}=f(x_n,\theta)$
	Learning or training is the process of finding a set of weights that minimized this loss function
---
# **Underfitting**
	*   **Too Simple:** The model cannot capture underlying patterns in the data.
	*   **Performance:** Poor results on both training and test data.

# **Overfitting**
	*   **Too Complex:** The model memorizes noise and outliers instead of learning true patterns.
	*   **Performance:** Excellent on training data, but poor on new test data.
	**The Goal:** Find the balance between complexity to maximize **generalization**.

---
# Gradient Descent
	An iterative optimization algorithm used to minimize the error (loss) of a machine learning model.
	**Positive Gradient:** Tells you which way the error is getting worse.
	**Negative Gradient:** Tells you which way the error is getting better.
	**Optimization:** To minimize error (reach the bottom), you take steps in the **opposite direction** of the gradient.


/assets/Clipboard 60.png
size: contain
image source hackernoon


---
# What is a gradient
	For a function $\mathbb R^n \to \mathbb R$, $x \mapsto f(\mathbf{x})$ of $n$ variables, 
	where $\mathbf{x} = [x_1, x_2, \dots, x_n]$:
	The gradient points straight toward the **steepest uphill slope** at your current location

$$\nabla f(\mathbf{x}) = \frac{df}{dx}= \begin{bmatrix} \frac{\partial f}{\partial x_1} \\ \frac{\partial f}{\partial x_2} \\ \vdots \\ \frac{\partial f}{\partial x_n} \end{bmatrix}$$


---
# Gradient descent algorithm
	Step 1: Start with random values for slope and intercept.
	Step 2: Calculate the error between predicted values and ground truth labels.
	Step 3: Find how much each parameter contributes to the error (gradient).
	Step 4: Update the parameters in the direction that reduces the error.
	Repeat until the error is as small as possible.

---
# Gradient Descent Example for Simple Linear Regression 
	Hypothesis: $h_\theta(x) = \theta_0 + \theta_1x$
	Parameters: $\theta_0, \theta_1$
	Loss Function: $$J(\theta_0,\theta_1) = \frac{1}{N}\sum^{n}_{i=1}(y_n-h(x_n,w))^2$$
	Goal: $\underset{\theta_0,\theta_1}{\text{minimize}}J(\theta_0,\theta_1)$


---
	initialize with random parameters
	Repeat until convergence
$$\theta_j := \theta_j-\alpha \frac{\partial}{\partial\theta_j}J(\theta_0,\theta_1)$$
$$\text{For } j = 0 \text{ and } j=1$$
	$\alpha$ is the learning rate, this determines fast the optimization algorithm moves each step



---

# Robustness
/assets/Clipboard 63.png
size: contain
	Source: Braiek, H. B., & Khomh, F. (2024). Machine Learning Robustness: A Primer (arXiv:2404.00897). arXiv. https://doi.org/10.48550/arXiv.2404.00897


---


/assets/Clipboard 64.png
size: contain



---



### Keyword Presentation
# Linear Algebra 


/assets/Clipboard 12 1.png
size: contain



---
There are three paradigmatic ways of introducing linear algebra which we can classify as elementary, computational, and abstract. 

# Three ways of defining Linear Algebra
|  Classification  |  Definition  |
|----|----|
|  Elementary  |  Linear Algebra is the study of vectors, matrices, systems of linear equations, and problems that can be solved using linear algebraic techniques  |
| Abstract   | Axler defines Linear Algebra as "the study of the study of linear maps on finite-dimensional spaces" (Axler, 2015)  |
|  Computational  |  "Linear Algebra is the study of vectors and ways of manipulating vectors" (Deisenroth, 2020) |


---
# There are three core concepts in linear algebra
	Scalar $\lambda \in \mathbb{R}$ 
	We can think of a scalar as a single value, usually a real number
	Vector 
	Example Vector $a = \begin{bmatrix} 1\\2\\3 \end{bmatrix} \in \mathbb{R}^3$ Vectors are objects that we can add together and multiply by a scalar to get another vector. 

	Matrix A $m\times n$ matrix is a collection of elements consisting of $m$ rows and $n$ columns. We  can think of matrices as a collection of vectors or a linear transformation
	Example Matrix 
	$A = \begin{bmatrix} 1 & 3 & 5 \\ 8 & 2 & 1 \\ 3 & 3 & 4 \end{bmatrix}$

---
# History of Linear Algebra
	Linear algebra encompasses many techniques that evolved over time and in several places including China, Europe, Greece, and Egypt


---
# The Nine Chapters on Mathematical Art
	Composed by scholars during the 10th-2nd Century BCE
	describes using array methods to solve linear equations including the concept of determinants

/assets/Clipboard 59.png
size: contain



---


/assets/Clipboard 58.png
size: contain

	In the 19th century James Joseph Sylvester and Arthur Cayley introduced algebraic techniques for linear algebra and coined the term *matrix*, which comes from the Latin word *mater* for womb 

/assets/Clipboard 57.png
size: contain



---
# What does Linear mean?
	Linear transformations are functions that map one vector to another

	Formal Definition
	A transformation $L()$ is called linear if the following properties hold
	Addition: $L(v+w) = L(v) + L(w)$
	Scalar Multiplication: $L(\lambda v) = \lambda \cdot L(v)$


---

# What is Algebra?
	Algebra comes from the name the text Al-jabr (الجبر) written by polymath Muhammad ibn Musa al-Khwarizmi who worked in Baghdad in the 9th century
	Algebra broadly refers to the formal manipulation of abstract symbols

/assets/Clipboard 62.png
size: contain



---
# Linear Algebra in Machine Learning
	**Making problems and data tractable**
	Linear algebra allows for optimization, efficient computation, data representation and manipulation
	**Data Representation**
	Data is represented using vectors and matrices, for example word embeddings
	Dot product, matrix manipulation, and matrix transformations are important to machine learning
	**Finding Better Representations**
	Eigenvalues, Eigenvectors, and matrix decompositions are important for fundamental ML algorithms such as Principle Component Analysis




---
# Hands on Technical Work #1
	Ordinary Least Squares Model (Linear Regression) 


---
# Technology Ground Rules
	1. This is not a contest
	2. You are not bad at technology (or math)
	3. Your mistake is almost invariably very minor.
	4. No one is an expert at everything.
	5. We do not sink or swim in this class.


---
# Technical Reflection and Observations (15min)
	What decisions are made as part of the machine learning process?
	How does this connect to material covered in fall and spring quarter?
	What questions do you have after completing this activity?
	What did you notice with this example


---
# Writing Workshop Next week
	Reading to develop your writing
	**Homework:** 
	- Find a paper in your field to analyze
	- Find a paper or reading from this class that you enjoyed reading