# git-push-multiple-remotes
### Manual configuration for pushing on multiple remotes

In the `.git/config` file you can add multiple urls to a defined remote:

```
[remote "all"]
    url=ssh://user@server/repos/g0.git
    url=ssh://user@server/repos/g1.git
```
     
Source from: [Stack Overflow](https://stackoverflow.com/questions/4255865/git-push-to-multiple-repositories-simultaneously#answer-4255934)
