This project was origially an asignment of ELL884 course (Deep Learning for NLP).It contains the implementation of Hidden Markov Model (HMM) and the Maximum Entropy markov Model (MEMM) to solve the problem of POS tagging. Here we try to solve the issue of asigning the most probable tag sequence given observatons ( here the words of a sentence). 

HMM uses the Viterbi algorithm which is inherently a Dynamic Programming based algorithm and takes help of the backpointer aporoach to keep track of the assigned tag sequence. MEMM is algorithmically the same but you would see the diffenrence in the modelling assumptions. The dependence of the current tag is not only on the previous tag but also the current word, whereas in HMM current tag only depends on the previous tag assigned. The dependence between the current observation (word) and the current tag) is a seperate entity in HMM.

You can see more details of the project in the report where I have explained everything in detail.

PS: Please refer to the Submission 2 in HMM.ipynb file. NOT submission1.
