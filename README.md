# Login & Signup Form UI

A simple, polished HTML/CSS interface for login and account creation screens.

## Features

- Glass-style card layout with gradient background.
- Separate **Login** and **Create Account** pages with tab-style navigation.
- Structured form fields for authentication and signup details.
- Mobile-friendly layout adjustments for smaller screens.

## Preview / Run Locally

You can run this project without any build tools:

1. Clone or download the repository.
2. Open `/home/runner/work/login-form/login-form/index.html` in your browser.
3. Use the tabs to switch between login and signup pages.

Optional: serve it with a simple static server.

```bash
cd /home/runner/work/login-form/login-form
python3 -m http.server 8000
```

Then open `http://localhost:8000/index.html`.

## Project Structure

```text
login-form/
├── index.html      # Login page
├── signup.html     # Signup page
├── style.css       # Shared styling for both pages
└── images/
    └── image.png   # Logo used in the form header
```

## Customization

- Update text labels/headings directly in `index.html` and `signup.html`.
- Adjust colors and glass effect values in `:root` and related rules in `style.css`.
- Replace `images/image.png` with your own logo while keeping the same path.
