# Ollama and Langchain LLM model testing
## What is boilerplate code?
This is a boilerplate code for testing new LLMs downloaded using Ollama and Langchain. 

## What is the purpose?
This is created for the soul purpose of testing the LLM modeles before implemented in a working project.

## What is it testing?
./setupTest
 * Correct installation of the LLM using Ollama.
 * Token generation is working.
  * Create a chain of response.
  * model and langchain memory buffer test.

./chatBotTest
  * Testing the model's ability to chat with a user.
  * Load previous conversations from saved text file to have historical conversation context.

 ## Ensure to install correct libraries (Mac & Project folder)
  * brew install ollama
  * pip3 install langchain langchain-community langchain-ollama
 * ...# llm-model-test-boilerplate

## Ollama 
Run Ollama 
* ollama serve

Stop Ollama
* brew services stop Ollama
* Control + C

Check if Ollama is running
* brew services list

Restart Ollama
* brew services restart ollama

Kill process manually
* pkill ollama

## Langchain API reference
https://python.langchain.com/api_reference/langchain/

## Other
If you are installing new libraries, please use the following command line: 
Update requirements.txt: pip freeze > all_reqs.txt

This will update the requirements.txt file with the name of libraries installed.