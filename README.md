# GitHub-Issue-and-PR-Auto-Documenter

**GitHub-Issue-and-PR-Auto-Documenter** is a bot that automatically documents GitHub issues and pull requests, providing helpful summaries of discussions, tags, and relevant contributors. This tool is designed to streamline project management and help new contributors quickly understand active issues and pull requests.


<p align="center">
  <img src="/workspaces/GitHub-Issue-and-PR-Auto-Documenter/img/DALL·E 2024-11-14 04.10.06 - System design diagram of a GitHub bot named 'GitHub-Issue-and-PR-Auto-Documenter.' The bot automatically documents GitHub issues and pull requests, hi.webp" alt="System Design Diagram for GitHub-Issue-and-PR-Auto-Documenter">
</p>

## Features

- **Automated Issue & PR Documentation**: Summarizes discussions, comments, and updates.
- **Tagging of Contributors**: Recognizes and tags relevant contributors based on their activity.
- **Organized Summaries**: Presents concise summaries of issues and PRs for easier navigation.

## System Design

Refer to the diagram for an overview of the bot's architecture, which includes:

- **GitHub Webhooks** to capture events.
- **Bot Handler (API Server)** to process and route events.
- **NLP Processor** for generating summaries.
- **Database** for storing raw and processed data.

## Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone <repo-url>

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt

