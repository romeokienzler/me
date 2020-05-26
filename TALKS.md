# Privacy-preserving machine learning
Data privacy is a huge concern and often prevents ML and AI project from flourishing.

In this talk we’ll introduce you to federated learning and homomorphic encryption. After we’ve covered the theoretical aspects we’ll see
how they can be used in practice. 

We conclude with an outlook on the future of these technologies.

# Trusted AI – Building Reproducible, Unbiased and Robust AI Pipelines using the python OpenSource stack
 
We are just in the middle of the DeepLearning hype. A lot of things are done, but production deployments are still rare. One of the reasons is that untrusted AI doesn’t make it into production. The concerns are just too high. In this talk we’ll show how data lineage, bias detection, adversarial robustness and model explainability can be achieved using an open source stack


# The Open ML and AI DevOps toolsuite of the future
 
In 2019 we've noticed a tremendous shift of client demand on model creation to model deployment and monitoring. This indicates a further step towards maturity of wider AI adoption within enterprises. In this talk we'll introduce you to the latest developments in the most widely used DeepLearning framework TensorFlow 2.1. We show how Kubernetes and Kubeflow Pipelines work and how Open Data Hub provides a Open Source powered platform for data science. Finally, we show you an end to end project example of a product using all of those components in harmony.

# Building Brains - Parallel training strategies of large-scale deep learning neural networks
 
DeepLearning is so powerful that it rapidly transforms the Machine Learning space. But DeepLearning is very resource and data hungry. In this talk we show how neural network training works and how it can be parallelized on large scale GPU clusters using inter-model, intra-model, data  and pipelined parallelism. We’ll use TensorFlow 2.0 for demonstration purposes.

# Towards de-facto standard in AI: TensorFlow 2.0 and KubeFlow
 
*Short Abstract*: TensorFlow was the hype in 2015. But we discovered many flaws, most of them addressed by Keras and PyTorch. TensorFlow V2 addressed all those and even went beyond what we could imagine in our wildest dreams! This seems to make other frameworks obsolete. In addition, by running natively on Kubernetes using KubeFlow, TensorFlow V2 has the potential to become the de-facto standard for any AI project
 
Abstract: Towards the End of 2015 Google released TensorFlow, which started out as just another numerical library, but has grown to become a de-facto standard in AI technologies. TensorFlow received a lot of hype as part of its initial release, in no small part because it was released by Google. Despite the hype, there have been complaints on usability as well. Especially, for example, the fact that debugging was only possible after construction of the static execution graph. In addition to that, neural networks needed to be expressed as a set of linear algebra operations which was considered as too low level by many practitioners.
 
PyTorch and Keras addressed many of the flaws in TensorFlow and gained a lot of ground.
 
TensorFlow 2.0 successfully addressed those complaints and promises to become the go-to framework for many AI problems.
 
In this talk we’ll introduce you to the most prominent changes in TensorFlow 2.0 and how you can use these new features successfully in your projects. We’ll cover eager execution, parallelisation strategies, the advantages of the tight high level Keras integration, live neural network training monitoring using TensorBoard, automated hyper parameter optimization, Model serving with TensorFlow Serving, TensorFlow.js and TensorFlow Lite. We’ll finalise with an outlook on TFX - where Google is planning to open source it’s complete AI pipeline and will contrast it with existing de-facto standard frameworks like Apache Spark.
 
At the end we show how to run TFX Pipelines on Kubernetes using Kubeflow.
 
What's the takeaway for the audience?
* Learn how TensorFlow Graphs work
* Understand how Eager Execution makes graphs obsolete
* Apply parallelisation strategies to run on clusters
* Use TensorBoard for live neural network debugging
* Execute hyper parameter optimisation
* Integrate TensorFlow Serving, TensorFlow.js and TensorFlow Lite into your projects
* Scale TFX Pipelines on Kubernetes with KubeFlow
 
Prerequisite knowledge for this presentation?
 
* Basic machine learning
* Basic python

# What’s new in Apache Spark 2.4
 
Apache Spark is the de-facto standard for massive parallel data processing at Enterprise and Cloud Scale - after an introduction in how Apache Spark works let’s have a look on what’s new in Version 2.4 and how the new features are impacting the Big Data and AI ecosystem from an architectural point of view.

# DeepLearning for Developers - Introduction to DeepLearning with Keras and TensorFlow
 
TensorFlow is an awesome library. But for the average developer fiddling with linear algebra is far to complicated. In this talk we'll give you a fast track recipe to master DeepLearning challenges using the Keras framework on top of TensorFlow. We'll start with basic image classification, show how you can implement a chat- bot and end with a Cryptocurrency price predictor. At the end of this talk you'll know how Convolutional Neural Networks, Long-Short-Term Memory Networks and Autoencoders work and how you can apply them using Keras and TensorFlow.

# From Zero to Singularity - Designing the AI that humans need
 
We have tried many things. All of those work to a certain extent. Some make us stronger, some make us faster, some make us sick. The ability to think always has been a major challenge. Consciousness is the state or quality of awareness or of being aware of an external object or something within oneself. At least this is the definition on wikipedia. Brute-force state space exploration in chess? Attacking a knowledge base with grammar? Blue Gene and Watson did the job. Artificial neural tissue running In Silico is the latest craze - outperforming human baseline in various cognitive tasks. Let’s extrapolate the latest developments in that space and project. Even conservatively minded folks will notice that things can get out of control. Actually they are already. Or aren’t they? In this talk we’ll cover state of the art AI in robotics and decision making to find out where we are - between zero and singularity. And what steps need to be done to design an AI that humans need. In an open, decentralized, interconnected and unbiased way.

# The next leap towards Singularity? Generative Adversarial Networks - Introduction and Application
 
When training a deep neural network, concepts we know as humans are buried into weights between neurons. So when training an image classifier, concepts of dogs and cats are known by the neural network. But these concepts have been in-accessible. GANs are different. GANs can create new data using these hidden concepts. Let's talk about how they work and discuss their applications.

# The AI universe speaks Python - Lessons learned from a Coursera Instructor 

As a Sun Certified Java Programmer and Developer, and after working in 100s of JEE/WebSphere projects for IBM I never could imagine using anything else than Java. Even when planning for the first coursera course - "Fundamentals of Scalable DataScience" - we had tons of discussions whether we should use Scala, R or python for it. Now Python is an obvious choice for data science and we are using it for our "Advanced Machine Learning and Signal Processing" course as well as for the "Applied AI using DeepLearning" course. So in this talk I'll give you a summary on how to use Python and ApacheSpark on top of different machine learning and deep learning frameworks like SparkML, SystemML, Keras, DeepLearning4J to build scalable brains for AI. I'll finalise with a summary on Fabric for DeepLearning and the Docker/Kubernetes based Open IBM Model Asset Exchange.

# Scalable and Fault Tolerant Machine Learning and DeepLearning on Microservices
 
Summary - This talk explains how machine learning and deep learning can be made accessible to the broader ecosystem by providing consumable services in a micro services infrastructure.
 
This session explains one of the most important steps in creating a data product. Most DataScience projects nowadays start with a notebook. But in order to be consumable by others model scoring but also model training has to be consumable, even if you don’t have a Ph. D. in math. This talk shows how models implemented in the most common machine learning and deep learning frameworks can be provided as micro service in a scalable and fault tolerant way using container infrastructure on top of GPUs.
 
# Introduction to NodeRED, open source data flow/ETL on Node.js
 
NodeRED is one of IBM's recent contribution to OpenSource. We've seen examples of NodeRED processing 1.000.000 msg/s on 64 MB main memory footprint. Learn how you can use NodeRED on the Cloud (any cloud vendor is supported), on your machine, in your data center or even on an Raspberry Pi




 

