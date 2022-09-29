# Topic-Shift-Detection-for-EMSupport

This work is to facilitate the [EMSupport repository](https://github.com/thu-coai/Emotional-Support-Conversation)

## Motivation
The generative model take entire dialog history as an input, which is not dirable because once the topic has shifted, previous dialog histories will have negative effect on sentence generation. To improve the chatbot, we automate the conversation history clearance using deep models.

## Task for this repo
Input an utterance, the model outputs a prediction of its topic label. We used the "situation" column in ESConv as labels and performed supervised learning.

## Evaluation
We chose the BERT-balanced-7classes version to facilitate EMSupport Chatbot. The performance of Chatbot has been improved based on the survey we sent to human evaluators. As the figure below, when topic shift happens, 183 times (out of 300) the evaluators chose the responses generated from the modified chatbot to be better than those generated from the original version. Only 19 times the evaluators think the origianal version gives better responses.

![alt text](https://github.com/jiz322/Topic-Shift-Detection-for-EMSupport/blob/main/evaluation_result.png)

## Detail
Detail are documented in the [report](https://github.com/jiz322/Topic-Shift-Detection-for-EMSupport/blob/main/Improve%20the%20Empathetic%20Chatbot-08-24-v3.pdf).


