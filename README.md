## Workflows implemented

### 1. Hello Actions
Trigger: on push  
Purpose: Demo basic GitHub Actions run  
Output: Prints runner info and message in logs.

### 2. Auto Label Issues
Trigger: on issue opened or edited  
Purpose: Automatically add labels based on keywords in title/body.  
How to test:
- Create a new issue with keywords like "bug", "feature", "documentation".
- The workflow will auto-add a label.

### 3. Welcome First PR
Trigger: on pull request opened  
Purpose: Automatically welcome first-time contributors.  
Output: Posts a thank you comment on the first Pull Request of a new user.

### 4. Weekly Maintenance
Trigger: schedule (every Monday at 8:00) or workflow_dispatch  
Purpose: Clean up stale issues that have been inactive for 30 days.  
Output: Adds 'stale' label to inactive issues and closes them after 7 days if no update.