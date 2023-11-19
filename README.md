# Install
- [lefthook](https://github.com/evilmartians/lefthook/)  
- [commitlint-rs](https://keisukeyamashita.github.io/commitlint-rs/)


## Run
Run `lefthook install` in the workspace  
Test commit
```
$ git commit -a -m "test"

** git commit -a -m "test"
╭───────────────────╮
│ 🥊 lefthook v1.5.2  hook: pre-commit │
╰───────────────────╯
│  format (skip) no files for inspection
│  linter (skip) no files for inspection

  ──────────────────
summary: (skip) empty
╭───────────────────╮
│ 🥊 lefthook v1.5.2  hook: commit-msg │
╰───────────────────╯
┃  commitlint ❯

scope  is not allowed. Only ["config", "app"] are allowed
type  is not allowed. Only ["feat", "fix"] are allowed


  ──────────────────
summary: (done in 0.01 seconds)
🥊  commitlint**
```

