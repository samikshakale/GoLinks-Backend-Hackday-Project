# GoLinks-Backend-Hackday-Project

## Specification

Create an API endpoint that returns the statistics for all of the user's repositories.

These stats include:
- Total repository count
- Total stargazer count
- Total forks count
- Average size of a repository (MB)
- List languages used and their counts (ordered by most to least popular)

## How to Run

Run the following from the terminal.

```console
$python3 statistics.py <username> <forked>
```
- username: username of the user you are looking at
- forked: flag set to either True or False
  - True: report stats on ALL REPOS
  - False: report stats on NON FORKED REPOS

## Important
Need to have python3 installed for some commands to work
