ref. https://medium.com/@Keithweaver_/only-run-github-actions-on-specific-branches-694782fcc07

run on git push on branch :branch-x
```bash
: this-folder
f='.github/workflows/onpush-branchx.yml'
mkdir -p ${f%/*} && touch $f

```
