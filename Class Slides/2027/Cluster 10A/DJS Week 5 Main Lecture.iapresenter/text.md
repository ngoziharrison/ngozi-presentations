# Measuring the Human, Measuring Society 
## Francis Galton and the Anthropometric Sciences
	Ngozi Harrison
	ngozih@g.ucla.edu
	Week 5: October 28, 2026

---
# Today
	- Measuring the Human, Measuring Society
	- Mathematics as Infrastructure
	- Genealogy of Statistics and Scientific Racism
	- Facial Recognition Technology and the Politics of Recognition


---

# “Drat statistics . . . these are folks!” 
##### W. E. B. Du Bois, The Quest of the Silver Fleece (1911)

/assets/Clipboard 5.png
background: true
opacity: 20%

This line comes from Du Bois's first novel, published in 1911. When presented with a statistical argument as to why Black people shouldn’t be educated in anything other than industrial labor, a character utters this reply. I see this as indicative of the core tension in Du Bois’s sociological and philosophical work: the tension between statistics and folks.

---
# Today we’re going to talk about the ==fault lines== between *statistics* and *folks*

I use fault lines very intentionally; this is a phrase that has special meaning for us here in California. Fault lines connote the space where two tectonic plates meet. These fault lines are fractures or discontinuities in the earth's surface. Fault lines are places that remind us that things that appear solid and timeless are in fact dynamic spaces of friction and change. While it may seem that statistics and folks are naturally joined together, examining these fault lines points us to the friction and dynamism at the heart of both of these domains and where they meet.

A fault line is a complex system of cracks and fractures

/assets/Clipboard 6.png
background: true
filter: grayscale
opacity: 30%
caption: An image of the San Andreas fault in California.(Image credit: Lloyd Cluff via Getty Images)


---

/assets/Clipboard 3.png
background: true
size: contain


---

/assets/Clipboard 4.png
background: true
size: contain


---
# Once we have data, 
# what do we do with it?


---
	Our Subject for Today
# How biometric and eugenic projects used measurement and quantification to make racialized claims appear objective and natural


---

## “Practices of measurement have long been necessitated for the interest of racialism and racialism has always been a form of measurement.” (Dixon-Román, 2025, p. 411)

Race and racialism have been grounding concepts in the development of measurement and statistics, and provide an example of how statistics and mathematics can do the work of naturalizing choices and assumptions into “facts.”

---
# Measuring the Human, Measuring Society
 
 
/assets/Clipboard 35.png
background: true
opacity: 30%

class studying the Bertillon method of 
criminal identification (1853-1914).


---
# Quantification and Measurement


	**Quantification**
	The broader process of turning qualities, categories, and experiences into numerical form so they can be counted, compared, ranked, and calculated with. It includes defining what counts, what gets left out, and which categories exist at all.

	**Measurement**
	“the assignment of numerals to objects or events according to rules” (Stevens, 1946). It requires deciding what property is measured, with what instrument, according to what scale, and the statistical operations applicable.

Measurement seems to simply record what is already there. But a skull, an "intelligence", or a "race" has to be defined as a measurable thing before any number can be assigned. 
quantification defines what is countable at all, measurement assigns numbers to a objects, events, or qualities according to a scale. 


---


### “Part of the challenge of understanding algorithmic oppression is to understand that mathematical formulations that drive automated decisions are made by human beings.” 
	Noble, S. U. (2018). Algorithms of oppression: How search engines reinforce racism. New York University Press. p. 19

This quote from Professor Noble reminds us that the mathematics forming the infrastructure and engine behind data and algorithmic systems are fundamentally social.

---
# Two Guiding Questions:
	- How do you quantify people?
	- How do you take the measure of society?

---

# Mathematics as Infrastructure

 https://en.wikipedia.org/wiki/Galton_board#/media/File:Quincunx_(Galton_Box)_-_Galton_1889_diagram.png


/assets/Clipboard 36.png
background: true
opacity: 20%

---
# There are several core areas of mathematics that provide machinery for making use of data
	- Statistics
	- Probability
	- Linear Algebra


---
# Statistics and Probability
	The emergence of statistics and probability was brought about by material, social, and mathematical transformations. They each emerged separately and converged in the 19th century 


---

# Statistics
	Statistics is a discipline concerned with collection, analysis, and interpretation of data. Statistics makes use of various methods and practices to conduct analysis and develop inferences based on data. 

/assets/Clipboard 10.png
size: contain
caption: https://en.wikipedia.org/wiki/Statistics#/media/File:Standard_Normal_Distribution-en.svg

---

# Probability
    Probability is the mathematics, it assigns a number between 0 and 1 to how likely an event is.
$$0 \le P(A) \le 1 $$
    Modern probability began in the 17th century with problems about games of chance and was eventually formalized into mathematical probability theory by Andrey Kolmogorov in 1933.
	

---
There are three paradigmatic ways of introducing linear algebra which we can classify as elementary, computational, and abstract. 

# Three ways of defining Linear Algebra
|  Classification  |  Definition  |
|----|----|
|  Elementary  |  Linear Algebra is the study of vectors, matrices, systems of linear equations, and problems that can be solved using linear algebraic techniques  |
| Abstract   | Axler defines Linear Algebra as "the study of linear maps on finite-dimensional spaces" (Axler, 2015)  |
|  Computational  |  "Linear Algebra is the study of vectors and ways of manipulating vectors" (Deisenroth, 2020) |




---
# There are three core concepts in linear algebra
	Scalar $\lambda \in \mathbb{R}$ 
	We can think of a scalar as a single value, usually a real number
	Vector 
	Example Vector $a = \begin{bmatrix} 1\\2\\3 \end{bmatrix} \in \mathbb{R}^3$ Vectors are objects that we add together and multiply by a scalar to get another vector. 

	Matrix A $m\times n$ matrix is a collection of elements consisting of $m$ rows and $n$ columns. We  can think of matrices as a collection of vectors or a linear transformation
	Example Matrix 
	$A = \begin{bmatrix} 1 & 3 & 5 \\ 8 & 2 & 1 \\ 3 & 3 & 4 \end{bmatrix}$




---
# History of Linear Algebra
	Linear algebra encompasses many techniques that evolved over time and in several places including China, Europe, Greece, and Egypt

	In the 19th century James Joseph Sylvester and Arthur Cayley introduced algebraic techniques for linear algebra and coined the term matrix, which comes from the Latin term for womb 

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

/assets/Clipboard 7.png
size: contain


---
# Linear Algebra and Data
	Linear algebra provides tools for representing and working with structured data.
	- A vector can represent one observation, with each entry recording a measured feature.
	- A matrix can organize many observations and variables in a single structure.
	- Matrix operations can combine, compare, and transform data, and help solve systems of equations.
	- These tools are used across fields to study relationships and patterns in data, from population tables to images.

	How data is organized into vectors and matrices reflects choices about what is measured and how.

---
# Modes of Reasoning with Data
	**Deductive reasoning**
	Deductive reasoning means moving from premises to conclusions by drawing valid inferences. A valid inference means that it logically follows from the premises
	**Inductive reasoning**
	Inductive reasoning is where generalizations or principles are made from a body of observations. For example, machine learning can be considered a form of automated induction.


---
# Genealogy of Statistics and Scientific Racism
To illustrate the historical link between statistics and scientific racism, I’ll provide four figures and three well-known examples in statistics and measurement. These case studies illustrate how choices and racial logics become naturalized and made to seem objective through mathematical methods.

/assets/Clipboard 11.png
background: true
opacity: 30%

---

	**Where Did Statistics Come From?**
	'Statistik' was coined by Gottfried Achenwall in 1749, and he thought of what he called statistics as the collection of 'remarkable facts about the state'.
	Statistics evolved out of the study and quantification of the state: large-scale efforts to conduct censuses, measure populations, and track state-relevant metrics (Hacking, 1990).

/assets/Clipboard 8.png
size: contain

/assets/Clipboard 9.png
size: contain


---

	“One can tell the story of biopolitics as the transition from the counting of hearths to the counting of bodies. The subversive effect of this transition was to create new categories into which people had to fall, and so to create and to render rigid new conceptualizations of the human being.” 
	(Hacking, 2015, p. 281)



---
# Social Statistics and Social Physics
	*folks as a collective*
	Social Statistics or Social Physics sought to discover immutable statistical laws that governed society

# Biometrics and Anthropometry 
	*The individual bodies that make up folks*
	Emerging from 19th century study of physiognomy and phrenology, the body became a target for quantification and measurement to track norms and deviances

Galton, F. (1885). On the Anthropometric Laboratory at the Late International Health Exhibition. The Journal of the Anthropological Institute of Great Britain and Ireland, 14, 205–221. https://doi.org/10.2307/2841978 pg 219




---
# Key figures
	- Adolphe Quetelet
	- Francis Galton
	- Karl Pearson
	- Alphonse Bertillon

---
# Methods for Quantification and Measurement
- Average
- Pearson Correlation and Regression toward the mean
- Principal Component Analysis

---

# Adolphe Quetelet (1796-1874)
	Belgian statistician, astronomer, and sociologist
	Founded the science of anthropometry and created the body mass index (BMI)
	developed the notion of the *homme moyen* or average man and was an important thinker in the development of eugenics
	Quetelet's move was to treat human traits using probability as if they were measurement errors scattered around a true value, the *homme moyen* or “average man.”

/assets/Clipboard 33.png
size: contain


---
# What is an Average
	Mathematically we can represent an average as:
$$\overline x = \frac{1}{n} \sum^n_{i=1}x_{i}$$
	but an average can also be a knowledge claim based on data


---
	“we thus arrive in inquiries of this kind, at the fundamental principle: that the greater the number of individuals observed, the more do individual particularities, whether physical or moral, become effaced, and leave in a prominent point of view the general facts, by virtue of which society exists and is preserved.”
	— Adolphe Quetelet, 1835


---

	In the preceding quote, Quetelet lays down the philosophical grounding for what an average is and what claims we can make about that data. Statistically we can define a common or average as a typical specimen


---

# Sir Francis Galton (1822-1911)
	- English Statistician, psychologist and anthropologist
	- Cousin of Charles Darwin and sought to bring Darwin’s theories into the study of society
	- Coined the term eugenics

/assets/Clipboard 1.png
size: contain

---
# A tale of two exhibitions

## Exhibit of American Negroes at the Paris World's Fair (1900)
/assets/Clipboard 13.png
size: contain

https://www.smithsonianmag.com/history/first-time-together-and-color-book-displays-web-du-bois-visionary-infographics-180970826/

## Galton’s Anthropometric Laboratory at the 1884 International Health Exhibition at South Kensington
/assets/Clipboard 14.png
https://publicdomainreview.org/essay/the-anthropometric-detective-and-his-racial-clues/



---

# The Anthropometric Laboratory
    International Health Exhibition, South Kensington, 1884
    - 9,337 people measured in 17 ways (Galton, 1885, p. 206)
    - About 90 people a day in a space 36 feet long and 6 feet wide
    - Visitors paid 3d. and received a card of their results
    - Measured: sight, color sense, judgment of eye, hearing, breathing, strength, swiftness of blow, arm span, height, weight

    “The object of the laboratory was to show to the public the simplicity of the instruments and methods by which the chief physical characteristics of man may be measured and recorded.” (p. 205)

/assets/Clipboard 16.png
size: contain


---
/assets/Clipboard 16.png
background: true
opacity: 30%

/assets/Clipboard 25.png
size: contain


---

### “The theory of hereditary genius, though usually scouted, has been advocated by a few writers in the past as well as in modern times. But I may claim to be the first to treat the subject in a statistical manner, to arrive at numerical results, and to introduce the “law of deviation from average” into discussions on heredity.”
	Galton, F. (1869). Hereditary genius: An inquiry into its laws and consequences. Macmillan.

---

# Two Ways of Measuring
|  |  Du Bois (Paris, 1900)  |  Galton (London, 1884)  |
|----|----|----|
|  Measures  |  Social conditions: education, land, occupation  |  Individual bodies and faculties: height, strength, senses  |
|  Presented as  |  Hand-drawn charts and photographs  |  Instruments, cards, a schedule  |
|  Explanation sought  |  Social and historical causes  |  Heredity (in his later work, e.g. *Hereditary Genius*)  |


---
# Measurement as Mode of Discipline
    “The use of periodical measurements is two-fold, personal and statistical. The one shows the progress of the individual; the other that of portions of the nation, or of the nation as a whole.” (p. 213)
	Galton proposed periodic measurement as “a recognised part of school discipline” (p. 207)


---

# Pearson Correlation and Regression Toward the Mean
	- Pearson correlation is widely used in statistics in the social sciences. Sir Francis Galton developed techniques for correlation and regression to study heredity in populations.
	- Further developed by Karl Pearson to support his analysis of data and arguments for the intellectual superiority of the Aryan race. 


---
# Mathematics of the Pearson Correlation
    The Pearson correlation coefficient measures how strongly two variables move together:
$$r = \frac{\sum_{i=1}^n (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum_{i=1}^n (x_i - \bar{x})^2}\,\sqrt{\sum_{i=1}^n (y_i - \bar{y})^2}}$$
    $r$ ranges from $-1$ to $1$. It has no units, so measurements in inches and pounds can be compared on one scale.

---
# Regression Toward the Mean
	When one sample of a random variable is extreme then the next sample is likely to be closer to its mean. Galton argued that this illustrated a reversion to mediocrity in populations.

	This can be understood in terms of intelligence: over the course of generations without intervention, intelligence in *good stock* will regress to the mean.


The line that predicts $y$ from $x$:
\hat{y} = \bar{y} + r\,\frac{s_y}{s_x}(x - \bar{x})$$
When $|r| < 1$, a prediction sits closer to the mean than the value it is based on. Galton saw this in the measurements of parents and children (Galton, 1886).


---
# Pearson correlation functions as an instrument for measuring sameness and difference. Originally, it was developed for explicitly racialized and eugenicist reasons.

---

# Galton believed heredity could be analyzed probabilistically
	- Regression (toward the mean) **the offspring tend toward the mean of the race**
	- Correlation **one factor’s dependency on another could be measured (even if they are in different, seemingly incommensurable units)**


---
# Karl Pearson (1857-1936)
	- English Biostatistician and Mathematician, founded the world's first statistics department at University College London in 1911
	- Developed many statistical techniques, including PCA, the chi-squared distribution, contingency tables, histograms, the mode, and the Pearson distribution
	- Proponent of social darwinism and eugenics, mentee and biographer of Galton

/assets/Clipboard 12.png
size: contain
caption: Karl Pearson with Sir Francis Galton (1910)

---
# Principal Component Analysis and Dimensionality Reduction
	PCA is a technique for dimensionality reduction that transforms data to a simpler representation that retains the most important information. Often used in exploratory data analysis.
	Principal component analysis was first developed as a technique by Karl Pearson in 1901



---
# Principal Component Analysis
	PCA finds patterns of variation across measured variables and summarizes them as new components.

	But a component is not simply “in” the people being measured. It depends on:
	- Which people are included
	- Which traits are measured, and how
	- Which variables are combined or standardized
	- Which patterns the analysis treats as important
	
	The mathematics works on the data it is given. It cannot tell us whether the data collection choices were fair or meaningful.



---
# How Choices Become Social Facts
	Consider a study that measures bodies and searches for patterns among them.
	Choosing the population, the measurements, and the units shapes the covariance matrix. PCA then returns components that are mathematically optimal for that matrix. If researchers interpret those components as innate differences between groups, the analysis can make those differences appear discovered rather than constructed through choices about measurement and interpretation.

The calculation may be rigorous. The categories and conclusions built around it still require scrutiny.

---
# Biometrics, PCA, and Eugenic Reasoning
	Karl Pearson developed his 1901 method for fitting lines and planes to observations within a broader biometric project of measuring variation in populations. Pearson was also a eugenicist.


---

# Alphonse Bertillon (1853-1914)
	- French criminologist and biometrics researcher
	- Developed and standardize the mug shot and created the first criminal photo database from anthropometric data

/assets/Clipboard 31.png
size: contain

---

# “Every measurement slowly reveals the workings of the criminal. Careful observation and patience will reveal the truth.” 
	– Alphonse Bertillon
/assets/Clipboard 32.png
background: true
opacity: 20%


---
# Francis Galton
	individual $\to$ type
	Galton sought to inductively discover types through statistical studies of heredity to discover how some led to the elevation and others to the decline of a race or society.

# Alphonse Bertillon
	type $\to$ individual
	Using photography, Bertillon developed a “database” of criminal types based on the measurement of physical attributes that could be used to convict individuals.



---
# Facial Recognition Technology, Bias, and the Politics of Recognition
/assets/Clipboard 30.png
background: true
opacity: 20%

---
# The Mathematics of Facial Recognition
	From image to mathematical representation and computational object
	**1. Image as matrix**
	A photo is a grid of pixel values, $I \in \mathbb{R}^{h \times w \times 3}$
	**2. Face as vector**
	Software detects landmarks and extracts features, converting a face into a vector of numbers (an "embedding"): $f(I) \in \mathbb{R}^{n}$

	**3. Similarity as distance**
	Two faces are compared by the distance between their vectors:
$$d(u, v) = \|u - v\|$$
	**4. Identity as threshold**
	A match is declared when $d(u, v) < \tau$ for some threshold $\tau$ 

---
# The Geometry of the Face
	A face can be treated as a set of points in space
	**2D landmarks:** $p_i = (x_i, y_i)$ for eye corners, nose tip, mouth corners, jawline
	**3D mesh:** vertices $V \in \mathbb{R}^{n \times 3}$ connected into triangles, approximating the surface of the face
	**Geometric measures:** distances and ratios between points
	**Alignment:** rotating, scaling, and translating the points to a standard pose before comparison

---
# Bertillon's Measurements, Automated
    Bertillon recorded fixed bodily measurements (head length, ear, nose) and described faces with a standardized vocabulary. Facial recognition systems also turn a face into measured geometry, but compute it automatically and at massive scale.

What changed: the instrument (camera and algorithm). What persisted: the premise that a person can be reduced to measurements, and that a database of those measurements can identify and classify people.

---
# Apple Face ID: Depth and Mesh
    - **Projection:** the TrueDepth camera projects over 30,000 invisible infrared dots onto the face
    - **Depth map:** distortion of the dot pattern gives a distance $z$ for each point, so the face becomes a surface $z = D(x, y)$
    - **Mathematical representation:** a neural network converts the depth and infrared data into a numerical template, stored in the Secure Enclave on the device
    - **Comparison:** a new scan is compared to the stored template, with adaptation over time

    Developers get a related geometry through ARKit: a face mesh of 1,220 vertices and 2,304 triangles that tracks expression in real time.

---
# Amazon Rekognition: 2D Landmarks
    Rekognition works from ordinary 2D photographs, not depth sensors. Detect Faces returns:
    - **Bounding box** around the face
    - **Landmarks:** coordinates for eyes, nose, mouth, and face outline, given as ratios of image width and height
    - **Pose:** roll, yaw, and pitch (the 3D rotation of the head estimated from a 2D image)
    - **Quality:** brightness and sharpness
    - **Attributes with confidence scores:** such as gender, age range, and emotion

    Landmarks are geometry. Attributes are interpretations laid on top of the geometry.

---
# Amazon Rekognition
/assets/Clipboard 30.png
size: contain

---
# Detect Faces API
	Rekognition detects faces in images and videos and identifies facial landmarks and other attributes. Rekognition then returns confidence scores for each attribute


/assets/Clipboard 29.png

/assets/Clipboard 27.png


---
# Dr. Joy Buolamwini
    - Computer scientist, founder of the Algorithmic Justice League
    - Face detection software failed to detect her face until she put on a white mask
    - *Gender Shades* (Buolamwini & Gebru, 2018) tested gender classification from IBM, Microsoft, and Face++

/assets/Clipboard 37.png
size: contain

---
# Gender Shades (2018)
    - Common benchmark datasets skew male and lighter-skinned (Labeled Faces in the Wild: about 77% male, over 80% white).
    - The Pilot Parliaments Benchmark uses parliamentarians from three African and three European countries, balanced by gender and skin type.
    - Error rates: as high as 35% for darker-skinned women, no more than 1% for lighter-skinned men.

/assets/Clipboard 38.png
size: contain

---
# Race and Gender Bias in Amazon Rekognition
    Raji and Buolamwini (2019) audited Rekognition’s gender classification with the same benchmark (data collected August 2018).
    - Flawless performance on lighter-skinned men
    - 68.6% accuracy on women of color (Buolamwini, 2019)
    Amazon disputed the findings, saying the audit tested facial analysis, not facial recognition.


/assets/Clipboard 26.png
size: contain



---
# Thresholds Are Choices
    Rekognition returns a label with a confidence score. In Buolamwini’s example, a photo of Oprah Winfrey was labeled “male” at 76.5%.

    - Reported accuracy depends on the threshold chosen: IBM reported darker-skinned women going from 65.3% to 96.6% at a 0.99 threshold
    - Amazon recommended 0.99 in one context and 0.95 in another; one police client reported not setting a threshold at all
---
# Where the Choices Are
    Each step involves human decisions that get built into the system:
    - **Training data:** whose faces were collected, and how they were labeled
    - **Features:** which landmarks and attributes count
    - **Threshold $\tau$:** how much error is acceptable, and for whom
    - **Categories:** what the system is asked to classify (gender, age, emotion) and how these categories are constructed

## A mathematically precise output can hide the choices behind it, which is what Raji and Buolamwini's audit made visible.

---

/assets/Clipboard 28.png
size: contain

---

# Du Bois's work was not just a disagreement with the racialism of the social scientific practitioners of his day—it was an attempt to do the work of science differently.

---
# Takeaways
    - Measurement is a set of choices about what, who, how, and which categories, not a neutral recording
    - Mathematical methods can make choices appear as if they are facts about nature
    - Standard instruments, records, categories, and thresholds from in biometrics then show up in facial recognition now
    - Du Bois shows data practice can be done differently

---
# Discussion
	- What should we do about the racialized history of modern measurement and quantification methods?
	- Who defines the categories being measured?
	- What would it mean to do the work of measurement differently, as Du Bois did?


---
# Sources
	Dixon-Román, E. (2025). Blackness & Measurement. Educational Studies, 61(4), 403–416. https://doi.org/10.1080/00131946.2025.2550024
	Stevens, S. S. (1946). On the Theory of Scales of Measurement. Science, New Series, 103(2684), 677–680.
	Galton, F. (1885). On the Anthropometric Laboratory at the Late International Health Exhibition. The Journal of the Anthropological Institute of Great Britain and Ireland, 14, 205–221. https://doi.org/10.2307/2841978
	Galton, F. (1869). Hereditary genius: An inquiry into its laws and consequences. Macmillan.
	Miller, J. (2019, May 25). Amazon shareholders reject proposal to limit sales of AWS face recognition software. TechSpot. https://www.techspot.com/news/80232-amazon-shareholders-reject-proposal-limit-sales-aws-face.html
	Buolamwini, J. (2019, April 24). Response: Racial and Gender bias in Amazon Rekognition — Commercial AI System for Analyzing Faces. Medium. https://medium.com/@Joy.Buolamwini/response-racial-and-gender-bias-in-amazon-rekognition-commercial-ai-system-for-analyzing-faces-a289222eeced
	Womack, A. (2021). The Matter of Black Living: The Aesthetic Experiment of Racial Data, 1880–1930. University of Chicago Press. https://doi.org/10.7208/chicago/9780226806884.001.0001
	Noble, S. U. (2018). Algorithms of oppression: How search engines reinforce racism. New York University Press.
