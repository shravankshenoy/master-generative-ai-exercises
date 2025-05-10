
## Exercise 1 
Connect to an LLM api, and ask the following question : "Describe Shimla in 1 sentence" 
\
\
The following sites provide free apis:
  - GroqCloud
  - Google (Gemini)
   
The following sites require payment:
  - OpenAI
  - Anthropic
   
The free apis should are good enough for these exercises. Make an account and get an API KEY so as to use these apis

## Exercise 2 
Create a program that does multiturn llm call i.e. you can send an input to the LLM as many times as you want until you press quit. Once done ask the following questions:
  - Describe Shimla in 1 sentence
  - Describe Manali in 1 sentence
  - Which of the two should I visit?

What is the response you get to the third question?

_Hint : Put the code from Exercise 1 in a while loop_

## Exercise 3
Write a program for multi turn LLM conversation with memory i.e. LLM should be able to answer questions based on conversation history. The way to do this is to store the previously asked questions and answers and pass that to the LLM along with the latest question

_Hint : https://community.openai.com/t/multi-turn-conversation-best-practice/282349/5_

One you finish the exercise look at the [following Langchain code](https://github.com/langchain-ai/langchain/blob/master/libs/langchain/langchain/memory/chat_memory.py). Does it look similar to your code?
