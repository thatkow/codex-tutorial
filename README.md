# codex-tutorial

This repository hosts a static Cytoscape.js visualisation of the NUCC skill progression graph. The published assets now live in the `docs/` directory so they can be served by GitHub Pages or any other static host.

## Viewing locally

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/docs/> in your browser.

## Publishing a public link with GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, enable **Pages** and choose `main` as the branch with `/docs` as the folder.
3. After Pages finishes building, your graph will be available at:
   
   ```
   https://<your-github-username>.github.io/<your-repo-name>/
   ```

   GitHub Pages automatically serves the contents of `docs/`, so `index.html` will load `definition.csv` from the same public URL.

Replace `<your-github-username>` and `<your-repo-name>` with your actual values to get the final public link you can share.
