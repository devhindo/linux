# Linux 

- [How To Work With Multiple Github Accounts on a single Machine](https://gist.github.com/rahularity/86da20fe3858e6b311de068201d279e3)
     when getting a new repo:
  ```bash
  $ git config user.email "<email>"
  $ git config user.name "<username>"
  $ git remote add origin `git@github.com-<my_username>:{owner-user-name}/{the-repo-name}.git`
   ``` 

  - if `$ ssh-add -K ~/.ssh/id_rsa ` didn't work : [solution](https://stackoverflow.com/a/66350907).

- make all commands run as sudo : [solution](https://askubuntu.com/a/192050)

  - ```bash
    sudo -i
    ```
