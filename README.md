# spm-jira-github-integration


## Overview

This project is a GitHub Action that integrates with Jira to create issues based on GitHub events. It is designed to be used in a GitHub workflow to automate the creation of Jira issues when specific events occur in a GitHub repository.

## Features

- **Event-Driven**: Creates Jira issues based on GitHub events such as pull requests, issues, or comments.
- **Customizable**: Allows customization of the Jira issue fields and content.
- **Secure**: Uses GitHub secrets to securely store Jira API credentials.

## Prerequisites

- A Jira account with API access.
- A GitHub repository where you want to set up the integration.
- Basic knowledge of GitHub Actions and YAML.

## Setup Instructions

1. **Create a Jira API Token**:
   - Log in to your Jira account.
   - Navigate to your account settings.
   - Create an API token and keep it secure.

2. **Store Jira Credentials in GitHub Secrets**:
   - Go to your GitHub repository.
   - Navigate to `Settings > Secrets`.
   - Add the following secrets:
     - `JIRA_BASE_URL`: Your Jira instance URL.
       
