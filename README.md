# git-tips

# Change token
```
git config --local --unset remote.origin.url
git config --local --add remote.origin.url https://oauth2:_YOUR_TOKEN_@gitlabee.server.tld/user/repo.git
git config --local -l
```
