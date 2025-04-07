---
title: "Capstone Mid-term: GitHub API Integration in a Chrome Extension"
---

## 🚀 About the Project

As part of our Capstone project, my team is building **CommitPro** — a Chrome Extension that allows users to add comments directly to GitHub issues using the GitHub API.

## 👨‍💻 My Role

I was responsible for the **backend and API integration**. My goal was to connect our extension to GitHub so users could post comments without leaving the browser.

## ⚙️ How I Did It

- **Explored GitHub’s REST API**, especially the `/repos/:owner/:repo/issues/:number/comments` endpoint.
- Implemented a `postComment()` function using `fetch()` in JavaScript.
- Handled **authentication** with a user-supplied GitHub token and stored it using `chrome.storage`.
- Integrated this with our popup UI so users could submit a comment and instantly see it posted to GitHub.

## 🧠 Lessons Learned

- How to work with APIs and Chrome extension permissions.
- Debugging CORS and token issues.
- Modular design between frontend and backend code in a browser extension.

## 🎯 Why It Matters

Understanding how browser extensions can interact with platforms like GitHub opens the door to creating productivity tools that feel native. I hope this inspires others to explore GitHub's API and build creative developer tools!

---

Thanks for reading!
