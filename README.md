
# Introduction

The goal of text summarizing is to see if we can come up with a method that employs natural language processing to do so. This method will not only save time in comprehending a text, but it will also allow someone to read multiple texts in a short period of time, saving time in the long term.

# Types of Text Summarization

There are two types of Text Summarization, one is Extractive Type and another one is Abstractive Type. Extractive summarization takes the original text and extracts information that is identical to it. In other words, rather than providing a unique summary based on the full content, it will rate each sentence in the document against all others, based on how well each line explains.

# Text Summarization using Cosine Similarity

The cosine similarity falls under the extractive text summarization method. A measure of similarity between two non-zero vectors is cosine similarity. It can be used to identify similarities between sentences because we’ll be representing our sentences as a collection of vectors. It calculates the angle between two vectors’ cosine. If the sentences are comparable, the angle will be zero.

# Impact

Summarization systems often have additional evidence they can utilize in order to specify the most important topics of document(s). For example, when summarizing blogs, there are discussions or comments coming after the blog post that are good sources of information to determine which parts of the blog are critical and interesting.

In scientific paper summarization, there is a considerable amount of information such as cited papers and conference information which can be leveraged to identify important sentences in the original paper.

## HOW TO USE

Install requirements using:

```
pip install -r requirements.txt
```

Place the text file in the same directory as text-summarizer.py.

Run the script using 

```
python text-summarizer.py
```

When prompted, type the name of the text file you wish to summarize.
