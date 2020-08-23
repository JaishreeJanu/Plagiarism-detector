## Plagiarism Detector

I have performed binary classification, that labels whether a file is plagarized or not. 

- **Containment** and **Longest Common Subsesquence** have been used as similarity features to find out how similar two files are.

- Containment calculates common n-grams between two files. It is calculated as follows:

∑𝑐𝑜𝑢𝑛𝑡(ngram𝐴)∩𝑐𝑜𝑢𝑛𝑡(ngram𝑆)/∑𝑐𝑜𝑢𝑛𝑡(ngram𝐴)

- Longest common subsequence can be calculated using Dynamic Programming.

- Correlated features are removed and neural network is trained which gives 96% accuracy. 

You can find notebook, python code and unittests in this repository.
