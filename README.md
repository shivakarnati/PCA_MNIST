# PCA_MNIST
Worked on Principle component analysis on MNIST dataset
Principal component analysis (PCA) is a technique that transforms high-dimensions data into lower-dimensions 
while retaining as much information as possible.

PCA is extremely useful when working with data sets that have a lot of features. Common applications such as image processing, 
genome research always have to deal with thousands-, if not tens of thousands of columns. While having more data is always great,
sometimes they have so much information in them, we would have impossibly long model training time and the curse of dimensionality starts to become a problem.
Sometimes, less is more.
It is a mathematical technique used to analyze and reduce the dimensions of a dataset. It aims to find the most important features or patterns in the data and represent them in a more concise and meaningful way.
Instead of understanding the data in the same way humans comprehend a storybook through language, PCA uses mathematical calculations to extract meaning from the data. It seeks to answer two fundamental questions:

Which parts of the data are most significant or informative?
Can we measure and quantify the amount of information contained in the data?
By addressing these questions, PCA helps us gain insights into the underlying structure and relationships within the dataset, 
enabling us to simplify and summarize the data while preserving the most important aspects.

**Variance** plays a crucial role in determining the amount of information contained in a dataset. It is a concept that many people are familiar with from their high school studies. Variance measures the average extent to which each data point deviates from the mean.
In the context of PCA, variance serves as an indicator of information. Higher variance implies a greater amount of meaningful information present in the data, while lower variance suggests less informative data. 
By examining the variances of different features or variables, PCA can identify the most significant patterns or directions along which the data varies the most. These patterns,
known as principal components, capture the essential information and allow for dimensionality reduction while retaining the most informative aspects of the data.

![image](https://github.com/shivakarnati/PCA_MNIST/assets/38187230/67d154e7-7569-4efd-8409-6d15958438e1)

