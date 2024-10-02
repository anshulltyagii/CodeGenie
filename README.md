# Autonomous Agent for Test-Driven Development (TDD)

"Programmers have programmed themselves out of jobs" - Unknown

https://github.com/anshulltyagii/CodeGenie/blob/7aed224e961ae3dc98fd3da8fb7edec0c8b9b681/CodeGenie.mp4

CodeGenie is an autonomous coding agent that builds applications in ReactJS, Flask, Express, and more, all while adhering to the Test-Driven Development (TDD) methodology. It operates entirely without human intervention. Beginning with a project plan, CodeGenie translates requirements into tests, develops code based on those tests, and debugs until all tests pass. The TDD framework keeps the agent focused and goal-oriented.

**Key Highlights:**

- **Autonomous Development:** CodeGenie operates without any human intervention, from planning to debugging.
- **Versatile Technology Stack:** Capable of building applications in ReactJS, Flask, Express, and more.
- **Test-Driven Development:** Adheres strictly to TDD methodology, ensuring robust and reliable code.
- **Simple Yet Powerful Architecture:** Utilizes just three tools: CLI, ReadFile, and WriteFile.
- **Adapted from Langchain's AutoGPT:** Enhanced significantly by ChatGPT Plus over a month-long chat.
- **Temporal Understanding:** Gained insights into temporal concepts like past, present, and future, as well as cause and effect.
- **Advanced Capabilities:** Utilizes GPT-4 Turbo and GPT-4 Vision to transform wireframes or screenshots into fully functional applications.
- **Expanded Context Window:** Functions as an integrated team comprising a Product Owner, Programmer, and Tester.
- **Continuous Learning:** Evaluates its mistakes and areas for improvement, incorporating insights into its operating prompts.

This project is in the early alpha stage. A GPT-4 API key is required.

## Setup Instructions

1. Setup a virtual environment:
```
python3 -m venv env
```

2. Activate the virtual environment:
- On macOS and Linux:
  ```
  source env/bin/activate
  ```
- On Windows:
  ```
  .\env\Scripts\activate
  ```
3. Clone the repository to your local machine:
```
git clone https://github.com/anshulltyagii/CodeGenie.git

```
4. Navigate to the project directory:
```
cd tddGPT
```

5. Run the following command to install the package and its dependencies:
```
python setup.py install
```

6. Set up your GPT-4 API keys as environment variables.
```
export OPENAI_API_KEY="at-..."
```

7. Run the main.py
```
cd tdd-gpt
python main.py --model gpt-4-1106-preview or gpt-3.5-turbo --prompt "Your prompt here" --temperature 0.2 --context_window 128000
```

Check the counter-app directory for the generated app.

## Example apps

The following are some apps have been built by this agent.

- [Todo App](https://todo-app-tv1.netlify.app/) - built with GPT4 Turbo + GPT4-V
- [Task Tracker](https://brilliant-biscotti-3f9e48.netlify.app/) - built with GPT4
- [Counter App](https://counter-app-tddgpt.netlify.app/) - built with fine-tuned GPT3.5

## Contributing

We welcome contributions to this project. Please feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Contact

If you have any questions or comments, please feel free to reach out on GitHub.
