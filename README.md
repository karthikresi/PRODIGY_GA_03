# PRODIGY_GA_03
Prodigy Infotech Internship – Generative AI
Task 3: Text Generation using Markov Chains

This repository contains my submission for Task 3 of the Generative AI Internship at Prodigy Infotech. The goal of this task was to implement a basic text generation model using Markov chains.

Task Objective:
To create a simple statistical model that generates text by predicting the next word or character based on the previous one(s). The model uses Markov chain logic to determine the most likely next token using a transition probability matrix.

Tools and Technologies Used:

Python

Google Colab / Local IDE

Custom Markov chain implementation (no external ML libraries)


What I Did:

Used a text file (input.txt) as the training dataset.

Processed the text and built a word-level and character-level Markov chain.

Created a generator to produce new sentences based on the trained model.

Displayed and saved the generated text output to a result.txt file.

Configured the order of the chain to change the context depth.


Files in This Repository:

Task3.py – Python script for training and generating text

input.txt – Sample input data for training the Markov model

result.txt – Output file containing generated text and probabilities


Example Output:
Trained on: input.txt
Sample prompt: The sun rises
Generated output: The sun rises slowly above the dark hills as birds begin their song...

Intern Details:
Internship: Generative AI – Prodigy Infotech
Task Status: Task 3 Completed
Name: G.KARTHIK

Note:
This project was completed using only fundamental programming techniques to simulate how a Markov chain can be applied to language modeling. No deep learning frameworks were used.
