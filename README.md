**AutoTestAgent**


This project uses a team of AI agents to fully automate the software testing process. It reads a Jira ticket, writes the test code, runs the tests, and reports the results back to Jira.

**Core Features**

* Automated Requirement Analysis: Reads and understands Jira tickets.

* AI-Powered Test Generation: Creates test scripts automatically.

* Optimized Test Execution: Runs tests efficiently and monitors performance.

* Intelligent Bug Reporting: Analyzes failures and creates detailed bug reports in Jira.

Getting Started
This project is designed to be run in a Google Colab notebook.

1. Installation
Run the first code block in the notebook to install all the necessary libraries.

# Run this block first to install all the required libraries.
!pip install -q crewai==0.28.8 crewai-tools==0.1.6 google-generativeai 
!pip install -q python-jira pytest playwright pytest-html requests faker pyyaml pytest-xvfb
# ... and other dependencies

2. Usage
Run the main script cell.

Choose "Run Full Test Automation" from the menu.

Follow the prompts to enter your API keys and credentials.

Provide the Jira Ticket ID and Project Key when asked.

The AI crew will then take over and complete the entire testing process.
