# Parts of speech tagger
## Problem statement 

when the Viterbi algorithm encountered an unknown word (i.e. not present in the training set), it assigned an incorrect tag arbitrarily. This is because, for unknown words, the emission probabilities for all candidate tags are 0, so the algorithm arbitrarily chooses (the first) tag. 

In this project, I have modify the Viterbi algorithm to solve the problem of unknown words. Though there could be multiple ways to solve this problem, I have used following two techniques:
1. Rule based function with Viterbi POS tagger
2. Modified Viterbi algorithm
