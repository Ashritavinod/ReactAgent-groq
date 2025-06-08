# Groq React Agent

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

An interactive agent built with Groq API that demonstrates reasoning and tool usage capabilities through a Thought-Action-Observation loop.

## Features

- **Interactive Agent System**: Implements a reactive agent that can perform calculations and retrieve planetary data
- **Dual Interaction Modes**:
  - Manual step-by-step execution (for learning/development)
  - Automated loop execution (for production use)
- **Custom Tools**:
  - Mathematical calculations (`calculate`)
  - Planetary mass lookup (`get_planet_mass`)
- **Groq API Integration**: Leverages Groq's fast LLM inference

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/groq-react-agent.git
cd groq-react-agent
```
2.Create and activate a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate  # Linux/MacOS
venv\Scripts\activate     # Windows
```
3.Install dependencies:

```bash
pip install -r requirements.txt
```
4.Set up your environment variables:

```bash
echo "GROQ_API_KEY=your_api_key_here" > .env
```
Usage-Jupyter Notebook
```bash
jupyter notebook groq_agent.ipynb



