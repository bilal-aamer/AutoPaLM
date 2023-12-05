_Please note that I'm solo on this project at the moment and will always welcome help. I'm still learning programming language and jargon. Thank you for your understanding and patience! Kindly give credit openly if using this repository_
# AutoPaLM

AutoPaLM is a Python-based AI program created with the help of PaLM and other LLMs. This was started from scratch. The program stores and manages the generated content in a memory system, allowing for context-aware responses and the ability to filter, archive, and retrieve information based on user input.


## Features

- Generate questions and answers based on user-defined prompts
- Store and manage generated content in a memory system
- Filter and archive memory based on user-defined thresholds
- Save and load memory settings for easy retrieval and customization
- Detect and save code snippets from generated content

## Usage

1. Install the required dependencies:
```
pip install -r requirements.txt
```

2. Run the `main.py` script to start the Auto-PaLM program:
```
python main.py
```

3. Follow the on-screen prompts to set goals, enter prompts, and generate questions and answers.

## Functions

- `set_clear_goals()`: Allows users to define goals for the AI system.
- `generate_text(prompt)`: Generates text based on the given prompt.
- `process_answer(question, answer, memory)`: Processes the answer, detects code snippets and updates the memory.
- `filter_memory(memory, prompt_embedding, threshold)`: Filters the memory based on the relevancy of the given prompt.

## User Input

Users can interact with the program by entering the following commands:

- Enter a prompt: Users can input a prompt for the AI to generate questions and answers based on the prompt.
- `exit`: Exits the program.
- `Clear memory`: Clears the memory of the program.
- Enter the number of iterations: Users can input the number of iterations for generating questions and answers. The default is 1.

## Memory Settings

- `num_prompts`: The number of prompts to remember.
- `filter_context_threshold`: The threshold for filtering context based on relevancy (between 0 and 1).
- `archive_memory_threshold`: The threshold for archiving memory (between 0 and 1).
- `filter_memory_threshold`: The threshold for filtering memory based on relevancy (between 0 and 1).

## Contributing

I welcome contributions to improve the Auto-PaLM program. Please feel free to submit suggestions and issues to discuss potential improvements or report bugs, and even help me understand terms and the correct process of open-source projects.

I'm so excited to see how both AutoPaLM will continue to push the boundaries of what is possible with AI in the future!


**For any issues raise an issue in the issues tab**

<packages to be installed are yet to be finalized>
