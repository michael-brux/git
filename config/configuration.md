# Git Configuration
## View all settings
To show all settings, use the following command:
```
$ git config --list
```
Additionally display where the settings originate:
```
$ git config --list --show-origin
```
## Identity
The first thing you should do when you install Git is to **set your user name and email address**. Every Git commit uses this information, and it’s **immutably baked into the commits** you make 
```
$ git config --global user.name "Max Mustermann"
$ git config --global user.email me@example.com
```
# References
[First Time Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
