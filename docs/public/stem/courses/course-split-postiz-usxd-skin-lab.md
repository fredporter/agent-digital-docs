---
layout: page
title: "Course split — Postiz clone + USXD skin lab (locked)"
permalink: /docs/public/stem/courses/course-split-postiz-usxd-skin-lab/
---

**Status:** **Locked** — two **self-contained** courses: **Course 1** runs **Postiz** with **no theming**; **Course 2** is a **wireframe CSS + uCode** lab on a **minimal static** app (see **[Course 2 — locked lab](course-2-skin-lab-wireframe-locked/)** — **no USXD interchange complexity** in the first pass).

**Canonical ladder:** [uDosDev — Value ladder v1](https://github.com/fredporter/uDosDev/blob/main/docs/specs/v4/UDOS_VALUE_LADDER_AND_PUBLISHING_PREMIUM_v1.md). **Family USXD lab:** [UniversalSurfaceXD](https://github.com/fredporter/UniversalSurfaceXD) (advanced surfaces — **not** required for Course 2).

---

## The split

| Course | Focus | Outcome | Theming |
| --- | --- | --- | --- |
| **1** — Run your own social media manager | Clone, configure, run **Postiz** locally | **Postiz** at `http://localhost:3000` | **None** — original Postiz UI |
| **2** — Skin any web app (wireframe) | **Open-box CSS** + optional **uCode** automation | Same app, **uDos wireframe** look | **[usxd-wireframe.css](../../../../assets/stem/usxd-wireframe.css)** overlay |

---

## Course 1 — Postiz clone (no skin)

**Upstream:** [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app)  
**Student outcome:** Postiz running at `http://localhost:3000`.

### What the student does

- Clone to `~/Code/Postiz` (or agreed path).
- Complete an **open-box config sheet** (domain, email, one social platform).
- Run **uCode parser** (or scripted helper) to generate `.env` / `docker-compose` inputs as per course materials.
- `docker-compose up` (or documented equivalent).
- Connect **one** social account.
- Schedule a **test post**.

### What the student does *not* do

- No skin application.
- No UI theming.
- No Course 2 lab in the same sitting.

### Message to students

Postiz **looks like Postiz**. That is intentional. **Course 2** uses a **small** HTML/CSS/JS app so changes are visible immediately.

---

## Course 2 — Pointer to locked lab

**Authoritative doc:** **[Course 2 — Skin lab (wireframe CSS + uCode) — locked](course-2-skin-lab-wireframe-locked/)**

That page defines:

- **Targets** (Sunny Polls + fallbacks + **embedded** [lab-polls](https://github.com/fredporter/AppStoreDocs/tree/main/assets/stem/lab-polls) files).
- **Modules** (clone → inspect CSS → link skin → customise → uCode exercise → share).
- **Deferred topics:** USXD surface spec, full LENS/SKIN theory, uGrid/UVIL (advanced courses).

**Optional later reading:** LENS = behaviour, SKIN = presentation — useful vocabulary **after** the first win; not a gate for Course 2.

---

## Cursor one-liner

**Course 1:** Clone Postiz, open-box config, run locally, **no** skin. **Course 2:** Follow **[locked Course 2 page](course-2-skin-lab-wireframe-locked/)** — tiny static app, **[usxd-wireframe.css](../../../../assets/stem/usxd-wireframe.css)**, uCode exercises per **UCODE v4**; **no** USXD document format required for the student path.

---

## Changelog

| Version | Notes |
| --- | --- |
| 1.1.0 | Course 2 defers to **course-2-skin-lab-wireframe-locked**; split overview only |
| 1.0.0 | Initial split + targets |
