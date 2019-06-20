# slacknowdemopython
Demo showing how to use Slack with Now serverless, Python and Flask including call to Slack API

## Requirements
- Python 3

Needed Python packages:
- flask
- json
- slackclient from https://github.com/SlackAPI/python-slackclient (install with `pip3 install slackclient==2.0.0` !!)

## Installation
1. Install missing python packages (if any)
2. Fork this repo on github
3. Connect your now account with your github account
4. Make sure the now app on github is connected to your repo
5. Once you pushed a change you should get an alias to your repo on the now dashboard
6. Create a Slack app in your workspace, add a slash command and use the alias from now as request URL for the slash command
7. Add scopes `channels:read` and `groups:read`
8. Install your Slack app into your workspace
9. Retrieve the token from the Oauth page of your app and set the environment variable SLACK_TOKEN with it

