
a. go to GitHub, click on your profile pic,
 Settings → Developer settings → Personal access tokens → Tokens (classic)

b. click "Generate new token (classic)"

c. follow instructions: 
- a descriptive name
- scopes: repo or better
- expiration date: max possible

d. generate, copy/paste it in a secret .txt file (it won't be shown again)

e. now, run git clone or push or pull so you get prompted for credentials:
Username: your GitHub username (not your email)
Password: paste the PAT
