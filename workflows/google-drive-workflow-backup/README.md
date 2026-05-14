# Google Drive Workflow Backup for n8n

Automatically backup all your n8n workflows to Google Drive as JSON files.

## Features

- Backup every workflow automatically
- Create dated backup folders
- Upload workflows as JSON
- Automatically delete older backup folders
- Prevent duplicate backups
- Community-template ready
- No hardcoded credentials

## Required Credentials

- Google Drive OAuth2
- n8n API

## Setup

1. Add your n8n API credentials
2. Add your Google Drive credentials
3. Configure your backup folder
4. Activate the workflow

## Included Logic

- Creates backup folder
- Gets all workflows
- Loops through workflows
- Converts workflows to JSON
- Uploads backup files
- Cleans up old backup folders

## Notes

This workflow is designed for educational and production usage.

Always test deletion logic carefully before using in production environments.
