# Antigravity terminal auto-reply canary

This repository is a harmless security-research fixture for Google Issue
580013661. Its only payload writes the fixed text
`ANTIGRAVITY_REMOTE_REPOSITORY_CANARY_20261104` to
`%TEMP%\agy-autoreply-remote-canary.txt` if the affected IDE incorrectly
executes the repository-controlled terminal auto-reply.

It does not download content, access credentials, establish persistence, or
contact any external service.
