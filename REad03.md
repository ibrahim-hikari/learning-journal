# What is Git:

- Snapshots: each time you made a change it will show you that in the same file by creating a snapshots

- Local Operations: you can do whatever you want on your cloud file in your pc, no need to be connected to the internet.

- Teacking changes: Git allways keep in touch with your file changes.

- loss of data: you have to be sure that the percent that you lost your file is almost 0%.

- States:
 1. Committed: data stored in local data base
 1. Modified: has been some changes in your file that not commited
 1. Staged: committing the last changes to the next snapshot

 ## Get Start

 - downloading Git from the website of Git
 
 - configuration of variables using git config

 - Identity Setting using the following command

 ``` 

 git config --global user.name 'ur name'
 git config --global user.email 'uremail@ex.com'
  
  ```

  - Default Text Editor:
  ```
   $ git config --global core.editor emacs
  ```

  - Check Settings
  ```
  git config --list
  ```

- Getting Help
```
git help command
git command --help
man git-command
```

## Setting up a Git Repository

- Cloning: 
```
~ git clone https://github.com/test mydirectory
```
