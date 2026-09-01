# Loop — Login Page UI

A clean, modern login interface built with plain HTML and CSS.
This is my third task for my remote internship at **Synent Technologies**.

## Live Demo

_Add your Vercel URL here once deployed, e.g._
`https://loop-login.vercel.app`

## About

A login screen for **Loop**, the same fictional habit-tracker app used in
Task 2's landing page — built to match its visual identity (fonts, colors,
brand mark).

- **Email field** — with icon and validation via `type="email"`
- **Password field** — with a show/hide visibility toggle
- **Login button** — primary call-to-action
- **Forgot password?** — link above the button
- Bonus: social login buttons (Google/GitHub) and a sign-up prompt for a
  more complete, realistic feel

## Tech Stack

- HTML5
- CSS3 (Flexbox, custom properties)
- A few lines of vanilla JavaScript for the password show/hide toggle
- [Google Fonts](https://fonts.google.com/) — Space Grotesk & Inter

No build tools or frameworks — it's a static page that runs directly in
the browser.

## Responsive Behavior

The card and background decoration scale down at 460px and below so the
layout stays centered and readable on small phones.

## Project Structure

```
.
├── index.html      # Page markup, embedded styles, and toggle script
├── favicon.svg      # Site favicon (matches the Loop brand mark)
└── README.md         # This file
```

## Running Locally

Clone the repo and open `index.html` directly in a browser:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
open index.html   # macOS
# or just double-click index.html on Windows/Linux
```

No server or build step is required.

## Deployment

This project is deployed on [Vercel](https://vercel.com) as a static site,
connected to this GitHub repository. Every push to `main` triggers a new
deployment automatically.

## Author

**Solomon Ashagre**
MERN Stack Developer & Tech Educator · Addis Ababa, Ethiopia

- Email: solash5156@gmail.com
- GitHub: [@Sol-Ethio-Coder](https://github.com/Sol-Ethio-Coder)
- LinkedIn: [sol-ethio-coder](https://www.linkedin.com/in/sol-ethio-coder/)
