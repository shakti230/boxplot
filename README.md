# boxplot
# Mary McDonagh
# Fundamentals for Data Analysis
# GMIT 2018


## Table of Contents
#### 1.0 Overview
#### 2.0 Prerequisites
#### 3.0 Github
#### 4.0 Summary
#### 5.0 References

## 1.0 Overview
This repository is intended to review the following in detail:
- • Summarise the history of the box plot and situations in which it used.
- • Demonstrate the use of the box plot using data of your choosing.
- • Explain any relevant terminology such as the terms quartile and percentile.
- • Compare the box plot to alternatives.


## 2.0 Prerequisites
Install Python 3.0
Install all required python dependencies

## 3.0 Github
Create repository and readme in github account.

## Download Data
In command line, cd (change directory) to this repo root directory
Execute setup script: sh ./setup/setup.sh. 
Clone github through command line.

## Jupter
Open the Jupyter notebook through Anaconda.
Create python 3 ipynb file and name it boxplot.

To begin my project I carried out an investigation of box plots. I have outlined my initial steps carried out below:
- Research the history of the box plot.
- Demonstrate the use of it with data.
- Import required libraries.
- Research and explanation of terminology.
- Comparison of the box plot to alternatives.
- Analyse all of the above information to summarise the dataset in detail.

After researching the history of boxplots I had a better understanding of their use. I defined the components of  boxplots and then I began displaying the various types of boxplots by simulating data to display them. I used np.random.rand to do this. I displayed 2 data simulations and I proceeded to display different types of boxplots such as:
- a basic boxplot
- a horizontal boxplot
- a notched boxplot
- changed outlier points
- not displaying outlier points
- changing the whisker length

To analyse this further in section 2.2 I used an some random data using the numpy package and also actual data using the Iris dataset to demonstrate the use of boxplots. I defined the variables in the Iris dataset and then used the descibe function to see a statistical analysis of it. I then began created boxplots using this data. I displayed the sepal and petal length and width. 

In Section 2.3 I continued my analysis by explaining the different terminology associated with boxplots. 

In Section 2.4 I carried out a comparison of boxplots to other alternatives.

Finally in Section 3 I summaried my work for this project defining boxplots and the tasks I covered throughout the project.


## 4.0 Summary
Boxplots capture a summary of data with a simple box and whiskers allowing us to compare easily across groups. I have learned throughout my research that a boxplot is simply a type of graph that displays a summary of a large amount of data in five numbers. These numbers include the median, upper quartile, lower quartile, minimum and maximum data values. Boxplots summarise a sample data using 25th, 50th and 75th percentiles. These percentiles are known as the lower quartile, median and upper quartile. The advantage of comparing quartiles is that they are not influenced by outliers. The median is the midpoint of the range of data; the upper and lower quartiles represent the numbers above and below the highest and lower quarters of the data and the minimum and maximum data values. Organizing data in a box plot by using five key concepts is an efficient way of dealing with large data too unmanageable for other graphs, such as line plots or stem and leaf plots.

####Advantages of boxplots
- they handle large amounts of data easily
- allow you to efficiently display large amounts of data using the 5 concepts mentioned above

#### Disadvantages of boxplots
- boxplots do not keep the exact values and details of the distribution results
- displays a simple summary of the data
- generally boxplots would need to be used in conjunction with other graphs
Reference 15.

## 5.0 References
- Reference 1: https://flowingdata.com/2011/12/06/40-years-of-boxplots/
- Reference 2: https://stats.stackexchange.com/questions/369393/whats-the-history-of-box-plots-and-how-did-the-box-and-whiskers-design-evolv
- Reference 3: https://louisville.edu/sphis/bb/src-2013/student-poster-competition/Abstract_WalkerM.pdf
- Reference 4: http://vita.had.co.nz/papers/boxplots.pdf
- Reference 5: http://www.math.wpi.edu/saspdf/stat/chap18.pdf
- Reference 6: https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.boxplot.html
- Reference 7: https://python-graph-gallery.com/30-basic-boxplot-with-seaborn/
- Reference 8: https://github.com/shakti230/Project2018
- Reference 9: https://www.kaggle.com/arturocarreno/box-plot-python-matplotlib
- Reference 10: https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/box-whisker-plots/a/box-plot-review
- Reference 11: http://www.flinders.edu.au/slc_files/Documents/Red%20Guides/Box%20and%20Whisker%20Plots.pdf
- Refernce 12: https://python-graph-gallery.com/24-histogram-with-a-boxplot-on-top-seaborn/
- Reference 13: https://data-flair.training/blogs/python-scatter-plot/
- Reference 14: https://blog.magrathealabs.com/choosing-one-of-many-python-visualization-tools-7eb36fa5855f
- Reference 15: https://sciencing.com/advantages-disadvantages-box-plot-12025269.html
- Reference 16: https://python-graph-gallery.com/35-control-order-of-boxplot/
- Reference 17: https://python-graph-gallery.com/38-show-number-of-observation-on-boxplot/
- Reference 18: file:///C:/Users/sam2/Downloads/BoxPercentilePlot.pdf
- Reference 19: https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/NCSS/Box_Plots.pdf
- Reference 20: https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/NCSS/Box_Plots.pdf
- Reference 21: https://blog.bioturing.com/2018/05/22/how-to-compare-box-plots-/
- Reference 22: https://matplotlib.org/gallery/statistics/boxplot_demo.htmlimport matplotlib.pyplot as plt
- Reference 23: https://matplotlib.org/gallery/statistics/boxplot_vs_violin.html
