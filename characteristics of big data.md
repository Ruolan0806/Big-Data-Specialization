# Characteristics Of Big Data

Is usualy caracterized using a number of V's.

The three most importants: Volume, Velocity and Variety.
 
## Volume

Refers to vast amounts of data that is generated every second.

	Volume == Size
	
Email, photo, Videos

There are a number of **challenges** related to the massive volumes of Big Data 

`Storage` -> `Distribution` -> `Processing`

`Data Acquisition`

`Retrieval`

The challenges include **cost, scalability and performance** related to their **storage, acess and processing**.

## Variety

Refers to the ever increasing different forms that data can come in such as text, images and geospatial data.

	Variety == Complexity
	
Variety is a form of scalability.

Today data are more heterogeneous:

**Structural Variety**: formats and models

**Media Variety**: medium in which data get delivered

**Semantic Variety**: how to interpret and operate on data

**Availability Variation**: real-time? intermittent?


## Velocity 

Refers to the speed that which data is being generated.

	Velocity == Speed
	
* Speed of creating data
* Speed of storing data
* Speed of analyzing data


**Batch Processing** (Incomplete)

	Collect Data -> Clean Data -> Feed in chunks -> Wait -> Act 

**Real-Time Processing** (Fast)

	Instantly capture stream data -> Feed real time to machines -> Precess real time -> Act
	
	
* Faster decision

## Veracity

Refers to biases, noises and abnormality in data.

	Veracity == Quality
	
**Validity** and **Volatity**

- Accuracy of data
- Reliability of data source
- Context within analysis

Unstructed data form the internet is imprecise and uncertain.

Example of Google Flu Trends: Uncertain, Provenance


## Valence

Refers to the connectendness of big data in forms of graphs.

	Valence == Connectendness
	
Measure of connectivity

* **Data Connectivity**: Two data items are connected when they are releated to each other
* **Valence**: Fraction of data items that are connected out of the total number of  possible connections

Challenges:

* More complex data exploration algorithms
* Modeling and prediction valence changes
* Group event detection
* Emergent behavior analysis
	

## Value

Heart of Big Data challenge

Starting to generate value from Big Data


**Data source**:

* Machine - User activity logs
* People - Twitter conversations
* Organization - User demografic info/Game stats


### A “Small” Definition of Big Data

The term ‘big data’ seems to be popping up everywhere these days. And there seems to be as many uses of this term as there are contexts in which you find it: ‘big data’ is often used to refer to any dataset that is difficult to manage using traditional database systems; it is also used as a catch-all term for any collection of data that is too large to process on a single server; yet others use the term to simply mean “a lot of data”; sometimes it turns out it doesn’t even have to be large. So what exactly is big data?

A precise specification of ‘big’ is elusive. What is considered big for one organization may be small for another. What is large-scale today will likely seem small-scale in the near future; petabyte is the new terabyte. Thus, size alone cannot specify big data. The complexity of the data is an important factor that must also be considered.

Most now agree with the characterization of big data using the 3 V’s coined by Doug Laney of Gartner:

· Volume: This refers to the vast amounts of data that is generated every second/minute/hour/day in our digitized world.

· Velocity: This refers to the speed at which data is being generated and the pace at which data moves from one point to the next.

· Variety: This refers to the ever-increasing different forms that data can come in, e.g., text, images, voice, geospatial.

A fourth V is now also sometimes added:

· Veracity: This refers to the quality of the data, which can vary greatly.

There are many other V's that gets added to these depending on the context. For our specialization, we will add:

· Valence: This refers to how big data can bond with each other, forming connections between otherwise disparate datasets.

The above V’s are the dimensions that characterize big data, and also embody its challenges: We have huge amounts of data, in different formats and varying quality, that must be processed quickly.

It is important to note that the goal of processing big data is to gain insight to support decision-making. It is not sufficient to just be able to capture and store the data. The point of collecting and processing volumes of complex data is to understand trends, uncover hidden patterns, detect anomalies, etc. so that you have a better understanding of the problem being analyzed and can make more informed, data-driven decisions. In fact, many consider value as the sixth V of big data:

· Value: Processing big data must bring about value from insights gained.

To address the challenges of big data, innovative technologies are needed. Parallel, distributed computing paradigms, scalable machine learning algorithms, and real-time querying are key to analysis of big data. Distributed file systems, computing clusters, cloud computing, and data stores supporting data variety and agility are also necessary to provide the infrastructure for processing of big data. Workflows provide an intuitive, reusable, scalable and reproducible way to process big data to gain verifiable value from it in and enable application of same methods to different datasets.

With all the data generated from social media, smart sensors, satellites, surveillance cameras, the Internet, and countless other devices, big data is all around us. The endeavor to make sense out of that data brings about exciting opportunities indeed!

# Quiz

1. Amazon has been collecting review data for a particular product. They have realized that almost 90% of the reviews were mostly a 5/5 rating. However, of the 90%, they realized that 50% of them were customers who did not have proof of purchase or customers who did not post serious reviews about the product. Of the following, which is true about the review data collected in this situation?

	Low Veracity

2. As mentioned in the slides, what are the challenges to data with high valence?

	Complex Data Exploration Algorithms

3. Which of the follow is NOT one of the 6 V's in big data?

	Vision

4. What is the veracity of big data?

	The abnormality or uncertainties of data.

5. What are the challenges of data with high variety?

	Hard to integrate

6. Which of the following is the best way to describe why it is crucial to process data in real-time?

	Prevents missed opportunities.

7. What are the challenges with big data that has high volume?

	Cost, Scalability, and Performance
	
	
# Getting Value out of Big Data

Explain why data science is the key to getting value out of Big Data.

List the right set of skills for a data scientist to fit your organization.

	Big Data - Insight - Action
	
Insight -> Data Product

Big Data + Analysis + Questions -> Insights

Data Science is not static = Recommendation Systems


	Historical Data + Near real-time data -> Prediction
	
Data Science is Team Work

	Computer Science + Mathematics + Business Expertise
	TEchnical Skills + Businnes Skills + Soft Skills
	
* Have passion for data
* Relate problems to analytics
* Care about engineering solutions
* Exhibit curiosity
* Communicate with teammates


# Building a Big Data Strategy

Strategy: Aim - Policy - Plan - Action

BigData strategy starts with big objectives

What data to collect?

**Business Objectives**

* Commitment
* Sponsorship
* Communication

**Build diverse team**

* Diverse team
* Deliver as a team

**Training**

**Share data**

Is key to any big data initiative

**Define big data policies**

**Cultivates analytics-driven culture**

	Communication Goals -> Build teams -> Share data -> Adapt for new situations -> Integrate analytics


# How does big data science happen?: Five Components of Data Science

* People
* Purpose
* Process
* Platforms
* Programability


Big Data Engineering    Computational Big Data Science

Acquire -> Prepare -> Analyze -> Report -> Act

**Rate of spread and direction**

Build 
  |
Explore 
  |     Report - Act
Scale   


Hadoop Plataform

Process: Build metrics for accountability

* Cost
* Timeline
* Planning of deliverables
* Expectations
* Purpose

*We define data science as a multidisciplinary craft that combines people, process, computational and Big Data platforms, application-specific purpose and programmability.*

# Asking the Right Questions

* Define the Problem
* Assess the situation
	* Risk
	* Benefits
	* Contigencies
	* Regulations
	* Resources
	* Requirements
* Define goals
	* Objectives
	* Criteria 
* Formulate the Questions


# Steps in the Data Science Process

## Step 1: Acquiring Data

Is to determine what data is available.

**Script Languages**

* Tradicional Databases
* WebService
* Txt Files
* NoSQL Storage

## Step 2: Prepare

### Step 2-A: Exploring Data

Goal: Understand your data.

Look for things with correlation.

Visualize your data:

* Histogram
* Line graphs
* Heat maps
* Scatter plotts

### Step 2-B: Pre-processing Data

Clean + Transform

* Inconsistent values
* Duplicate records
* Missing values
* Invalid data
* Outliers

1. Addressing Data Quality Issues
	* Remove data with missing values
	* Merge duplicated records
	* Generate best estimate for invalid values
	* Remove oultiers

2. Getting Data in Shape
	* Data manipulation/Data preprocessing/Data wranglig

3. Feature Selection
	* Remove feature
	* Combine features
	* Add feature
	
4. Dimensionality Reduction
	
### Step 3: Analyzing Data

Build a model from your data

Input Data -> Analysis Technique -> Model -> Model Output

Categories of analysing data:

* Classification: Predict category
* Regression: Predict numeric value
* Clustering: Organize similar items into groups
* Graph analysis: Use graph structures to find connections between entities
* Association analysis: Find rules to capture associations between items

**Modeling**:

* Select techinique
* Build model
* Validate model

### Step 4: Communicating Results

What to present?
How to present?

D3.js
Leaflet.js

### Step 5: Turning Insights into Action
