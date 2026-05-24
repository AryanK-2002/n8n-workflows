AI News Automation using n8n and Llama 3

Overview :

This project implements a fully automated pipeline for tracking, summarizing and delivering the latest developments in artificial intelligence. It integrates multiple data sources, processes and filters content, and uses a large language model to generate concise, actionable summaries, which are then delivered in real time via Telegram.

The system is designed to demonstrate practical application of AI in workflow automation, combining low-code orchestration with LLM-powered processing.

Key Features :

Multi-source data aggregation from RSS feeds (Hugging Face, Reddit and Product Hunt)

Automated data merging and preprocessing

AI-driven summarization using Llama 3 via Ollama

Conditional filtering to ensure relevance and quality of updates

Real-time delivery through Telegram integration

Modular and extensible workflow design

System Architecture :

The workflow follows a structured pipeline --

Scheduled trigger initiates the workflow at defined intervals

Multiple RSS feeds are fetched in parallel

Data from all sources is merged into a unified stream

Content is cleaned and formatted for processing

Llama 3 generates concise summaries of each update

Conditional logic filters high-quality and relevant items

Final updates are sent to a Telegram channel or user


Tech Stack :

n8n for workflow orchestration

Ollama for local LLM execution

Llama 3 for text summarization

RSS feeds as data sources

Telegram Bot API for notification delivery


Use Case :

This system is built to solve the problem of information overload in the rapidly evolving AI landscape. Instead of manually tracking multiple platforms, users receive curated, summarized updates in a single channel, enabling faster awareness and decision-making.


Output Format :

Each update delivered to Telegram includes --

Title of the update with concise AI-generated summary
