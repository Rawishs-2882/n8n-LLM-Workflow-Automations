<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:F8BBD0,50:CE93D8,100:B39DDB&height=180&section=header&text=n8n%20LLM%20Automations&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=OpenAI%20%2B%20Gmail%20%2B%20Sheets%20%2B%20Airtable&descAlignY=58&descSize=15)

</div>

## Overview

A collection of n8n workflows that connect OpenAI models to everyday tools like Gmail, Google Sheets and Airtable, turning repetitive data processing and notification tasks into automated pipelines that run without manual intervention.

## Key Features

### OpenAI powered processing
Incoming data is passed through OpenAI models for tasks like summarization, classification or extraction before being routed onward.

### Gmail automation
Workflows can read, label, and send emails automatically as part of a larger automation chain.

### Google Sheets integration
Structured results are written directly into Sheets, keeping a live, shareable record without manual data entry.

### Airtable integration
Airtable bases are updated automatically, useful for tracking structured records that benefit from Airtable's views and relations.

### Reusable workflow exports
Every workflow is exported as JSON, so it can be imported into any n8n instance and adapted quickly.


## Tech Stack

<div align="center">
<img src="https://tech-orbit.wontory.dev/api?title=n8n&tech=n8n,openai&size=420&duration=20" alt="tech stack orbit" width="420" />
</div>

n8n as the automation engine, with the OpenAI API, Gmail API, Google Sheets API and Airtable API connected as nodes within each workflow.

## How It Works

Each workflow starts from a trigger such as a new email, form submission or scheduled run. Data flows into an OpenAI node for processing, and the result is routed to one or more destination nodes, whether that is Gmail, Sheets or Airtable, depending on the workflow's purpose.

## Setup and Run

1. Import the workflow JSON files from `/workflows` into your own n8n instance.
2. Configure credentials for OpenAI, Gmail, Google Sheets and Airtable inside n8n.
3. Adjust trigger conditions and destination nodes to match your use case.
4. Activate the workflow and monitor executions from the n8n dashboard.

## Roadmap

- Add a Slack notification workflow
- Add error handling and retry logic across all workflows
- Publish a workflow template for lead qualification

## Status

> **Status:** This repository was scaffolded from the project description on the author's resume. Source code is being migrated and added here in stages. Reach out using the contact links below if you would like early access to the implementation.

## Let's Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rawish0922@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rawishsarfraz)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rawishs-2882)
[![Phone](https://img.shields.io/badge/Call-+92--332--8747138-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+923328747138)

</div>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:B39DDB,50:CE93D8,100:F8BBD0&height=80&section=footer)

</div>
