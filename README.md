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

If you're interested in contributing to this project, please take a moment to review the following guidelines.

### How to Contribute

1. **Fork the repository:** Click on the "Fork" button at the top right of this repository to create your own copy.

2. **Clone your fork:** Clone your forked repository to your local machine using:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

3. **Create a new branch:** Create a new branch to work on your feature or bug fix using:

    ```bash
    git checkout -b feature/your-feature-name
    ```

    or

    ```bash
    git checkout -b bugfix/your-bug-fix
    ```

4. **Make changes:** Make your changes to the code, documentation, or any other relevant files.

5. **Commit your changes:** Commit your changes with a descriptive commit message:

    ```bash
    git commit -m "Add your descriptive commit message here"
    ```

6. **Push to your branch:** Push your changes to your forked repository:

    ```bash
    git push origin feature/your-feature-name
    ```

7. **Submit a Pull Request:** Open a Pull Request (PR) from your forked repository to the original repository's branch.

### Guidelines

- Ensure your code follows the project's coding standards.
- Provide clear and concise commit messages.
- Keep the documentation up-to-date if relevant.
- Test your changes thoroughly before submitting a PR.
- Ensure your PR does not introduce breaking changes.

### Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project, you agree to abide by its terms.

Thank you for contributing to our project! 🚀

**For any issues raise an issue in the issues tab**

<packages to be installed are yet to be finalized>
