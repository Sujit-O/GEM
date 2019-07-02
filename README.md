[![Documentation Status](https://readthedocs.org/projects/gemben/badge/?version=latest)](https://gemben.readthedocs.io/en/latest/?badge=latest)

# GEM-benchmark 

## Documentation
Please find the documentation [here!](https://gem.readthedocs.io)

## Introduction
Graph embedding, which refers to the task of representing nodes of a graph in a low-dimensional space, has gained significant traction in the past few years, with applications including link prediction, node classification, and graph visualization. Many methods have been proposed for this task which primarily differs in the inherent properties being preserved from the original graph. However, comparing such methods is challenging. Most methods show performance boosts on just a few selected networks. Such performance improvement may be due to fluctuations or specific properties of the networks at hand, thus being often inconclusive when comparing methods on different networks. To conclusively determine the utility and advantages of an approach, one would need to make a comparison on several such networks. In this work, we introduce a principled framework to compare graph embedding methods. We test embedding methods on a corpus of real-world networks with varying properties and provide insights into existing state-of-the-art embedding approaches. We cluster the input networks in terms of their properties to get a better understanding of embedding performance. Furthermore, we compare embedding methods with traditional link prediction techniques to evaluate the utility of embedding approaches. We use the comparisons on benchmark graphs to define a score, called GFS-score, that can apply to measure any embedding method. We rank the state-of-the-art embedding approaches using the GFS-score and show that it can be used to understand and evaluate a novel embedding approach. We envision that the proposed framework may serve as a community benchmark to test and compare the performance of future graph embedding techniques.
