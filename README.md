# Personal Website with Hugo and Massively Theme

This is a personal website built with [Hugo](https://gohugo.io/) static site generator using the [Massively](https://html5up.net/massively) theme from HTML5 UP.

## Getting Started

### Prerequisites

- [Hugo](https://gohugo.io/installation/) installed on your system

### Development

To start the development server:

```bash
hugo server
```

The site will be available at `http://localhost:1313`

### Building

To build the site for production:

```bash
hugo
```

The generated static files will be in the `public/` directory.

## Project Structure

```
.
├── content/          # Content files (markdown)
├── themes/           # Hugo themes
│   └── massively/    # Massively theme
│       ├── layouts/  # Template files
│       └── static/   # Static assets (CSS, JS, images)
├── hugo.toml        # Hugo configuration
└── public/          # Generated static site (after build)
```

## Configuration

Edit `hugo.toml` to customize:
- Site title and metadata
- Theme parameters (intro, featured post, posts list, social links, contact info)
- Menu items

## Content

- `content/generic.md` - Generic page template
- `content/elements.md` - Elements reference page

## Theme

The Massively theme is located in `themes/massively/`. The theme includes:
- Responsive design
- Blog post layout
- Contact form
- Social media integration

## License

The Massively theme is licensed under the [Creative Commons Attribution 3.0 License](https://html5up.net/license).
