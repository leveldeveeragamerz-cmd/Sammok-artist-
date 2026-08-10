---
name: Static Vite metadata
description: Build behavior for canonical and social metadata URLs in static artifact HTML shells.
---

When a Vite artifact's production domain is not known, keep canonical and social image URLs document-relative rather than fabricating a deployment URL. In this workspace, bare root or directory-relative metadata URLs can be interpreted as file assets during Vite HTML processing, while concrete paths such as `./index.html` and `./images/...` build successfully.

**Why:** The static artifact build processes HTML URL attributes and can fail with an EISDIR error when a metadata URL resolves to a directory.

**How to apply:** Before publishing, replace relative canonical, Open Graph URL, and image URLs with absolute production URLs obtained from deployment information.