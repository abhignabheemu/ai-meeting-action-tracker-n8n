# AI Meeting Action Tracker using n8n

## Overview

This project automates extraction of meeting action items using OpenAI and n8n.

The workflow:

1. Accepts meeting notes
2. Extracts tasks, owners, and due dates
3. Stores action items in Google Sheets
4. Sends approval-based notifications
5. Clears processed records

## Tech Stack

- n8n
- OpenAI GPT-4o-mini
- Google Sheets
- Gmail / Outlook

## Workflow

Meeting Notes
→ OpenAI
→ Extract Tasks
→ Google Sheets
→ Approval Check
→ Email Notification
→ Clear Sheet

## Features

- AI-powered task extraction
- Approval workflow
- Email summaries in table format
- Google Sheets integration
- Low token consumption

## Import Workflow

Import `workflow.json` into n8n.

## Screenshots

(Add screenshots here)
