# AI-Powered Data Analysis Automation using n8n

## Project Overview

This project automates spreadsheet analysis and email reporting using **n8n**, **OpenAI**, **Google Sheets**, and **Gmail**.

The workflow receives a request through the n8n chat interface, retrieves relevant data from Google Sheets, uses an AI Agent to generate an analysis, and sends the report to a configured email recipient through Gmail.

## Objectives

- Automate spreadsheet data analysis.
- Generate easy-to-understand summaries and insights.
- Reduce repetitive manual reporting.
- Deliver analysis reports through email.

## Technologies Used

- **n8n** — workflow automation
- **OpenAI Chat Model** — AI-generated analysis and responses
- **Google Sheets** — data source
- **Gmail** — email delivery
- **Simple Memory** — conversational context

## Workflow

1. **Chat Trigger:** Receives the user's analysis request.
2. **AI Agent:** Coordinates the analysis process and tool usage.
3. **OpenAI Chat Model:** Generates the response and insights.
4. **Google Sheets:** Retrieves spreadsheet data.
5. **Simple Memory:** Maintains conversational context where applicable.
6. **Gmail:** Sends the generated report by email.

## How It Works

1. The user submits a request through the n8n chat interface.
2. The AI Agent uses the connected Google Sheets tool to retrieve relevant data.
3. The AI generates a summary or analysis based on the information returned.
4. The Gmail tool sends the report to the configured recipient.
5. The workflow execution can be reviewed in n8n to check for errors.

## Setup Instructions

1. Download the workflow JSON file from this repository.
2. Sign in to your n8n instance.
3. Import the JSON workflow into n8n.
4. Configure your own OpenAI, Google Sheets, and Gmail credentials.
5. Select the correct spreadsheet and sheet.
6. Configure the intended email recipient and verify the email subject/body mappings.
7. Test each integration using non-sensitive sample data.
8. Publish the workflow after the complete workflow test succeeds.

> **Note:** Exported workflows do not include working credentials. Each user must configure their own credentials and permissions in n8n. Node settings may need adjustment depending on the n8n version and account configuration.

## Security and Privacy

- Never commit API keys, passwords, access tokens, or credential exports.
- Use n8n's credential management for authentication.
- Avoid publishing private spreadsheet IDs, personal information, or confidential data.
- Use sample or non-sensitive data for public demonstrations.
- Check email recipients and spreadsheet permissions before running the workflow.

## Current Status

Basic chat-triggered data analysis and email reporting workflow. Features should be described as complete only after they have been tested successfully.

## Future Enhancements

- Scheduled daily or weekly reports
- Data validation and cleaning
- Explicit KPI calculations
- Historical reporting and period-over-period comparisons
- Anomaly detection and conditional alerts
- Error notifications and retry handling
- Power BI dashboard integration

## Author

**Sejal Bhole**

