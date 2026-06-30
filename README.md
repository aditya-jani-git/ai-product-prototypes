# AI Tax Planner (Case Study)

## Overview

This project demonstrates an AI-powered Tax Planner solution built using OCR, Retrieval-Augmented Generation (RAG), and Claude AI.

The objective was to automate tax document processing, reduce manual effort, and generate intelligent tax recommendations.

> Note: Production code is proprietary. This repository shares the architecture, prompts, and product approach only.

---

## Problem Statement

Tax professionals manually review multiple financial documents to determine tax recommendations.

Challenges:

- Time-consuming manual reviews
- Human errors
- Inconsistent recommendations
- Poor scalability during peak tax seasons

---

## Solution

The solution uses:

- Amazon Textract for OCR
- RAG for contextual retrieval
- Claude AI for recommendation generation
- Prompt Engineering for structured outputs

---

## High-Level Workflow

1. User uploads tax documents
2. OCR extracts text using Amazon Textract
3. Documents are tagged and classified
4. Relevant knowledge is retrieved through RAG
5. Claude generates tax recommendations
6. User reviews and approves results

---

## Architecture

(See architecture.png)

---

## Sample System Prompt

See:

prompts/system-prompt.md

---

## My Role

Product Owner / Project Manager

Responsibilities:

- Problem discovery
- Product requirements
- User stories
- AI workflow definition
- Stakeholder management
- Sprint planning
- UAT and release management

---

## Technologies

- Claude AI
- Amazon Textract
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering
- Agile/Scrum
- Jira

---
