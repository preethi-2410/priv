# Graph-Greener: GitHub Contribution Graph Generator

A simple tool to fill your GitHub contribution graph with commits on custom dates.

## Features

- Generate commits with random dates within the last year
- Customize the number of commits
- Specify which file to modify for commits
- Automatic handling of remote repository setup

## Setup

1. Create a new GitHub repository to use with this tool
2. Clone the repository to your local machine
3. Copy the `main.py` script into your repository

## Usage

```bash
python main.py
```

Follow the prompts to:
1. Enter the number of commits you want to make
2. Specify the repository path (default is current directory)
3. Choose which file to modify (default is data.txt)

If you haven't set up a remote repository yet, the script will guide you through the process.

## Requirements

- Python 3.6+
- Git installed and configured

## Tips

- Use a dedicated repository for this tool to avoid cluttering your main projects
- Make sure your GitHub account is properly configured with your local Git