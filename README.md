<h4>Just a simple project for helping with pandas datasets</h4>
<h4>Installation</h4>
<blockquote>pip install</blockquote>
<p><h4>Usage:</h4>
Checking Null Values<br>
<blockquote>Helper.null_count(dataframe)</blockquote>
Removing outliers via interquartile ranges<br>
<blockquote>Helper.rm_outlier(dataframe_column)</blockquote>
Randomizing index<br>
<blockquote>Helper.randomize(dataframe,seed)<br>
seed for reproducibility</blockquote>
Test, train split of dataframe
<blockquote>Helper.test_train_split(dataframe,frac=0.2)<br>
frac value range: 0 - 1</blockquote>