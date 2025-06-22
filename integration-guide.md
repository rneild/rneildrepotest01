# Integration Guide: Workday to Research Administration System

This guide provides a detailed walkthrough for setting up and customizing the Workday–Research Admin System integration.

## Overview
- **Purpose:** Keep research admin HR data in sync with Workday.
- **Scope:** New hires, terminations, and updates.

## Setup Steps
1. Obtain API credentials for both Workday and RAS.
2. Configure environment variables in `.env`.
3. Run `node src/main.js` to test the sync.

## Screenshots
![Sample Screenshot](https://placehold.co/600x200?text=Workday+to+RAS+Sync)

## FAQs
- **Q:** What data is synced?
  **A:** Employee name, email, department, and employment status.
- **Q:** How often does it run?
  **A:** By default, every hour (configurable).

## Troubleshooting
- Check API credentials and network access.
- Review logs in the console output.
