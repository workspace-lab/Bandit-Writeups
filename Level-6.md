# Bandit Level 6

## Objective
Find a file owned by a specific user and group.

## Commands Used

```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat filepath
```

## Explanation
Searched the filesystem while suppressing permission errors.

## What I Learned
- Searching the filesystem
- Redirecting errors
- Ownership filtering
