# ‘I’m ready’  
***Data Mining research and development  
Analysis of Data and last statements of candidates for Capital punishment in Texas***  

the full project is in the 
'[project.ipynb](https://github.com/YPshir/datamining-project/blob/master/project.ipynb)' file.  

![2](https://user-images.githubusercontent.com/46241467/79245311-9e00fd00-7e80-11ea-9ff8-afd9e7670377.png)  
  
  ## Implementation  
  For this project in the "Data Mining" course - chosen a topic and database for which we will perform the process.
  ###  Data Mining  
  Data mining is the practice of automatically searching large stores of data to discover patterns and trends that go beyond simple       analysis. Data mining uses sophisticated mathematical algorithms to segment the data and evaluate the probability of future events.     Data mining is also known as Knowledge Discovery in Data (KDD).
  ##### The key properties of data mining are:
  * Automatic discovery of patterns  
  * Prediction of likely outcomes  
  * Creation of actionable information  
  * Focus on large data sets and databases  
  * Data mining can answer questions that cannot be addressed through simple query and reporting techniques.
  
  ### Main Tools  
 this project wrote in Python programming language in the Jupyter Notebook environment, which contains many directories for   realizing and executing data mining processes.   
  
  ### *[Pandas](https://pandas.pydata.org/)*      
  Pandas is an open-source Python package that provides high-performance, easy-to-use data structures and data analysis tools for the   labeled data in Python programming language. Pandas stand for Python Data Analysis Library.   
  Pandas is a perfect tool for data wrangling or munging. It is designed for quick and easy data manipulation, reading, aggregation, and visualization.
Pandas take data in a CSV or TSV file or a SQL database and create a Python object with rows and columns called a data frame. The data frame is very similar to a table in statistical software, say Excel or SPSS.  
###### used Pandas in:  
  1. Indexing, manipulating, renaming, sorting, merging data frame  
  2. Update, Add, Delete columns from a data frame  
  3. Impute missing files, handle missing data or NANs  
  4. Plot data with histogram or box plot  
  
  ### *[NumPy](https://numpy.org/)*      
One of the most fundamental packages in Python, NumPy is a general-purpose array-processing package. It provides high-performance multidimensional array objects and tools to work with the arrays. NumPy is an efficient container of generic multi-dimensional data.
NumPy’s main object is the homogeneous multidimensional array. It is a table of elements or numbers of the same datatype, indexed by a tuple of positive integers. In NumPy, dimensions are called axes and the number of axes is called rank. NumPy’s array class is called ndarray aka array.  
###### used NumPy in:  
  1. Basic array operations: add, multiply, slice, flatten, reshape, index arrays  
  2. Advanced array operations: stack arrays, split into sections, broadcast arrays  
  3. Work with DateTime or Linear Algebra  
  4. Basic Slicing and Advanced Indexing in NumPy Python  
  
  ### *[SciPy](https://www.scipy.org/)*      
The SciPy library is one of the core packages that make up the SciPy stack. SciPy builds on the NumPy array object and is part of the stack which includes tools like Matplotlib, Pandas, and SymPy with additional tools,
SciPy library contains modules for efficient mathematical routines as linear algebra, interpolation, optimization, integration, and statistics. The main functionality of the SciPy library is built upon NumPy and its arrays. SciPy makes significant use of NumPy.  
###### used SciPy in:  
 scipy.cluster.hierarchy for the hierarchy module provides functions for hierarchical and agglomerative clustering. Its features include generating hierarchical clusters from distance matrices, calculating statistics on clusters, cutting linkages to generate flat clusters, and visualizing clusters with dendrograms.  
 
   ### *[Matplotlib](https://matplotlib.org/)*      
Matplotlib is the plotting library for Python that provides an object-oriented API for embedding plots into applications. It is a close resemblance to MATLAB embedded in Python programming language.  
You can create stories with the data visualized with Matplotlib.
With a bit of effort and tint of visualization capabilities, with Matplotlib, you can create just any visualizations.  
###### used Matplotlib in:  
Histogram, bar charts, scatter plots, area plot to pie plot, Scatter plots, pie charts.  

  ### *[Seaborn](https://seaborn.pydata.org/)*      
data visualization library based on Matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics. seaborn is an extension of Matplotlib with advanced features.
Matplotlib is used for basic plotting; bars, pies, lines, scatter plots and stuff whereas, seaborn provides a variety of visualization patterns with less complex and fewer syntax.  
###### used Seaborn in:  
  1. Determine relationships between multiple variables (correlation)  
  2. Analyze uni-variate or bi-variate distributions and compare them between different data subsets  
  3. Plot linear regression models for dependent variables  
  4. Provide high-level abstractions, multi-plot grids  
  
  ### *[Scikit Learn](https://scikit-learn.org/stable/)*      
Scikit Learn is a robust machine learning library for Python. It features ML algorithms like SVMs, random forests, k-means clustering, spectral clustering, mean shift, cross-validation and more. NumPy, SciPy and related scientific operations are supported by Scikit Learn with Scikit Learn being a part of the SciPy Stack.
Scikit-learn provides a range of supervised and unsupervised learning algorithms via a consistent interface in Python. Supervised learning models like Naive Bayes to grouping unlabeled data such as KMeans, Scikit learn would be your go-to.  
###### used Scikit Learn in:  
  1. Classification: Spam detection, image recognition  
  2. Clustering: Drug response, Stock price  
  3. Regression: Customer segmentation, Grouping experiment outcomes  
  4. Dimensionality reduction: Visualization, Increased efficiency  
  5. Model selection: Improved accuracy via parameter tuning  
  6. Pre-processing: Preparing input data as a text for processing with machine learning algorithms.  
  
  
  ### *[Statsmodels](https://www.statsmodels.org/stable/index.html)*      
Statsmodels is the ultimate Python package that provides easy computations for descriptive statistics and estimation and inference for statistical models.  
###### used Statsmodels in:  
 A convenience interface for specifying models using formula strings and DataFrames. This API directly exposes the from_formula class method of models that support the formula API. Canonically imported using import statsmodels.formula.api as smf.  
 
 
   ### *[NLTK](https://www.nltk.org/)*    
   NLTK is a leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries, and an active discussion forum.  
###### used NLTK in:  
 1. most common words from the latest statements of the death row candidates and sort them by each race of those candidates.  
 2. show most frequent 100 words not related to the diffrents races (by using WordCloud package).  
 3. through Sentiment Intensity Analyzer we are going to sort out the letters of confessions by negative, positive and neutral emotions.
 4. predict the gender of candidates by their first name using the n-gram algorithm we learned in the class.  
 

 ## Conclusion
 * Gender - The gender of the victims is divided relatively evenly.  
 * Race - Most of the defendants are of a white race similar to the race distribution in the country.  
          A positive correlation was found between the race of the accused and the race of his victim, contrary to the prevailing hypothesis - "race war".
 * Education - The vast majority of the defendants had 12 years of schooling and even some went on to higher education.  
 * Criminal record - About half of the defendants do not have a criminal record and this is their first criminal offense.  
 * Text Mining - Most of the statements contained words related to family life and names of relatives (parents / children). Also, the word God has been mentioned frequently.         
                 80 percent of recent statements have a positive connotation despite the difficult situation they are in - their execution.
