---
layout: page
title: "Course 2 — Skin lab (wireframe CSS + uCode) — locked"
permalink: /docs/public/stem/courses/course-2-skin-lab-wireframe-locked/
---

**Status:** **Locked** — **Course 2** teaching track: **open-box CSS** + **uCode-style automation** on a **tiny** static app. **No** USXD JSON/surface spec, **no** LENS/SKIN theory block, **no** uGrid/UVIL in this course (deferred to advanced tracks).

**Parent brief:** [Course split — Postiz + skin lab](course-split-postiz-usxd-skin-lab/). **Canonical uCode:** [UCODE_v4](https://github.com/fredporter/uDosDev/blob/main/docs/specs/v4/UCODE_v4.md). **Wireframe asset:** [usxd-wireframe.css](../../../../assets/stem/usxd-wireframe.css).

---

## Part 1 — Target: Sunny Polls (or fallback)

| Priority | Source | Notes |
| --- | --- | --- |
| **Primary** | [github.com/sunny/polls](https://github.com/sunny/polls) | Verify repo is reachable before assigning |
| **Fallback 1** | [github.com/anders94/blockchain-demo](https://github.com/anders94/blockchain-demo) | Vanilla, single-page |
| **Fallback 2** | [mdn/webextensions-examples](https://github.com/mdn/webextensions-examples) (e.g. `browser-action`) | More setup than a single page |
| **Fallback 3** | Embedded lab (this site) | No GitHub required |

**If the primary repo is unavailable:** copy the **embedded polls lab** into `~/Code/polls/` (or any folder) and open `index.html` locally.

**Embedded files (download or copy):**

- [index.html](../../../../assets/stem/lab-polls/index.html)
- [style.css](../../../../assets/stem/lab-polls/style.css) (original look **before** skin)

---

## Part 2 — Course structure (no USXD complexity)

**Course name:** **Skin any web app with uDos wireframe**  
**Outcome:** Student changes **look and feel** with **open-box CSS** and can **automate** copy/link steps with **uCode** (real syntax per **UCODE v4**).

| Module | Title | Outcome |
| --- | --- | --- |
| 1 | Get the polls app | Clone **or** create `index.html` + `style.css`; see original look in browser |
| 2 | Look under the hood | Read `style.css`; change **one** colour and refresh |
| 3 | Open-box CSS | Add [usxd-wireframe.css](../../../../assets/stem/usxd-wireframe.css) **after** `style.css` |
| 4 | Customise the skin | Edit `:root` variables; optional `body.udos-teletext`; change accent |
| 5 | uCode command | Script copies skin file and ensures `<link>` (see §5 — **pseudocode** vs real uCode) |
| 6 | Share | Export/share `.css`; optional “.usxd” naming = **packaged skin file** (convention only in this course) |

---

## Part 3 — Linking the skin

```html
<link rel="stylesheet" href="style.css" />
<link rel="stylesheet" href="usxd-wireframe.css" />
```

Optional teletext grid: add **`class="udos-teletext"`** to `<body>` (see stylesheet), or uncomment grid rules **inside** `usxd-wireframe.css`.

---

## Part 4 — Open-box template

The **authoritative** wireframe file is **[usxd-wireframe.css](../../../../assets/stem/usxd-wireframe.css)** (variables, overrides, optional commented blocks). Students edit **variables first**, then optional effects.

---

## Part 5 — uCode: apply / remove skin (illustrative)

**Important:** Snippets below are **course pseudocode**. Implementations must follow **[UCODE v4](https://github.com/fredporter/uDosDev/blob/main/docs/specs/v4/UCODE_v4.md)** and your installed **`udos ucode`** CLI.

**Example stubs (non-normative):**

- [apply-skin.ucode.example](../../../../assets/stem/lab-polls/apply-skin.ucode.example)
- [remove-skin.ucode.example](../../../../assets/stem/lab-polls/remove-skin.ucode.example)

**Pedagogical goal:** copy `usxd-wireframe.css` into the project folder; ensure **one** `<link>` in `<head>`; reverse steps to remove.

---

## Part 6 — Takeaways

### What students learn

- CSS drives **appearance**; behaviour (JS) can stay untouched.
- **Open-box** blocks and **variables** make skins easy to read and swap.
- One **shared** `.css` file can theme many small apps.
- **uCode** (when implemented to spec) can automate file + HTML edits.

### What is deferred (not this course)

- USXD **surface document** format and validators.
- Full **LENS/SKIN** vocabulary (optional advanced reading only).
- **uGrid** coordinates, **UVIL**, teletext **block** specs.

### Why keep it simple

Students get a **visible win** (theme flips) before interchange **complexity**.

---

## Cursor one-liner

**Course 2 (locked):** Target **Sunny Polls** if available; else **blockchain-demo**, an MDN example, or **embedded** [lab-polls](https://github.com/fredporter/AppStoreDocs/tree/main/assets/stem/lab-polls). Student uses **open-box** [usxd-wireframe.css](../../../../assets/stem/usxd-wireframe.css), linked **after** `style.css`, then customises variables; **uCode** steps are **automation exercises** using real **[UCODE v4](https://github.com/fredporter/uDosDev/blob/main/docs/specs/v4/UCODE_v4.md)** — examples ship as `.ucode.example` only. **No** USXD spec, **no** mandatory LENS/SKIN lecture, **no** uGrid in scope.

---

## Changelog

| Version | Notes |
| --- | --- |
| 1.0.0 | Initial lock — targets, fallback lab, open-box CSS, uCode as illustrative + UCODE_v4 pointer |
