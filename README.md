# Project Documentation Wiki Template

This repository is a **template** for course wiki documentation.

- **Start here (Wiki):** https://github.com/denuoweb/Project-Documentation-Wiki-Template/wiki
- The Wiki is the single source of truth for project documentation.
- This repo exists to make the wiki content easy to clone and reuse.
- If the destination wiki does not exist yet, create it by adding a single page in the GitHub UI first.

## Seed a new project's wiki (keeps history)
Use this to preserve the template wiki history and make it your project's wiki history.

```bash
git clone https://github.com/denuoweb/Project-Documentation-Wiki-Template.wiki.git wiki
cd wiki
git remote set-url origin https://github.com/<org>/<new-project>.wiki.git
git push -u origin <default-branch>
```

