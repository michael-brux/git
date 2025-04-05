# Git Configuration
View all settings:
```
$ git config --list
```
... and show where they are comming from:
```
$ git config --list --show-origin
```
## Identity
"first thing you should do when you install Git is to set your user name and email address" - "every Git commit uses this information, and it’s immutably baked into the commits you start creating"
```
$ git config --global user.name "Max Mustermann"
$ git config --global user.email me@example.com
```
# References
[First Time Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
