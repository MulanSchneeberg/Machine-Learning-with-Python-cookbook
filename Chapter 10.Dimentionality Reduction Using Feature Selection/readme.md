In Chapter 9, we discussed how to reduce the dimensionality of our feature
matrix by creating new features with (ideally) similar ability to train quality
models but with significantly fewer dimensions. This is called feature extraction.
In this chapter we will cover an alternative approach: selecting high-quality,
informative features and dropping less useful features. This is called feature
selection.
There are three types of feature selection methods: filter, wrapper, and
embedded. Filter methods select the best features by examining their statistical
properties. Wrapper methods use trial and error to find the subset of features that
produce models with the highest quality predictions. Finally, embedded methods
select the best feature subset as part or as an extension of a learning algorithm’s
training process.
Ideally, we’d describe all three methods in this chapter. However, since
embedded methods are closely intertwined with specific learning algorithms,
they are difficult to explain prior to a deeper dive into the algorithms themselves.
Therefore, in this chapter we cover only filter and wrapper feature selection
methods, leaving the discussion of particular embedded methods until the
chapters where those learning algorithms are discussed in depth.
