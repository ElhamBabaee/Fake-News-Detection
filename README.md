# Fake-News-Detection

In this NotebookI will talk about how one can create an NLP to detect whether the news is real or fake. Nowadays, fake news has become a common trend. Even trusted media houses are known to spread fake news and are losing their credibility. So, how can we trust any news to be real or fake?

## Dataset
<ul><li>train.csv: A full training dataset with the following attributes:</li>
<li>id: unique id for a news article</li>
<li>title: the title of a news article</li>
<li>author: author of the news article</li>
<li>text: the text of the article; could be incomplete</li>
<li>label: a label that marks the article as potentially unreliable. Where 1: unreliable and 0: reliable.</li></ul>

## Tabel of Contents

<ul>
<li>
<p>Define Problem</p>
<ul>
<li>Can we predict the reliable news from the Fake news?</li>
<li>Goals</li>
</ul>
</li>
<li>
<p>Discover Data</p>
<ul>
<li>Exploratory Data Analysis(EDA)</li>
<li>Data Visualization</li>
</ul>
</li>
<li>
<p>Develop solutions</p>
<ul>
<li>Establish model</li>
  <li>Multinomial Classifier with Hyperparameter</li>
  <li>Build GRU Neural Network</li>
<li>Hyperparameter Tuning &amp; Optimization</li>
<li>Best model</li>
</ul>
</li>
<li>
<p>Deploy solution</p>
</li>
</ul>
