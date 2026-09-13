# Ustadan Landing Page

A responsive Turkish landing page introducing Ustadan, a home-services app concept.
It presents service categories, the intended user journey and a coming-soon section.

[View the deployed page](https://project-gveqd.vercel.app/)

## Scope

- Hero section, service categories and explanatory cards.
- Responsive layouts built with CSS Grid, Flexbox and a viewport breakpoint.
- In-page navigation to the explanation and coming-soon sections.

The email form is a visual placeholder: it has no configured submission endpoint,
JavaScript handler or email-delivery integration. This repository contains the
landing page; app functionality and a backend are not included.

## Run locally

Clone the repository and open `index.html` in a browser. No dependencies or build step are required.

For a local HTTP preview, if Python 3 is installed:

```sh
git clone https://github.com/kadir2848/ustadan-landing.git
cd ustadan-landing
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000>. Stop the server with `Ctrl+C`.

## Files and technologies

| File | Purpose |
| --- | --- |
| `index.html` | HTML content and embedded CSS, including responsive styles. |
| `hero.jpg` | Hero background image. |

Built with HTML and CSS and deployed on Vercel. Keep both files together when serving the site.
