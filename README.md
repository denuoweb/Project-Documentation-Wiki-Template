# Project Documentation Wiki Template

This repository is a **template** for course wiki documentation.

- **Start here (Wiki):** https://github.com/denuoweb/Project-Documentation-Wiki-Template/wiki
- The Wiki is the single source of truth for project documentation.
- This repo exists to make the wiki content easy to clone and reuse.

## Clone (including wiki as a submodule)
```bash
git clone --recurse-submodules https://github.com/denuoweb/Project-Documentation-Wiki-Template.git
```

## After editing wiki pages: update the submodule pointer

The GitHub Wiki is a separate git repository. The `wiki/` directory in this repo is a **submodule** pointing to a specific wiki commit. If you edit the wiki (in the GitHub UI or by pushing to the wiki repo), the main repo’s submodule pointer will **not** automatically update.

To bump the submodule pointer in the main repo:

```bash
cd Project-Documentation-Wiki-Template/wiki
git pull

cd ..
git add wiki
git commit -m "Update wiki submodule pointer"
git push
```
