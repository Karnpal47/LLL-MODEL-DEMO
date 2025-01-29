Overview
The LLM Model Generator, utilizing the Gemini API, is designed to automate the creation of README files for various projects, significantly simplifying the documentation process. This tool leverages advanced language models to analyze codebases and generate comprehensive, professional-quality README files.
Features
Code Analysis: Automatically analyzes project files to understand structure and key components.
Enhanced Documentation: Integrates best practices and configuration details into the generated README.
Customizable Output: Allows users to customize README templates with various options.
Multiple API Support: Compatible with different LLM providers, including OpenAI, Anthropic, and Google Gemini.
Getting Started
Prerequisites
Ensure you have Python installed on your system.
Obtain an API key from your chosen LLM provider (e.g., OpenAI, Gemini).
Installation
Clone the repository:
bash
git clone https://github.com/yourusername/llm-model-generator.git
cd llm-model-generator
Install required dependencies:
bash
pip install -r requirements.txt
Set up your API key:
bash
export GEMINI_API_KEY=your_api_key_here
Usage
To generate a README file from a project repository, use the following command:
bash
readmeai --repository https://github.com/yourusername/yourproject --api gemini -m gemini-1.5-flash -o README.md
Customization Options
You can customize the output by adding various flags:
Output File Name: Specify the output file name with -o.
Model Selection: Choose a specific model using -m.
Additional Parameters: Adjust parameters like temperature or badge styles.
