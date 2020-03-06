
This project automates common procedures that are traversing all repositories 
in this project.

The `update` command executes 'git update' which causes repeatedly prompting 
the user to input their username and password. In order to avoid this 
repetition, it is recommended to set credential helper to 'store' as following:

```
git config --global credential.helper store
```

[modeline]: # ( vim: set fo+=wa spell:)
