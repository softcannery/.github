﻿## Before Use
- Create service [GitHub token](https://github.com/settings/tokens/new) with next permissions:
```
repo:status
repo_deployment 
public_repo 
repo:invite 
security_events
workflow
write:packages
read:packages
read:org
notifications
read:discussion
project
read:project
manage_runners:enterprise
```
- Create Organization secret(or Repository secret for all needed repositories) with **ACTIONS_TOKEN** name and **service token** value
![img.png](images/img.png)


## 
