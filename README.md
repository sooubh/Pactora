# Pactora

Pactora is a private, offline-first app that helps you track commitments, money owed, and items lent or borrowed. It keeps your money, promises, and shared commitments organized in one beautiful place.

## Project Overview

Pactora acts as your personal accountability engine. It solves the awkward problem of forgetting promises or losing track of small loans and borrowed items by providing a clear, simple, and locally-stored record.

## Features

- **Promise Tracking:** Never forget a commitment again. Log promises you make or those made to you.
- **Expense Tracking:** Log shared expenses, IOUs, and split bills. Keep a clear record of who owes what.
- **Shared Records:** Ensure everyone is on the same page with straightforward logs.
- **Activity Timeline:** View a chronological history of all your activities and settled debts.
- **Secure Data:** Privacy-first design with local storage and offline-first capabilities.

## Screenshots

<div align="center">
  <img src="assets/images/home.png" width="200" alt="Home Page" />
  <img src="assets/images/promise.png" width="200" alt="Promise Page" />
  <img src="assets/images/finance.png" width="200" alt="Finance Page" />
  <img src="assets/images/timeline.png" width="200" alt="Timeline" />
</div>

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Styling:** Tailwind CSS (via CDN)
- **Typography:** Inter (Google Fonts)
- **Deployment/Hosting:** Static file hosting ready (GitHub Pages, Netlify, Vercel, etc.)

## Installation

Getting the website running locally is extremely simple.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sooubh/pactora.git
   cd pactora
   ```

2. **Run the site:**
   Since it's a static site, you can just open `index.html` in your browser.
   Alternatively, use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   ```
   Then navigate to `http://localhost:8000`.

## Project Structure

```text
pactora/
├── assets/
│   └── images/          # Application screenshots and logo files
├── index.html           # Main landing page
├── how-to-use.html      # User guide page
├── contact.html         # Contact/Support page
├── privacy.html         # Privacy Policy page
├── terms.html           # Terms of Use page
├── script.js            # Custom JavaScript functionality
├── style.css            # Additional custom styles
├── README.md            # Project documentation
├── HOW_TO_USE.md        # Detailed text guide
├── PRIVACY_POLICY.md    # Privacy Policy text
└── TERMS_OF_USE.md      # Terms of Use text
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open-source and available for usage. Please review the repository for any specific licensing files or contact the author.

## Author

GitHub: [@sooubh](https://github.com/sooubh)
