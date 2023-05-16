# Natural Language Processing Project: Creating an Academic Paper Browsing Tool
### Jeffrey Bailey
### Data 340-03, Professor Tucker

#### Overview:
For this project, I want to make a model or set of models and tools that can be used to easily parse through dense academic papers and assist with finding interesting papers for the user to read. These are to be packaged into a prototype "app" that runs in python, that demonstrates how the models and created database could be used to develop this paper-browsing tool.

Specifically, I am making a transformer-based summarization model, doc2vec embeddings model, and topic selection model to make a database of scientific articles that includes short summaries, preprocessed versions of article text, vectorized document embeddings, and topic tags. This database will then be used by the set of functions and prototype app to create our paper-browser.

Code and a demo of the prototype app can be seen in the walkthrough notebook. Additional details can be found in the writeup.

#### About the Data
I am using a very large set of data taken from the huggingface "datasets" library. It contains nearly 200,000 full academic articles from the arXiv repository of math and physics papers. To create my pipeline and prototype app, I used a random subset of 2,500 articles so I could quickly test different models and code architectures.

## Initial Proposal
To keep as a reference, here is my initial project proposal from the February 2nd interest statement:

A potential project topic that is interesting to me is to analyze aspects of linguistics and writing styles within published scientific articles. This is relevant to me because until recently I was a fully focused chemistry major (I now focus on data science), and this semester I will finish writing a paper I have been working on with a W&M professor. However, I don't fully know what kind of questions or applications are applicable for the kind of language processing we will do in this class, I preliminarily plan to research trends between a paper's writing style and its influence in the field. Influence could be quantified using the writer's H-index, the paper's acclaim or earned accolades, or the paper's prevalence or reach into non-scientific media. The work from this project could be used by publishers or scientific authors to analyze their own work. More importantly to me I think it would be interesting to see if any particular writing styles or phrases are more prevalently used by succesful scientists so that I may incorporate those styles into my own work.
