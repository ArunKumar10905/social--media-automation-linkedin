# AI-Powered Social Media Automation Using n8n

## Project Overview
This project automates AI technology news publishing on LinkedIn using n8n, Google Sheets, and Google's Gemini Flash model.

It collects article URLs, processes and summarizes the content, analyzes important information, generates professional LinkedIn posts, and publishes them automatically.

## Workflow Architecture

Google Sheets Trigger
↓
Gemini Flash – Article Processing
↓
LLM Chain – Article Summarization
↓
LLM Chain – Article Analysis
↓
LLM Chain – LinkedIn Post Generation
↓
LinkedIn – Automatic Post Publishing

## Technologies Used
- n8n – Workflow Automation
- Google Sheets – Article URL Management
- Google Gemini Flash – AI Article Processing
- LLM Chains – Summarization, Analysis and Content Generation
- LinkedIn API – Automated Publishing

## Key Features
- Automated article collection through Google Sheets
- AI-powered article summarization
- Article analysis using Gemini
- Professional LinkedIn post generation
- Automated LinkedIn publishing

## Learning Outcomes
- Understanding n8n workflow automation
- Working with AI models and LLM chains
- Integrating external services and APIs
- Building practical automation workflows

## Project Screenshots
See the screenshots folder for workflow and execution examples.

## How to Use
1. Import the workflow JSON into your n8n instance.
2. Configure Google Sheets credentials.
3. Configure Gemini API credentials.
4. Configure LinkedIn credentials.
5. Update the required Google Sheets and LinkedIn settings.
6. Activate the workflow and test it.

**Note:** API credentials are not included in this repository. Configure your own credentials before running the workflow.
