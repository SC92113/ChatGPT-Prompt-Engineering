# ChatGPT-Prompt-Engineering

### 🛠️ This project is supported by [DeepLearning.AI](https://www.deeplearning.ai/) and [OpenAI](https://openai.com/).

### 🎯 Goal
- **Optimize the use and capabilities of prompting**
- **Quick access to notebooks**
  
  - Summarizing: [Summarizing_Prompt.ipynb](https://github.com/SC92113/ChatGPT-Prompt-Engineering/blob/ee7bf1ac5a5f4828f7829ae20abc913d29b98476/Summarizing_Prompt.ipynb)
  - Inferring including extracting: [Inferring_Prompt.ipynb](https://github.com/SC92113/ChatGPT-Prompt-Engineering/blob/ee7bf1ac5a5f4828f7829ae20abc913d29b98476/Inferring_Prompt.ipynb)
  - Transforming: [Transforming_Prompt.ipynb](https://github.com/SC92113/ChatGPT-Prompt-Engineering/blob/ee7bf1ac5a5f4828f7829ae20abc913d29b98476/Transforming_Prompt.ipynb)
  - Expanding: [Expanding_Prompt.ipynb](https://github.com/SC92113/ChatGPT-Prompt-Engineering/blob/ee7bf1ac5a5f4828f7829ae20abc913d29b98476/Expanding_Prompt.ipynb)
  - Chatbot: [Building_Chatbot.ipynb](https://github.com/SC92113/ChatGPT-Prompt-Engineering/blob/51ed603bd595c4b785f52c8aa221d07f229561b3/Building_Chatbot.ipynb)

### 💡 Key concepts in the project

- **Prompting principles**

  - **Principle 1 - write clear and specific instructions**
  
    - Use delimiters to quote the task and avoid prompt injection to ensure to execute content as a whole, i.e. '', "", ``, <>
    - Ask for structured output formats to respond, i.e. JSON, HTML
    - Check if the conditions are satisfied
    - Few-shot prompting

  - **Principle 2 - give the model time to 'think'**
  
    - Specify steps to complete a task
    - Instruct model to think before conclude and complete a task

  - **Quick access to notebook:** [Prompting_Guidelines.ipynb](https://github.com/SC92113/ChatGPT-Prompt-Engineering/blob/b67c291849502f68af4df5efefc3985a06210c92/Prompting_Guidelines.ipynb)

- **Prompt development lifecycle**
  - **Process**
    - Idea/ Problem
    - Implementation
    - Experimental results
    - Error analysis

  - **Quick access to notebook:** [Prompt_Development_Lifecycle.ipynb](https://github.com/SC92113/ChatGPT-Prompt-Engineering/blob/b67c291849502f68af4df5efefc3985a06210c92/Prompt_Development_Lifecycle.ipynb)

- **Capabilities of prompting**

  - **Summarizing**
    - Summarize a task content based on prompt
    - Can be single/ multiple tasks
    - For multiple tasks
      - Define a List of all required task contents
      - Define for-loop of List
      - Print( i, response, "\n")

  - **Extracting**
    - Extracting is part of natural language processing (NLP)
    - Can be included in the process of summarizing and inferring

  - **Inferring**
    - Help provide basic understanding of a task content
    - Classify sentiment of a task content (Yes/ No)
    - Identify specific sentiments of a task content (What kinds of sentiments)
    - Extract keywords as an understanding of a task content
    - Can be single/ multiple tasks

  - **Transforming**
    - Identify language
    - Translate from language A to language B
    - Tranform to formal and informal tone
    - Tranform from format A to format B, i.e. HTML, JSON
    - Transform from text A to text B, i.e. re-writing, shortening
    - Check gramma and spelling
    - Can be single/ multiple tasks

  - **Expanding**
    - Create a response including all the other functions, i.e. extract and summarize the task content for creating a response

### 📚 References

- OpenAI API: [OpenAI API access](https://platform.openai.com/login?launch)
  - if there is rate and region limit, check out [Limit guide](https://platform.openai.com/docs/guides/rate-limits)
- Best practices for prompt engineering [Prompting FAQ](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-the-openai-api)
- Prompting with OpenAI examples: [Examples](https://platform.openai.com/examples)
- Reference task contents for prompting: [DeepLearning.AI](https://www.deeplearning.ai/)
