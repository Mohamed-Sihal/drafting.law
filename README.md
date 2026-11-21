# DraftDesk

DraftDesk is a static front-end prototype for an Indian legal drafting workspace, with Family and DRT matter flows.

## Run locally

Open `index.html` in a modern browser. No package install or build step is required.

## Publish with GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`. To publish:

1. Create a GitHub repository and push these files to its `main` branch.
2. In the repository, open **Settings → Pages** and set the publishing source to **GitHub Actions**.
3. Push to `main` (or run the **Deploy to GitHub Pages** workflow manually from the Actions tab).
4. After the workflow succeeds, open the Pages URL shown in the workflow deployment environment.

For a new repository, from this folder:

```powershell
git init -b main
git add index.html README.md .gitignore .github/workflows/deploy.yml
git commit -m "Add DraftDesk prototype"
git remote add origin https://github.com/<OWNER>/<REPOSITORY>.git
git push -u origin main
```

Replace `<OWNER>` and `<REPOSITORY>` with your repository details. Do not include real client information in this prototype.

## Prototype limitations

- The interface runs entirely in the browser and has no backend, AI model, database, or citation-retrieval system.
- Draft generation creates outlines only; it does not produce legal advice or verified legal citations.
- The source panel describes the intended official-source policy; it does not verify sources.
- Do not enter real client details. Add authentication, secure storage, access controls, and source verification before using this for client work.
