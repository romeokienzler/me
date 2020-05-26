# Privacy-preserving machine learning
Data privacy is a huge concern and often prevents ML and AI project from flourishing.

In this talk we’ll introduce you to federated learning and homomorphic encryption. After we’ve covered the theoretical aspects we’ll see
how they can be used in practice. 

We conclude with an outlook on the future of these technologies.

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
