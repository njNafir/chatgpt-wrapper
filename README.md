<p align="center">
  <img alt="lwe-logo-small" src="https://github.com/llm-workflow-engine/llm-workflow-engine/assets/43772/6921deac-0964-41a9-84fd-7c2ebce198c0" />
</p>

<h1>
  <p align="center">
    LLM Workflow Engine
  </p>
</h1>

<p id="summary-header" align="center">LLM Workflow Engine (LWE) is a <b>Power CLI</b> and <b>Workflow manager</b> for LLMs.</p>

<h4 id="documentation" align="center">
  <a href="https://llm-workflow-engine.readthedocs.io" target="_blank">
    Read the documentation
  </a>
</h4>

## Welcome!

What would you like to do?

* [Learn about the project](https://llm-workflow-engine.readthedocs.io)
* [Install LWE](https://llm-workflow-engine.readthedocs.io/en/latest/installation.html)
* [Learn how to use it](https://llm-workflow-engine.readthedocs.io/en/latest/how_it_works.html)
* [Read the documentation](https://llm-workflow-engine.readthedocs.io)
* [Learn more about configuration/features](https://llm-workflow-engine.readthedocs.io/en/latest/configuration.html)
* [Troubleshoot common issues](https://llm-workflow-engine.readthedocs.io/en/latest/troubleshooting.html)
* [Upgrade LWE](https://llm-workflow-engine.readthedocs.io/en/latest/upgrading.html)
* [Using GPT4](https://llm-workflow-engine.readthedocs.io/en/latest/model_access.html#gpt4)
* [Report a bug](ISSUES.md)
* [Get support](SUPPORT.md)


## What happend to the original ChatGPT Wrapper project?

The original ChatGPT Wrapper project (created by [mmabrouk](https://github.com/mmabrouk)) lives on in LWE, in the deprecated [browser backend](#playwright-browser-based-deprecated).

While it can still be used, it's become less useful after the release of [OpenAI's Chat Completions API](https://platform.openai.com/docs/guides/gpt/chat-completions-api), and also become harder to maintain due to security lockdowns on [chat.openai.com](https://chat.openai.com).

It was an amazing tool for its time, thank you [mmabrouk](https://github.com/mmabrouk) for all your hard work, it lives on in a new form :)

## Highlights

🤖 LWE lets you use the powerful ChatGPT/GPT4 bot from the **command line**.

💬 **Runs in Shell**. You can call and interact with ChatGPT/GPT4 in the terminal.

💻  **Supports official ChatGPT API**. Make API calls directly to the OpenAI ChatGPT endpoint (all supported models accessible by your OpenAI account)

🔌 **Simple plugin architecture**. Extend LWE with custom functionality

🗣 **Supports multiple LLM providers**. Provider plugins allow interacting with other LLMs (GPT-3, Cohere, Hugginface, etc.)

🔄[**Build workflows**](#workflows). Easily integrate calls to an LLM into larger workflows via Ansible Playbooks

𝑓(𝑥) [**Execute functions**](#functions). Support for [OpenAI functions](https://platform.openai.com/docs/guides/gpt/function-calling)

🐳 **Docker image**. LWE is also available as a docker image. (experimental)

🐍**Python API**. LWE also has a Python library that lets you use ChatGPT/GPT4 in your Python scripts.

:test_tube: **Flask API**. You can use LWE as an API. (experimental)

## Projects built with the original ChatGPT Wrapper

- [bookast: ChatGPT Podcast Generator For Books](https://github.com/SamMethnani/bookast)
- [ChatGPT.el: ChatGPT in Emacs](https://github.com/joshcho/ChatGPT.el)
- [ChatGPT Reddit Bot](https://github.com/PopDaddyGames/ChatGPT-RedditBot)
- [Smarty GPT](https://github.com/citiususc/Smarty-GPT/tree/v1.1.0)
- [ChatGPTify](https://github.com/idilsulo/ChatGPTify)
- [selection-to-chatgpt](https://github.com/collin-murphy/selection-to-chatgpt)

## Contributing

We welcome contributions to LWE! If you have an idea for a new feature or have found a bug, please open an issue on the GitHub repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The original ChatGPT Wrapper project (which LWE grew from) was created and maintained by [mmabrouk](https://github.com/mmabrouk) 
- The original 'browser' backend is a modification from [Taranjeet](https://github.com/taranjeet/chatgpt-api) code which is a modification of [Daniel Gross](https://github.com/danielgross/whatsapp-gpt) code.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=llm-workflow-engine/llm-workflow-engine&type=Date)](https://star-history.com/#llm-workflow-engine/llm-workflow-engine&Date)
