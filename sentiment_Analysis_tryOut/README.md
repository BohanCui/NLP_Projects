# This is where I try to analyze the sentiment of feedback.

   
## Project Outline

The project is made up of five steps, which are built on each other:

   * Creating sub-dataset.
   * Create and evaluate a dictionary-based sentiment analyzer.
   * Creating neural network-based sentiment analyzers.
   * Reporting your results with visuals.

## Techniques

In order to get a deeper understanding of people’s opinions about video game/fashion,I :
   * Calculate the sentiment value of the reviews with the dictionary-based sentiment analysis tools using  NLTK. Data evaluation with scikit-learn in Python.
   * Analyzing the reviews with deep learning DistilBERT model. (Pytorch & transformers packages used)
   * Evaluating your model and creating descriptive statistics
   * Visualizing findings about preferable and non-preferable words related to video games using Altair.

## Dataset

The Amazon review dataset can be downloaded from [here](https://nijianmo.github.io/amazon/index.html). Download the zipped json file of the category of video games 5 core(too large to upload here), which can be found under the title Small subsets for experimentation. Once the download is complete, simply extract the file.
