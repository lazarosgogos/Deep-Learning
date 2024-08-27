# Deep Learning code repository

### What does this repo contain?
This repository contains various implementations of Deep Learning techniques, such as SVMs, Auto Encoders, simple CIFAR-10 classifiers but also
Deep Reinforcement Learning implementations

### SVM Example
For example, a Keras implementation of an SVM put right before a pre-trained AutoEncoder results 
in the following details:

A grid search for the best (C,γ) values tells us that the best combination is somewhere near (C,γ)=(2^1, 2^-3)
![SVM wide grid search](https://github.com/lazarosgogos/Deep-Learning/assets/75678168/bb9239d8-1dac-47aa-b477-b951ff3fb638)

Thus, a finer grid search results in (C,γ)=(2^0.5, 2^-2.75). 
![SVM narrow grid search](https://github.com/lazarosgogos/Deep-Learning/assets/75678168/f700eeb6-c88a-4ece-84a8-11b1ff4a60d7)

### Deep Reinforcement Learning 
After training a Deep Q Network to play Blackjack on the Gymnasium environment, its testing is illustrated below. 
At best, playing Blackjack yields the following chances: 42% win, 8% draw, 50% lose.
Hence, the closer the blue line is at 0, the better the results. 
![Deep Q Network - testing](https://github.com/user-attachments/assets/b797ae98-66f7-4b97-9c7e-f2154a315c42)
