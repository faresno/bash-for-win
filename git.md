# Helpful git commands

```curl -u '[your github username]' https://api.github.com/user/repos -d '{"name":"[repo-name-to-create]"}'```

## credential caching

* Temporary in-memory caching

  ```git config --global credential.helper cache```  [Caching your GitHub password in Git](https://help.github.com/articles/caching-your-github-password-in-git/#platform-linux)

* Securly store credentials [Using credential store](http://stackoverflow.com/a/32470658)

  ```git config --global credential.helper libsecret```
