# Engineering & Maintenance – Ongoing Works dashboard (GitHub Pages)

## One-time setup
1. Create a GitHub repository (e.g. `works`). On a free account the site is public.
2. Upload everything from this folder (drag the files into **Add file → Upload files**): `index.html`, `data.js`, `build_works.py`, `Departmental_Ongoing_Works_Professional.xlsx`, `README.md` and the `.github` folder.
3. Check that the file `.github/workflows/update-works.yml` exists in the repository. If it is missing or sits in the main folder, click **Add file → Create new file**, type the name `.github/workflows/update-works.yml`, paste the text from `update-works.yml.txt`, and commit.
4. **Settings → Pages**: Deploy from a branch, branch `main`, folder `/ (root)`, Save. Your link appears after about a minute.

## Update the status
1. Edit the tracker in Excel and save it (keep the file name and the sheet layout).
2. In the repository: **Add file → Upload files**, upload `Departmental_Ongoing_Works_Professional.xlsx`, Commit changes.
3. Wait 2–3 minutes. In **Actions**, a green tick on "Update works data" means it worked. Refresh the dashboard (Ctrl+F5).

## Notes
- The dashboard has no password. On a public repository anyone can open the site and download the Excel file.
- It shows the three departments Fiber Bleaching, R-Cot Line and Spunlace Project. A new department sheet needs a small change to `index.html`.
