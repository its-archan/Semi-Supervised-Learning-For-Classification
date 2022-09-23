
# Semi-Supervised Learning for Classification

![Alt text](https://www.altexsoft.com/media/2022/03/supervised-vs-unsupervised-vs-semi-supervised-mach.png "a title")

## What is Semi-supervised learning?

Semi-supervised learning is an approach to machine learning that combines a small amount 
of labelled data with a large amount of unlabelled data during training. Semi-supervised 
learning falls between unsupervised learning (with no labelled training data) and supervised 
learning (with only labelled training data).

## Why is it required?

If we want to use Supervised ML we require labels of the data but labelling is:
- slow (it requires human experts to manually label training examples one by one) and
- costly (a model should be trained on the large volumes of hand-labelled data to provide accurate predictions).
If we want to use Unsupervised ML it has also drawbacks like:
- has a limited area of applications (mostly for clustering purposes) and provides less accurate results.
Semi-supervised learning(SSL) bridges supervised learning and unsupervised learning 
techniques to solve their key challenges. With it, you train an initial model on a few 
labelled samples and then iteratively apply it to the greater number of unlabelled data.
- Unlike unsupervised learning, SSL works for a variety of problems from classification and regression to clustering and association.
- Unlike supervised learning, the method uses small amounts of labelled data and also large amounts of unlabelled data, which reduces expenses on manual annotation and cuts data preparation time


### Assumptions of Semi-Supervised Learning:

In order to make any use of unlabeled data, some relationship to the underlying distribution 
of data must exist. Semi-supervised learning algorithms make use of at least one of the 
following assumptions:

**1.** **Continuity** **Assumption:** The algorithm assumes that the points which are closer to each other are more likely to have the same output label.

**2.** **Cluster** **Assumption:** The data can be divided into discrete clusters and points in the same cluster are more likely to share an output label.

**3.** **Manifold** **Assumption:** The data lie approximately on a manifold of much lower dimension than the input space. This is the less intuitive assumption, but it can be extremely useful to reduce the complexity of many problems. First of all, we can provide a non-rigorous definition of a manifold. An n-manifold is a topological space that is globally curved, but locally homeomorphic to an n-dimensional Euclidean space. In the following diagram, there's an example of a manifold: the surface of a sphere in ℜ^3
