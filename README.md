# AI-Based-Resume-Evaluation-and-Feedback-Automation-System
Resume Checker AI Agent is an automated system that analyzes resumes from Google Docs using AI, provides structured feedback, and delivers evaluation reports via email and Telegram. Built using Make, AI Agents, and API integrations, it demonstrates workflow automation and intelligent content analysis.

## Overview
This project implements an intelligent AI Resume Evaluator Agent that analyzes
resumes stored in Google Docs, provides structured feedback, and delivers results
via Telegram and email. The system is built using Make.com automation, Gemini AI,
and Model Context Protocol (MCP) for unified tool access.

## Key Capabilities
- Resume analysis from Google Docs links
- Telegram-based user interaction
- AI-generated structured feedback
- Automated email delivery of evaluation reports
- MCP-based unified system integration

## Tech Stack
- Make.com – Automation and AI Agent orchestration
- Google Gemini AI – Resume analysis and evaluation
- Telegram Bot API – User interaction
- Gmail API – Email delivery
- Google Docs – Resume content source
- MCP (Model Context Protocol) – Unified tool access

## Architecture Overview
The project is implemented in two versions:
1. System Tools based architecture (multiple direct integrations)
2. MCP-enabled architecture (single unified connection)

Detailed architecture documentation is available in the `architecture/` folder.

## Workflow Summary
1. User sends a message or resume link via Telegram
2. Telegram Watcher triggers the AI Agent
3. Resume content is extracted from Google Docs
4. AI Agent evaluates resume using predefined frameworks
5. Results are sent back via Telegram and email

## AI Agent Design
- Strict system prompts with zero flexibility
- Predefined response templates
- Tool-driven execution (no free-form responses)
- Deterministic behavior for consistency

## MCP Integration
Using MCP, all external tools (Google Docs, Gmail, Telegram) are accessed through
a single standardized protocol, improving scalability, security, and maintainability.

## Future Enhancements
- Multi-role resume evaluation
- Scoring and ranking system
- Resume version comparison
- Dashboard for analytics

## Resume Summary
Designed and implemented an AI-powered Resume Evaluator Agent using Make.com,
Gemini AI, Telegram Bot, and MCP to automate resume analysis, feedback delivery,
and communication through a scalable agent-based architecture.
