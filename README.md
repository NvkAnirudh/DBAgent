# DBA(gent)

A powerful agent-based system that leverages OpenAI's Agents SDK and Assistants API with Code Interpreter along with AgentOps AI for tracing and observability to perform advanced data analysis on CSV files.

## Overview
This project implements an agent architecture that automates data analysis tasks using GPT-4 and Code Interpreter. The system allows users to provide CSV files and natural language queries, and returns comprehensive insights, statistics, and visualizations.

## Features

Agent-Based Architecture: Uses a flexible agent framework to coordinate analysis tasks
OpenAI Assistants API Integration: Leverages the Code Interpreter capability for in-depth data analysis
CSV Data Analysis: Process and analyze any CSV dataset
Natural Language Queries: Ask questions about your data in plain English
Visualization Support: Automatically generates and captures visualizations created during analysis
Tracing and Monitoring: Built-in support for AgentOps tracing to monitor agent performance

## Requirements

Python 3.8+ <br>
OpenAI API key <br>
AgentOps API key (for tracing)

## Installation

Clone this repository:
```
clone https://github.com/yourusername/advanced-data-analysis-agent.git
```
cd advanced-data-analysis-agent

Install the required dependencies:
```
install -r requirements.txt
```

Create a .env file with your API keys:
```
OPENAI_API_KEY=your_openai_api_key
AGENTOPS_API_KEY=your_agentops_api_key
```
