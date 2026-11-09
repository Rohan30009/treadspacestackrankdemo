# Treadspace StackRank V2 — Team Demo

This repository contains a static browser-based prototype of the Treadspace Candidates and StackRank experience.

## Publish with GitHub Pages

1. Create a GitHub repository (e.g., `treadspace-stackrank-demo`).
2. Upload `index.html`, `.nojekyll`, and `README.md` to the **root** of the repository's `main` branch.
3. Open **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, choose **main** and **/(root)**, then save.
5. Use the **Visit site** link in Settings → Pages after deployment. Typical URL: `https://YOUR-USERNAME.github.io/treadspace-stackrank-demo/`.

## Demo walkthrough

- Start on the original-style **Candidates** screen.
- Click **StackRank** beside Filter and Sort.
- Explore **Overall Ranking**, **Evaluation Completed**, **By Evaluation**, and **By Competency**.
- Try sorting, filtering, comparing candidates and inspecting candidate detail.

## Important limitations

- This is a demonstration with sample candidate records, not a live ATS.
- No backend, login, shared accounts, API integration, or persistent server database.
- Some interactions persist to the visitor's own browser using `localStorage`; changes are not shared across team members.
- Do not publish real applicant details, private company information or secrets.
- GitHub Pages website visibility is normally **public**, including when the repository is private unless your enterprise supports private Pages access.

## Updating

Replace `index.html` with the next reviewed prototype version and commit the change. GitHub Pages will redeploy the updated page.
