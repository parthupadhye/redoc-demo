# Redocly-Demo
This repository represents the simplest way to build a Redoc site from a YAML file. To create a production ready site, you need to make additional changes which have been skipped in this initial release.

## Prequisites
- GitHub account
- VSCode or a YAML editor.

## Creating your Redoc site
1. Download this repository, extract and copy its contents to your working directory.
2. Open your directory/folder in VSCode. The File Explorer should display the four files from the repo.
3. Rename **booksapi.yaml** to your YAML name.
4. Open **index.html**. In the body tag, in the redoc tag, for spec-url attribute, replace value from **booksapi.yaml** to the your filename.
5. Open and edit your YAML file.
6. In the terminal or comman prompt, run the following.
```
openapi preview-docs openapi.yaml
```
7. Save to a GitHub repository (optional)
8. Preview server running at http://127.0.0.1:8080 
