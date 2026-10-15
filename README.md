# Studyflow

A free, static exam study planner. Create a realistic study schedule around your exam date, available days, subjects, daily study time, and breaks. No account, backend, build tools, or external dependencies required.

## Features

- Build a schedule from an exam date, daily study hours, and preferred study days.
- Choose subjects and prioritize the ones that need more attention.
- Set a daily start time, session length, and break duration.
- Save multiple plans in the browser, switch between them, and delete individual plans.
- Download the selected plan as a formatted PDF or print it.
- Responsive layout for desktop and mobile.

## Run locally

The site is plain HTML, CSS, and JavaScript. You can open `index.html` directly in a browser, or start a local static server from the project folder:

```sh
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Publish with GitHub Pages

1. Create a GitHub repository and upload `index.html` and `README.md` to the repository root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then save.
5. After GitHub Pages finishes deploying, visit the URL shown in the Pages settings. It will usually look like `https://<your-username>.github.io/<repository-name>/`.

No build command or GitHub Actions workflow is needed. GitHub Pages serves the static files directly.

## Privacy and storage

Studyflow has no server and does not send plans anywhere. Saved plans are stored in `localStorage` in the current browser on the current device. They are not synced or backed up; clearing that browser's site data removes them. Use the PDF download if you want a portable copy.

## Repository details

- **Suggested description:** A free, private exam study planner that runs entirely in your browser.
- **Suggested topics:** `study-planner`, `exam-planner`, `static-site`, `html`, `javascript`, `github-pages`
- **Dependencies:** None

## License

No license is included. Unless you add one, others do not receive permission to reuse, modify, or distribute this code beyond rights granted by applicable law.
