# NLI_RTE_Project
Natural Language Inference (NLI), or Recognizing Textual Entailment (RTE) Project.

## About the project:
I wanted to see how different newspapers review the same event.

Are there any differences in the titles of the articles?

In this project I wanted to check that.

This task is part of language inference field, which is called Recognizing Textual Entailment (RTE).

So my project goal: determining how pairs of English sentences are related (entailment connection / contradict / neutral)

**Example:**

Sentence 1: "The kids are sad"

Sentence 2: "Children smiling and waiving at the camera"

Conclusion: Those sentence are contradict ('sad' is the opposite of 'smiling')

**How I tried to do that?**

I used pre-trained Bert model (DistilBert) to get sentences' embeddings; then I trained Machine Learning models to do the classification task (Logistic Regression, Support Vector Classification and Ensembles)

**Dataset source:**
https://nlp.stanford.edu/projects/snli/

**Download the dataset:**
https://nlp.stanford.edu/projects/snli/snli_1.0.zip
