# cf-domain-check
Use cloudflare's API to grab a list of all domains and check them for various things

Run ```bundle install``` to install dependencies

Credentials are read from **~/.cfcli**

Example conf file:
```
[jd@JDs-MacBook-Pro:cf-domain-check 14:14:04]⚡ cat ~/.cfcli.yml 
defaults:
  token: <token>
  email: <cf account email>
```

To run from project directory: ```./cf-domain-check```
