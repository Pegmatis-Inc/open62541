# Pegmatis open62541 Repository

This repository is hosted by Pegmatis and tracks the official open62541 repository.

- `origin`: `https://github.com/Pegmatis-Inc/open62541.git`
- `upstream`: `https://github.com/open62541/open62541.git`

## Synchronize with upstream

Run these commands from the repository directory whenever you want to bring the Pegmatis repository up to date:

```powershell
git fetch upstream
git switch master
git merge upstream/master
git push origin master
```

If the merge reports conflicts, resolve the conflicts, stage the resolved files, and complete the merge before pushing:

```powershell
git add <resolved-files>
git commit
git push origin master
```

Check the configured remotes with:

```powershell
git remote -v
```

New commits made on the `master` branch are pushed to Pegmatis with:

```powershell
git push origin master
```
