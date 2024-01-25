Test Repository for possible Hugo issues
========================================

# Problems with `fileExists` and `readDir`

To reproduce just run:
```
hugo
mkdir -p themes/PaperMod/layouts/partials/shortcodes/metadata
hugo
```

## Possible cause
`fileExists` and `os.Stat` seem to work on the underlaying union file system while `readDir` doesn't.
