<h1 align="center">📜 Code Chronicler Agent </h1>

**CCAgent** is an AI-powered agent that analyzes source code
repositories to automatically generate **technical documentation** and
**architecture diagrams**. It was designed to help developers, teams,
and reviewers quickly understand complex projects with minimal manual
effort.

> "From source code to knowledge."

&nbsp;&nbsp;&nbsp;

## ✨ Features

-   🔍 Automatic source code analysis
-   📝 Technical documentation generation
-   🗺️ Architecture and flow diagrams generation
-   🤖 Integration with Google ADK agents
-   🔐 Support for private repositories (via GitLab tokens)

&nbsp;&nbsp;&nbsp;

## 🏗️ Project Architecture

    ccagent/
    ├── agent/
    ├── services/
    ├── tools/
    ├── config/
    └── assets/

&nbsp;&nbsp;&nbsp;

## 🚀 Technologies

&nbsp;&nbsp;&nbsp;

<table border="0" align="center">
  <tr>
    <td align="center" width="100">
      <a href="https://www.python.org/" target="_blank">
        <img src="https://skillicons.dev/icons?i=py" width="50"/>
        <br>Python
      </a>
    </td>
    <td align="center" width="100">
      <a href="https://google.github.io/adk-docs/" target="_blank">
        <img src="./assets/images/agent-development-kit.png" width="50"/>
        <br>ADK
      </a>
    </td>
    <td align="center" width="100">
      <a href="https://ai.google.dev/gemini-api/docs?hl=pt-br" target="_blank">
        <img src="./assets/images/gemini.png" width="50"/>
        <br>Gemini
      </a>
    </td>
    <td align="center" width="100">
      <a href="https://python-poetry.org/docs/" target="_blank">
        <img src="./assets/images/poetry.png" width="50"/>
        <br>Poetry
      </a>
    </td>
    <td align="center" width="100">
      <a href="https://graphviz.org/" target="_blank">
        <img src="./assets/images/graphviz.png" width="50"/>
        <br>Graphviz
      </a>
    </td>
  </tr>
</table>

&nbsp;&nbsp;&nbsp;


## 📋 Prerequisites
> [!WARNING]
> To run the project, you need the following tools and services:

### Local tools
-   Python = 3.12
-   Poetry
-   Graphviz

### External services / LLM
-   Access to Gemini 2.5 Flash (Google LLM)

&nbsp;&nbsp;&nbsp;

## 🚀 Getting Started

### Clone the repository

``` bash
git clone https://github.com/MichaelDouglasPIX/cc-agent.git
cd ccagent
```

### Install dependencies

``` bash
poetry install
```

### Configure environment variables
> [!IMPORTANT]
> Rename the `.env_example` to  `.env` and update the fields.


``` env
GITLAB_TOKEN=your_gitlab_token_here
GOOGLE_GENAI_USE_VERTEXAI=true_or_your_vertexai_value
GOOGLE_API_KEY=your_google_api_key_here
```

### Run the project

``` bash
poetry run adk web --port 8000
```

&nbsp;&nbsp;&nbsp;

## 📄 License

MIT License

------------------------------------------------------------------------


