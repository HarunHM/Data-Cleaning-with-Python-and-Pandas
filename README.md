# Data Cleaning.






Data cleaning is the process of preparing data for analysis by removing or modifying data
that is incorrect, incomplete, irrelevant, duplicated, or improperly formatted.



Data cleaning is one those things that everyone does but no one really talks about. 
Sure, it’s not the "sexiest" part of machine
learning. And no, there aren’t hidden tricks and secrets to uncover.

 Added a data cleaning using python/ pandas library (2rd october 2019) using property data.csv  data set.
 
 
 
 The data set  is small compared to real data machine learning models data set. i kept it simple to ease coding.



<h1> useful functions</h1>

<b>Removing NA from the data set: </b> <br>

<code>
 df=df.dropna(axis=0, how='any')
 </code>

<b> dropna function here yields a dataframe as its output, and you can save it either as a DataFrame. </b>
