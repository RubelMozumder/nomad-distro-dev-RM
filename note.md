# General Notes

## Git
### Remove the submodule from git
```
# Deinitiate submodule from git config
git submodule deinit -f -- <submodule_path>
# Remove submodule metadata from .gitmodules file
# If it does not work remove it manually
git rm --cached <submodule_path>
# Remove submodule from .git modules dir
rm -rf .git/modules/<submodule_path>
# Remnove submodule from working dir
rm -rf <submodule_path>
# commit changes
git commit -m "Removed submodule <submodule_path>"
git push
```
## Some UV comments:
1. Check which python environment uv package manager is using
`$ uv venv`

## Branch list with branch of submosules
1.  SPMapp (nomad->jumpToReference, pynxtools->master, pynxtools-spm-->SPMapp)
2. 

