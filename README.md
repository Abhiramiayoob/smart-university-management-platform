# Smart University Management Platform

An n8n-based workflow automation project designed to support routine university management tasks through Google Sheets and Telegram.

## Project Overview

This project contains five independent workflows that demonstrate automation for academic reminders, student record management, deadline tracking, study planning, and progress reporting.

## Workflows

1. **Assignment Reminder** — Sends Telegram reminders for pending assignments.
2. **Student Records** — Stores student information in Google Sheets.
3. **Deadline Tracker** — Retrieves pending assignment records and sends Telegram notifications.
4. **Study Planner** — Formats and delivers a predefined study schedule through Telegram.
5. **Weekly Progress Report** — Formats and sends a sample student progress report through Telegram.

## Technologies Used

- n8n
- Google Sheets
- Telegram Bot
- Docker Desktop
- JSON workflow exports

## Project Files

The repository includes exported n8n workflow files, workflow documentation, an architecture diagram, and the project presentation.

## Limitations

The current prototype uses sample data. The study planner and progress report use predefined values, and the deadline tracker checks assignment status rather than prioritizing reminders by due date.

## Future Enhancements

- Integration with a live university database
- Due-date-based reminders
- AI-generated study plans and progress reports
- A student dashboard and improved access controls

## Disclaimer

This project is an educational prototype developed for the AI/LLM Summer School. It is not a production-ready university management system.
