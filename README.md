# NLP_AutoComplete_Markovchain

Text auto completion implemented using Markov Chain. 

The algorithm take's a corpus as an input to create n-gram dictionary, which stores the frequency of the nth token for the n-1 tokens. 

For a given statement, the output can be generated in either of the two ways:

* Deterministic : Where the next n^{th} word is the most frequently (most probabilistic) word given the n-1 tokens in the sentence.
* Non-Deterministic : Where the next n^{th} word is selected randomly from the distribution of words following n-1 tokens.
