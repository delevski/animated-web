# Animated Authentication UI

A polished, responsive sign-in and registration experience built as a single self-contained HTML file. The project focuses on interaction design: animated tab changes, inline validation, password visibility controls, strength feedback, social-login buttons, and a refined glass-style interface.

## Highlights

- Sign-in and account-creation views in one animated card
- Responsive layout for desktop and mobile screens
- Password visibility and strength indicators
- Client-side form validation and feedback states
- Accessible labels, keyboard-friendly controls, and reduced-motion support
- No framework, build step, or external UI library

## Stack

- Semantic HTML
- Modern CSS, including custom properties, gradients, and keyframe animation
- Vanilla JavaScript

## Run locally

Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/delevski/animated-web.git
cd animated-web
```

For a local web server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Integration note

This repository is a front-end UI prototype. The forms currently demonstrate validation and success states in the browser; connect `handleLogin` and `handleRegister` in `index.html` to your own authentication API for production use.
