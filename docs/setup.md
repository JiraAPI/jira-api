## Project Setup

To run the scripts against your instance, do the following:

0. clone this repo:
   1. `git clone https://github.com/JiraAPI/jira-api`
1. Create a file:  `.host` and enter the URL of your host like:  `https://<host>.atlassian.net`
2. Generate an API key in your account.
3. Enter that key in file:  `.api-key`
4. Create these two files:
   1. `.user` (containing your login/email address to your site)
   2. `.password` (containing your password to your site)
5. Then run:
   1. cd `bin/jira`
   2. ./gen-token

---
Run a script:
1. cd `bin/jira`
2. ./create-meta-api-key