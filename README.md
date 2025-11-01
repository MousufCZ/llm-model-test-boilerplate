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

List of installed Ollama models (once ollama serve is running)
* ollama list

Stop Ollama
* brew services stop Ollama
* Control + C

Check if Ollama is running
* brew services list

Restart Ollama
* brew services restart ollama

Kill process manually
* pkill ollama

### Ollama available commands

Available Commands:
  serve       Start ollama
  create      Create a model from a Modelfile
  show        Show information for a model
  run         Run a model
  pull        Pull a model from a registry
  push        Push a model to a registry
  list        List models
  cp          Copy a model
  rm          Remove a model
  help        Help about any command

Flags:
  -h, --help      help for ollama
  -v, --version   Show version information

Use "ollama [command] --help" for more information about a command.

## Langchain API reference
https://python.langchain.com/api_reference/langchain/

## Other
If you are installing new libraries, please use the following command line: 
Update requirements.txt: pip freeze > all_reqs.txt

This will update the requirements.txt file with the name of libraries installed.

## Contribute to this project?
Please do!
As I use LLMs more, I will be updating this repository. There are certain features I want to build.
* LLM testing on local hardware features. These are speed of token generation.
* Cloud GPU implementation.
* Multiple hardware testing and report generation (CSV file type). Data is fun. Understanding the speed of various LLMs on you local or cloud hardware will be beneficial for project implementation.
* Once I have these features implemented, won't it be amazing to have a TUI? Look at Textualize if you want to give it a go. https://www.textualize.io

How do you contribute? Check out the following link: https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project
