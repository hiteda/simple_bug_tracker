# Simple Bug Tracker

## Rough Outline
- Create bug report (Create)
    - Summary
    - Details
    - How found
    - Severity
    - Attach files
    - Created by
    - Assigned to
    - Date created
    - Last updated
- Display bug reports (Read)
    - List view
        - Show summaries, severity, assigned to, and date created, create report button
        - Search
        - Sort
    - Detailed view - All info, delete and edit buttons
- Edit bug report (Update)
- Delete bug report (Delete)

## Database Schema
- Bug Report
    - ID
    - Summary (string) 1st iteration
    - Details (string) 1st iteration
    - How found (string) 1st iteration
    - Severity (int: 1-5) 1st iteration
    - Created by (string, ID) 2nd iteration
    - Assigned to (string, ID) 2nd iteration
    - Date created (date) 1st iteration
    - Last updated (date) 1st iteration
- User (2nd iteration)
    - ID
    - Username (string)
    - Google Auth ID (string)
- File (3rd iteration)
    - ID
    - Link (string)
    - Description (string)
- file_reports (3rd iteration) junction table
    - File ID (string)
    - Report ID (string)