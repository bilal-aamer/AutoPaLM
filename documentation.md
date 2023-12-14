# Documentation

Following is the high level overview of code in main.py:

## 1.Imports:
- The script imports necessary modules such as os, json, re, and subprocess.
- It also attempts to import a module called google.generativeai as palm.
  
## 2.Configuration:
- An API key is configured for the palm generative AI model.
  
## 3.Classes:
- SystemMemory: Manages the memory of the system, including loading or creating memories, appending information to the memory, marking tasks as completed, and summarizing conversations.
- TaskGenerator: Generates tasks and subtasks using the palm generative AI model.
- CodeExecution: Tests and processes code snippets, including extracting code snippets from generated content.
  
## 4.Main Function:
- Initializes an initial prompt for the conversation.
- Creates instances of TaskGenerator and SystemMemory.
- Selects a memory or creates a new one.
- Loads or creates the selected memory and updates it with the initial prompt.
- Generates a list of tasks using the TaskGenerator and appends them to the memory.
- Generates subtasks for each task, appends them to the memory, and processes them using the CodeExecution class.
- Updates the memory with the task summary and generates a next step based on the progress.
- Prints the next step, summary of completed tasks and subtasks, and the summary of the entire conversation.
  
## 5.Execution:
- The main function is executed if the script is run as the main program.