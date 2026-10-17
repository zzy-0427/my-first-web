# my-first-web

Simple static site with multiple example pages.

Files:
- index.html
- my-site.html
- router-app.html
- router-app-2.html
- tofo.html
- vue-todo.html
- vue-todo-2.html
- vue-todo-3.html
- vue-todo-4.html

Run locally (choose one):

1) Python 3 (minimal, no install if Python present):
   Open PowerShell in the project folder and run:
   ```powershell
   python -m http.server 8000
   ```
   Then open: http://localhost:8000/index.html

2) Node (if Node.js installed):
   ```powershell
   npx serve -p 8000 .
   ```

3) VS Code: Install Live Server extension and click "Go Live".

Notes:
- These are static HTML files; no build step required.
- To preview a different page, replace `index.html` in the URL with the filename.

If you want, I can:
- Open and explain a specific file
- Start a local server here and show the contents
- Convert a page into a Vue single-file component
