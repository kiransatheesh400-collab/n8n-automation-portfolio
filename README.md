## AI Lead Qualification System

## Problem

Businesses receive many inquiries and spend time manually identifying serious prospects.

## Solution

This workflow receives lead information through a webhook, sends it to Gemini AI for analysis, and categorizes the lead automatically.

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
