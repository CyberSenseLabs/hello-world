# Hello World

A simple Hello World web app built from a Figma design. Features a centered title, subtitle, and a call-to-action button.

## Live App

- **Production**: https://hello-world-rho-murex-53.vercel.app
- **Figma Design**: https://www.figma.com/design/b5RFbkfyOsw3LOIElWCw8Q

## Getting Started

No build step required. Open `index.html` directly in a browser:

```bash
open index.html
```

Or serve it locally:

```bash
npx serve .
```

## Project Structure

```
hello-world/
├── index.html   # App markup
├── style.css    # Styles
├── main.js      # Button interaction
└── .github/
    └── workflows/
        └── deploy.yml  # Auto-deploy to Vercel
```

## Deployment

This project deploys automatically via GitHub Actions:

- **Pull request** → preview deployment on a unique Vercel URL
- **Merge to `main`** → production deployment

To deploy manually:

```bash
vercel        # preview
vercel --prod # production
```

## License

MIT License

Copyright (c) 2026 Marcel Lammerse

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
