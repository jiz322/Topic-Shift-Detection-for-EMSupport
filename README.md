# Topic-Shift-Detection-for-EMSupport

This work is to facilitate the [EMSupport repository](https://github.com/thu-coai/Emotional-Support-Conversation)

# Motivation
The generative model take entire dialog history as an input, which is not dirable because once the topic has shifted, keeping the previous dialog histories will only give negative effect. Therefore, we need to automate the conversation history clearance using deep models.\

# Task for this repo
Input an utterance, the model should output a topic label. We used the "situations" column in ESConv as labels and performed supervised learning.

# Evaluation
We chose the BERT-balanced-7classes version to facilitate EMSupport Chatbot. The performance of Chatbot has been improved based on the survey we sent to human evaluators.

# Detail
Detail are documented in the report.


