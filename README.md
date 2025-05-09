# API GitHub User Activity

A simple command line interface (CLI) to fetch the recent activity of a GitHub user and display it in the terminal.

## Features

- Provide the GitHub username as an argument when running the CLI.
    - github-activity <username>
- Fetch the recent activity of the specified GitHub user using the GitHub API. You can use the following endpoint to fetch the user’s activity:
    - ##### https://api.github.com/users/<username>/events
    - ##### Example: https://api.github.com/users/kamranahmedse/events
- Display the fetched activity in the terminal.
    - Output:
        - Pushed 3 commits to kamranahmedse/developer-roadmap
        - Opened a new issue in kamranahmedse/developer-roadmap
        - Starred kamranahmedse/developer-roadmap
        - ...
- You can learn more about the GitHub API here.
- Handle errors gracefully, such as invalid usernames or API failures.
- Use a programming language of your choice to build this project.
- Do not use any external libraries or frameworks to fetch the GitHub activity.


## Installation

1. Make sure you have [Node.js](https://nodejs.org) installed.

2. Clone or download this project.

3. To run use this command : `node cli_github_user_activity.js lladrian`
  - Usage: node cli_github_user_activity.js [command]
  - Commands:
     - **username**  List of recent activity of a GitHub user.


4. https://roadmap.sh/projects/github-user-activity
