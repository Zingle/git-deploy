This package installs the `git deploy` command.  This command can be used to
perform the proper steps necessary to push a deployment tag which triggers a
Travis-CI deployment.

Install
=======
```sh
sudo -H npm install -g @zingle/git-deploy
```

Use
===
```sh
# enter git repo directory
git deploy beta                 # tag current HEAD as 'beta'
git deploy release              # tag current HEAD as 'release'
```
