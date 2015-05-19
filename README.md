# cf-domain-check

[![Join the chat at https://gitter.im/websummit/cf-domain-check](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/websummit/cf-domain-check?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
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
