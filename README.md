# ASaP
ASaP is a Windows desktop application built with WPF and .NET 8 for collecting anonymous patient satisfaction surveys. The app is designed for use in a hospital environment and presents a structured questionnaire, records responses locally, and can trigger update checks and notifications.

## Overview
This project provides a touch-friendly survey experience for gathering feedback from patients. The questionnaire content is loaded from an embedded JSON file, and responses are stored in a local SQLite database.

## Features
- WPF-based desktop interface for survey collection
- Embedded questionnaire definition with configurable questions
- Local persistence using SQLite
- Automatic update check support
- Optional notification email integration for update events

## Tech Stack
- .NET 8
- WPF
- Entity Framework Core
- SQLite
- Newtonsoft.Json

## Requirements
- Windows 10/11

## Notes
This application appears to be intended for internal or institutional use and may include environment-specific integrations such as email notifications and update distribution.
