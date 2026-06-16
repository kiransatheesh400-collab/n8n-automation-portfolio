# n8n-automation-portfolio
Business automation workflows built using n8n and AI to reduce manual work and improve efficiency.
# 1.AI Lead Qualification System

## Overview

This workflow automatically evaluates incoming leads using AI and categorizes them as High, Medium, or Low quality.

## Problem

Businesses receive many inquiries and spend time manually identifying serious prospects.

## Solution

The workflow receives lead information through a webhook, sends it to Gemini AI for analysis, and categorizes the lead automatically.

## Workflow

Webhook → Gemini AI → IF Node → Google Sheets

## Technologies Used

* n8n
* Google Gemini
* Google Sheets
* Webhooks

## Input Example

Lead Message:
"Need an ecommerce website. Budget ₹75,000."

## Output Example

Score: 9

Category: High

Reason: Clear requirements and budget provided.

## Screenshots

See the screenshots folder.

## Workflow Export

The workflow1.json file is included in this repository.
