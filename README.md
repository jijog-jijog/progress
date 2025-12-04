# githubaction-daily-commit

This repository contains a GitHub Actions workflow that automatically maintains a daily commit streak.

## What it does

The workflow runs three times a day (at 6:00 AM, 1:00 PM, and 10:00 PM IST) and:

- Updates the `streak.txt` file with the current IST timestamp
- Commits the change with the message "Streak commit sucessfull"
- Pushes the commit to the repository

This helps maintain a daily commit streak on GitHub by ensuring at least three commits per day.

## Manual Trigger

You can also trigger the workflow manually from the Actions tab for testing purposes.