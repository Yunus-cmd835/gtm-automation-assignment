# GTM Automation Assignment

## Overview
Intelligent lead generation and routing system built with n8n that processes 100+ leads from Reddit and LinkedIn, enriches data, and implements multi-channel scoring.

## Files
- `n8n_workflow.json` - Complete n8n workflow
- `sample_data.csv` - Sample output data
- `assignment_summary.md` - 500-word summary

## Setup Instructions
1. Import `n8n_workflow.json` into your n8n instance
2. Update API credentials:
   - Snov.io: Replace client_id and client_secret
   - NumVerify: Replace API key
3. Update data source URLs if needed
4. Configure Google Sheets integration

## Features
- Multi-source data collection (Reddit + LinkedIn)
- Email verification (Snov.io + pattern fallback)
- Phone validation (NumVerify + regex fallback)  
- 4-channel scoring algorithms
- Intelligent routing strategies
- Lead quality grading (A+ to C)