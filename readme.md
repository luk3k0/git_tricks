## Clone then create nonexistent repo on other git

```sh
git clone --bare https://git-codecommit.ap-northeast-1.amazonaws.com/v1/repos/<repo name>
cd <repo name>.git
git push https://git.example.net/namespace/<repo_name>.git '*:*'
```
