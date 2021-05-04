# git-tips

# Credentials
```
git config --global user.email "user@domain"
git config --global user.name "First NAME"
git config --global credential.helper store
```
# Change token
```
git config --local --unset remote.origin.url
git config --local --add remote.origin.url https://oauth2:_YOUR_TOKEN_@gitlabee.server.tld/user/repo.git
git config --local -l
```
