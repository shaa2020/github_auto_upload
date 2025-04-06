# GitHub Auto-Upload Script

## Description
A Bash script designed to automate the process of creating, configuring, and uploading content to a GitHub repository. This tool simplifies repository management by handling repository creation, local Git setup, file staging, committing, and pushing—all from a single command-line interface.

## Features
- **GitHub Integration**: Creates repositories via the GitHub API or uses existing ones.
- **Flexible File Management**: Add all files or specific files to the commit.
- **Customizable**: Supports custom repository paths, branch names, and commit messages.
- **Secure**: Temporarily embeds authentication tokens and cleans them up post-use.
- **Logging**: Detailed logs for troubleshooting and audit purposes.
- **User-Friendly**: Color-coded output and clear prompts.

## Prerequisites
- **Bash Environment**: Compatible with Linux/macOS systems with Bash installed.
- **Git**: Required for version control operations.
- **curl**: Used for GitHub API interactions.
- **GitHub Personal Access Token (PAT)**: Must have `repo` scope for repository management.
- **Sudo Privileges**: Needed to install dependencies if not already present.

## Installation
1. **Download the Script**:
   ```bash
   curl -O https://raw.githubusercontent.com/<shaa2020>/<github_auto_upload>/main/github_auto_upload.sh
