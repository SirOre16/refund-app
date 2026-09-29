# AI-Powered Customer Support Refund System

A full-stack customer support refund system built as part of the **Worknoon Full Stack AI Integration Product Challenge**.

The application allows customers to submit refund-related requests and uses customer/order data, refund policy rules, and AI assistance to help determine whether a request should be **Approved**, **Denied**, or **Escalated for human review**.

## Note

The DeepSeek API key is currently hardcoded in the application for temporary assessment/demo purposes.

The API key will be deleted from the DeepSeek dashboard after one week following the assessment period.

## Features

- Customer-facing refund request chat
- AI-powered customer support responses
- DeepSeek AI integration
- Customer and order lookup
- Refund policy evaluation
- Refund decisions:
  - Approved
  - Denied
  - Escalated
- Support/admin dashboard
- Refund decision reasoning and audit notes
- Synthetic customer and order data
- Prepared SQL queries
- Basic protection against attempts to bypass refund rules
- Simple and easy-to-test interface
- Docker support for running the application


## Project Structure

refund-app/
│
├── index.php
├── ai.php
├── admin.php
├── db.php
├── database.sql
├── modafvibe.png
├── chat-header.php
├── docker-compose.yml
├── Dockerfile
└── README.md
