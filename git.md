# Helpful git commands

```curl -u '[your github username]' https://api.github.com/user/repos -d '{"name":"[repo-name-to-create]"}'```

## credential caching

* Temporary in-memory caching

  ```git config --global credential.helper cache```  [Caching your GitHub password in Git](https://help.github.com/articles/caching-your-github-password-in-git/#platform-linux)
  
* plain text store

  ``` git config --global credential.helper store```

* Securly store credentials [Using credential store](https://askubuntu.com/a/776335)

  ```text
  sudo apt-get install libgnome-keyring-dev
  sudo make --directory=/usr/share/doc/git/contrib/credential/gnome-keyring
  git config --global credential.helper /usr/share/doc/git/contrib/credential/gnome-keyring/git-credential-gnome-keyring
  ```
