# CR7 — Made of More

A responsive Cristiano Ronaldo fan landing page built with Python’s standard library. The project combines a lightweight Python HTTP server with a hand-crafted HTML, CSS, and JavaScript experience.

## Preview

The page includes:

- Editorial-style hero section with CR7-inspired branding
- Responsive layout for desktop, tablet, and mobile screens
- Scroll progress indicator and sticky glass navigation
- Active section highlighting while scrolling
- Hero parallax movement and reveal animations
- Animated career statistics
- Interactive career timeline cards
- Reduced-motion support for accessibility

## Run locally

This project does not require Flask or any third-party Python package.

```bash
python3 main.py
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## Project structure

```text
.
├── main.py       # Python server and embedded landing page
├── README.md     # Project documentation
└── .gitignore    # Local Python and editor files to ignore
```

## Notes

The page uses Google Fonts and Unsplash-hosted image URLs, so an internet connection is needed for the full visual treatment. The server itself runs locally using Python’s built-in `http.server` module.

## License

This is a fan-made educational project. It is not affiliated with or endorsed by Cristiano Ronaldo or CR7.
