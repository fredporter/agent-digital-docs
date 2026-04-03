# Custom Domain Setup

## Goal

Connect:

`docs.agentdigital.co`

to your GitHub Pages site.

## In GitHub

1. Go to repository **Settings**
2. Open **Pages**
3. In **Custom domain**, enter:
   `docs.agentdigital.co`
4. Save
5. Enable HTTPS once GitHub makes it available

## In Your DNS Provider

Create a CNAME record:

- **Host / Name:** `docs`
- **Value / Target:** `fredporter.github.io`

## Result

Your docs site will load at:

`https://docs.agentdigital.co`
