# 401 Labs Website

Official website of 401 Labs!

## About 401 Labs

At 401 Labs, we build ad-hoc products in our weekends and free time—focused entirely on solving real, everyday problems.

Each product is built fast, launched quickly, and kept live for a defined period (usually around a year).

Anyone interested can acquire or take over the product, or choose to maintain and evolve it further.

We believe in simple ideas, rapid execution, and making useful tools that create real value for real people.

## Getting Started

This is a static website built with HTML and CSS. No build process required!

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/401labs/401labs-website.git
   cd 401labs-website
   ```

2. Open `index.html` in your browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # Or simply double-click the file in your file explorer
   ```

### Using a Local Server

For a better development experience, you can use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Project Structure

```
401labs-website/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── README.md       # This file
└── LICENSE         # MIT License
```

## Contributing

We welcome contributions! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
