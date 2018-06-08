---
# Page settings
layout: default
keywords: [ai, glossary, terms, concepts, artificial intelligence, neural network]
comments: false

# Hero section
title: AI Glossary
description: Concepts and terms used in AI

# Author box
author:
    title: Clint Francis
    title_url: '#'
    external_url: true
    description: Author description

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Previous page
        url: '#'
    next:
        content: Next page
        url: '#'
---

## Concepts and Terms

There are a lot of the concepts and terms in the field of AI can be intimidating for newcomers to the space. This page will be maintained as an ever growing glossary of terms and 'things to know'. To help break things down I've grouped the entries into three categories [*"Things you should know"*](#ThingsYouShouldKnow), [*"Going deeper"*](#GoingDeeper) and [*"Down the rabbit hole"*](#DownTheRabbitHole).

## <a name="ThingsYouShouldKnow">Things You Should Know

#### <a name="Algorithm"></a>Algorithm
Generally speaking, the most important part of AI is the Algorithm. An Algorithm is a mathematical formula or set of commands that dictate how a process should be applied when solving a problem. Alternatively it could be described as "a set of rules that precisely defines a sequence of operations".

#### <a name="ArtificialIntelligence"></a>Artificial Intelligence (AI)

_Artificial Intelligence_ refers to computer simulated ‘intellectual processes’ such as the ability to reason, discover meaning, generalise, or learn from past experience.

#### <a name="Autonomous"></a>Autonomous

Autonomy in AI essentially means that the system is able to operate without external guidance or intervention. One of the most popular examples is the concept of driverless cars that are able to drive and operate without a human driver's input. Currently driverless cars do require some external guidance, from both navigation grids and human drivers who provide a safety net. In the future the hope is to obtain completely autonomous vehicles that are capable of operating independently.

#### <a name="BlackBox"></a>Black box

In programming terms a black box is an unknown set of operations. We can observe the data that goes in and the data that is returned, however we are not able to see (or understand) the calculations that take place 'within the box'. In AI, a black box often refers to the learning process where the actual computations are difficult for us to comprehend, however we're not all that concerned with _exactly how_ the algorithm produced its output.

#### <a name="ChatBots"></a>Chat Bots

A chatbot is used to simulate a conversational exchange, with users able to interact with the bot using natural language. Chatbots typically use dialog based interactions (you say, I say) to process blocks of the conversation, each block provides the bot with information about the users intent.

Chat bots are used a wide range of purposes, with the most common use cases being in commerce and help desk support. 

#### <a name="CognitiveComputing"></a>Cognitive computing

Cognitive computing is concerned with simulating human thought processes such as vision, speech, reasoning etc.

Cognitive computing involves self-learning systems that can learn as information changes, and as goals and requirements evolve.

#### <a name="DataScience"></a>Data science
Data Science is an interdisciplinary field that unifies concepts from statistics, data analysis, and machine learning in order to understand and analyse events.

Data scientists are employed help organisations to turn raw data into valuable business information.

#### <a name="DataMining"></a>Data mining

Data mining is the act of extracting patterns in large data sets, the term is somewhat misleading as 'data mining' is not concerned with the extraction of the data itself. 

Before the data can be processed it needs to be transformed into an understandable structure. Artificial Neural Networks often require large amounts of data to train their internal models and this data first needs to prepared into a consistent structure before it is processed.

#### <a name="MachineLearning"></a>Machine learning

Machine Learning refers to the ability of a machine to learn using large data sets instead of being explicitly programmed. Machine learning algorithms are often typically grouped by learning style (i.e [supervised](SupervisedLearning) or [unsupervised](UnsupervisedLearning)) or by their similarity in form or function (i.e. [decision tree](#DecisionTree), [deep learning](#DeepLearning), etc).

Regardless of which grouping is used, machine learning algorithms are composed of three core components:

- **Representation**  
	A classifier or language that the computer can understand.
- **Evaluation**  
		An evaluation function used to distinguish a good classifier from a bad one.
- **Optimisation**  
	A method for searching through all the classifiers for the highest scoring one.

The fundamental goal of machine learning is to generalise beyond the examples in the training set. 

#### <a name="NaturalLanguageProcessing"></a>Natural Language Processing (NLP)

The goal of natural language processing is to allow interaction between humans and computers using _our_ own language. NLP makes it possible for computers to read text, hear speech, interpret it, measure sentiment and determine which parts are important. 

The use cases for NLP go far beyond just speech recognition and can be applied to a variety tasks suck as automatic summarisation, translation, named entity recognition, relationship extraction, sentiment analysis, speech recognition, and topic segmentation.

#### <a name="Model"></a>Model

In AI a model is an abstract concept that refers to the trained (or yet to be trained) artefact created by the [machine learning](#MachineLearning) process. Once a model has been trained it can be used to predict the outcome of new data.


#### <a name="TuringTest"></a>Turing test

The Turing test is a way of testing the 'intelligence' of a computer or AI system. To pass the Turing test a human should be unable to distinguish between the system and another human being by evaluating the replies put to both. The test is named after Alan Turing, an English mathematician who pioneered machine learning during the 1940s and 1950s.

#### <a name="StrongAI"></a>Strong AI

Strong AI describes a hypothetical system that exhibits behaviour on par with human intellect, it is also sometimes referred to as _artificial general intelligence_. There are currently no systems that can be considered as Strong AI.

#### <a name="WeakAI"></a>Weak AI

Weak AI is artificial intelligence that is focused on one narrow task. Currently _all_ AI systems can be considered as Weak AI as they are not able to operate outside the bounds of their initial making and lack general intelligence.

## <a name="GoingDeeper"></a>Going Deeper

#### <a name="ArtificialNeuralNetwork"></a>Artificial Neural Network (ANN)

An Artificial Neural Network is computer model intended to simulate the way humans learn. Neural Networks "learn" by considering examples, generally without being programmed with any specific rules. They excel at finding patterns which are far too complex for human programmers to implement.

Neural networks are made up from multiple 'layers'. They have both input and output layers but also contain (in most cases) hidden layers that transform the inputs into something that the output layer can use.

Each layer contains multiple connected 'artificial neurons' that allow signals to pass through in a single direction. When a neuron receives a signal it process it and then forwards the signal on to additional neurons connected to it. The connections between neurons are called 'edges'. Each of the neurons and edges typically have a [weight](#Weights) that adjusts as learning proceeds. Its this weighting that helps to determine the final output from the Neural Network. 

 Artificial Neural Networks are often used in cognitive computing (Computer vision, speech recognition, machine translation, etc).

#### <a name="Heuristics">Heuristics

A heuristic is a technique designed for solving a problem quickly when classic methods are too slow, or for finding an approximate solution when classic methods fail to find any exact solution. Heuristic methods are not guaranteed to find an optimal solution to the problem but will provide a satisfactory outcome most of the time.

For more information see [Wikipedia](https://en.wikipedia.org/wiki/Heuristic_(computer_science)).

#### <a name="DeepLearning"></a>Deep learning

The “Deep” in Deep Learning refers to having more than one hidden layer within an [Artificial Neural Network](#ArtificialNeuralNetwork). 

#### <a name="DecisionTree"></a>Decision tree

A decision tree is a flowchart like structure that guides a decision process from start to finish. The process is routed according to the requirements of each 'node' in the flowchart with a final decision reached at the conclusion of the path.

Main advantage of decision trees is that they are a 'white-box' method. This means that we can easily explain their decisions, in contrast to the [Neural Networks](#ArtificialNeuralNetwork) whose complexity is usually too high to easily understand (see [Black Box](#BlackBox)). 

#### <a name="GPU"> GPU

A graphics processing unit (GPU) is type of specialised computer chip with a highly parallel structure. GPU's are more efficient than general-purpose CPUs for algorithms where the processing of large blocks of data is done in parallel. Originally created to offload graphics processing from a computers CPU, GPU's are increasingly being used for processing algorithms used in technologies such as [Machine Learning](#MachineLearning) and BlockChain. 

## <a name="DownTheRabbitHole"></a>Down The Rabbit Hole

#### <a name="Weights"></a>Weights

Each neuron in an [artificial neural network](#ArtificialNeuralNetwork) has a set of inputs, each of which is given a specific weight. The neuron performs a function on the weighted sum of the inputs and returns a value between 0 and 1. This value is then transmitted to other neurons as its output. 

During the training process (supervised/unsupervised) the weights get adjusted so as to account for the relation between the input & the output.

#### <a name="ReinforcementLearning"></a>Reinforcement Learning

Reinforcement learning is inspired by behavioural psychology, and is concerned with how software agents should take actions in an environment to maximise some notion of cumulative reward. In a similar way to how humans learn through interaction, reinforcement learning is a computational approach to learning through actions. If we consider a reinforcement learning model as a loop, there are three elements: *state*, *action* and *reward*.
 The agent receives a *state* from the environment, then acting on the *state* the agent takes an *action*. Dependent upon whether the action is desirable or not the agent is given a *reward*, and so the loop repeats. 

#### <a name="SupervisedLearning"></a>Supervised learning
Supervised learning algorithms can apply previous learnings to new data to predict future events. The algorithm begins with a known and labelled training dataset which is used to base the predictive model upon. After sufficient training the system should be able to correctly distinguish between and categorise new unlabelled data.

For example in supervised learning for image processing, an AI system might be provided with labelled pictures of animals in categories such as cats and dogs. After training the system should be able to sort and label any new images as either a cat or a dog.

#### <a name="TransferLearning"></a>TransferLearning

Transfer learning is an algorithm that builds upon an already existing model as the starting point for a second task.

Transfer learning is widely used in deep learning where a pre-trained model is used as the starting point for tasks like computer vision and [natural language processing](#NaturalLanguageProcessing). For example, a pre-trained model that can recognise cars could be used as a starting point when trying to recognise trucks.

#### <a name="UnsupervisedLearning"></a>Unsupervised learning

Unsupervised learning algorithms are used when the information used to train is neither classified nor labeled. Unsupervised learning studies how systems can infer the hidden structure from unlabelled data. The system doesn’t figure out the right output, but it explores the data and can draw inferences from datasets to describe hidden structures from unlabelled data.