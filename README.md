# bloop

An open, browser-based arcade and game creation platform powered by a custom programming language. **bloop** lets players jump straight into games in the browser with zero downloads or installations, while giving creators—including beginners and AI-assisted builders—an easy way to write code, publish playable games, and share them with the community.

---

## Overview

Traditional game distribution often forces creators to package builds, handle OS compatibility, and ask players to download and run unfamiliar executables—creating friction and security concerns. **bloop** removes that barrier by turning code written in the platform's custom language directly into live, playable browser games.

* **Instant Play:** Browse, search, and play games right inside the browser.
* **Create & Share:** Write code in the custom language (manually or generated with AI), publish games quickly, and optionally share source code for community learning.
* **Community Feedback:** Rate games with likes or dislikes and discuss creations through comments.

---

## Pages & Navigation

* **Home / Game Library (`/`):** Main arcade hub showcasing game cards, search/filtering, and quick access to playable titles.
* **Game Page (`/game/[id]`):** Runs the selected game directly in the browser alongside its details, like/dislike controls, and comments.
* **Create / Publish Game (`/create`):** Editor and publishing flow for creating or uploading games using the custom language.
* **Player Profile (`/player/[id]`):** Displays player info, published games, likes, name, and description.
* **Authentication (`/login`, `/register`):** Sign-in and account registration forms with required fields and validation.
* **Account Settings (`/settings`):** Update profile details, bio/description, and account credentials.

---

## Roles & Permissions

There is no dedicated admin-only page; instead, **Admin** accounts inherit all standard user capabilities and gain extra moderation and management controls across the site.

| Role | Capabilities & Restrictions |
| --- | --- |
| **Guest** | Browse public pages, open and play games, and give a **like** or **dislike**. Cannot post comments or create/publish games. Can access login and registration. |
| **User** | Full access to everything a guest can do, plus **create/publish games**, manage their own games, **post comments**, and update their profile details. |
| **Admin** | Inherits all **User** permissions and additionally has elevated controls to **delete games**, **ban users**, and view platform/user data and stats. |

---

## Core Features

* **Authentication & Account Management:** Register new accounts, log in, log out, and edit user profile details (including name and description).
* **Instant Browser Gameplay:** Launch and play games directly on the web without local installs.
* **Game Creation & Publishing:** Author or paste custom-language code and publish playable builds to the library.
* **Ratings & Comments:** Like or dislike games (guests, users, admins) and post comments (users and admins).
* **Moderation & Oversight (Admin):** Remove games, ban/restrict users, and inspect site data across slices/statistics.

---

If you want to customize any specific routes, tech stack details, or registration fields in this README, let me know which sections to tweak!
