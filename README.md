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

### Next steps
- Add workflow to welcome first pull request.
- Add scheduled maintenance job.