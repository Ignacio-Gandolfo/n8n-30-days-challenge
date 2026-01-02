# Day 02 – Daily Calendar Events Reminder

## Goal
Receive an automatic email every day with the events scheduled for **tomorrow**.

---

## What this automation does
- Runs daily at a scheduled time
- Fetches tomorrow’s events from Google Calendar
- Formats them into a simple, readable list
- Sends the summary via email using Gmail

---

## Why this matters
A small but common friction:
checking the calendar multiple times or forgetting meetings.

This automation removes that step and starts the day with clarity.

---

## Services used
- n8n
- Google Calendar
- Gmail

---

## Setup
1. Import the `workflow.json` into n8n
2. Connect your Google Calendar credentials
3. Connect your Gmail credentials
4. Adjust the schedule time if needed
5. Activate the workflow
