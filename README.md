# ⚙️ GitHub Action Repo – Triggers Webhook Events

This repository is used to simulate GitHub events such as:

- ✅ Push
- ✅ Pull Request
- ✅ Merge

These actions trigger a webhook that sends data to the Flask-based backend app in [`webhook-repo`](https://github.com/treesa64/webhook-repo).

---

 🎯 Purpose

This repo is part of a developer assessment project. The goal is to:

> Send GitHub webhook events on push, pull request, and merge actions to a registered endpoint (`/webhook`) in another repo, where the events are processed and stored in MongoDB, then displayed in a UI.

---

 🧪 How to Test

You can simulate each event like this:

 1. ✅ Push Event

- Add or update a file (e.g., `push-demo.txt`)
- Commit directly to the `main` branch

 2. 🔁 Pull Request Event

- Create a new branch (e.g., `feature-ui`)
- Add a file like `pull-demo.txt`
- Submit a Pull Request back to `main`

 3. ✅ Merge Event

- After PR is opened, click Merge pull request
- This triggers a merge webhook event

---
 🔗 Linked Project

- Webhook Listener App: [webhook-repo](https://github.com/treesa64/webhook-repo)
- Demo Hosted With: Ngrok + Flask

---

🙋‍♀️ Developed by

Treesa
B.Tech Computer Science Graduate  
Built as part of a GitHub Webhook + MongoDB + Flask assessment project.

---

