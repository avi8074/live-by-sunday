# Live by Sunday

> Learn AI. Build real software. Go live by Sunday.

The landing page for **Live by Sunday** — free, weekly, guided AI build sessions for students in and around Vizag (Visakhapatnam), India.

## What it is

Every Sunday at 7 PM IST, we go live on Zoom: one community-submitted problem, built together step by step, **deployed by 9 PM**. A complete beginner ends the night with a working app live on the internet — and their name on the URL.

- **Zoom is the classroom. WhatsApp is the group.** The invite link drops in the group before every session.
- **One problem a week.** Submitted by the community through a Google Form pinned in the group — no teams, no competition, everyone builds the same thing, together.
- **The Builder Passport.** Three deploys across three Sundays earns an invite to the 4th-Sunday Deployers' Café. Consistency over brilliance.
- **Free forever.** ₹0. No catch — showing up is the only fee.

## This repo

A single-file, zero-dependency landing page (`index.html`):

- Manrope + JetBrains Mono, custom CSS (no frameworks)
- Vanilla JS only — scroll reveals via IntersectionObserver, a live countdown to the next Sunday 7 PM IST (computes the next session forever — year boundaries and leap years handled), sticky mobile CTA
- Accessible: keyboard focus states, skip link, `prefers-reduced-motion` support, WCAG-AA contrast

Hosted on GitHub Pages.

## Live site

**https://avi8074.github.io/live-by-sunday/**

## Built by

**K. Avinash** — builder, guide, Vizag.
*"I walk you through every step, live."*
