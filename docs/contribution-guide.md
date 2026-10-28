# StudyBuddy Contribution Guide

## Start a task
```bash
git switch main
git pull origin main
git switch -c feature/short-task-name
```

Use a short branch name that describes the task. Do not work directly on `main`.

## Check, commit and push
```bash
git status
git diff
git add path/to/your/files
git commit -m "Describe the change"
git push -u origin feature/short-task-name
```

Add only the files you intend to commit. Use clear commit messages.

## Pull request checklist
- Explain what changed.
- Explain how you tested it.
- Link the issue, for example `Closes #1`.
- Request a sibling's review.
- Respond respectfully to feedback.
- Merge only after review.

## Review etiquette
Be specific, kind and constructive. Ask questions when something is unclear. Focus on improving the code, not criticizing the person.

## If a merge conflict happens
Read the conflict markers, discuss the intended result with the author, resolve the file, test it and commit the resolution.
