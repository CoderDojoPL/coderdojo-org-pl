# CoderDojo Poland

This repository contains the source code and content for the CoderDojo Poland website, built with [Hugo](https://gohugo.io/) and the [Blowfish](https://blowfish.page/) theme.

## Purpose

- Promote volunteering as a meaningful and empowering activity.
- Preserve and showcase the legacy of the CoderDojo Poland initiative (2013–2020).
- Provide a landing page and onboarding flow for potential mentors.

The site is focused on promoting the *idea* of volunteering, with CoderDojo as a successful past example.

## Development

### Prerequisites

- [Hugo](https://gohugo.io/) (v0.147.9+ recommended)
- Git (for theme submodule)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/coderdojo-org-pl.git
   cd coderdojo-org-pl
   ```

2. Initialize the theme submodule:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:
   ```bash
   hugo server --buildDrafts
   ```

4. Open your browser and navigate to `http://localhost:1313`

### Building for Production

```bash
hugo --minify
```

The generated files will be in the `public/` directory.

## Theme

This site uses the [Blowfish](https://blowfish.page/) Hugo theme, which provides:

- Modern, responsive design
- Dark/light mode support
- Excellent performance
- SEO optimization
- Multi-language support

### Theme Documentation

The Blowfish theme includes comprehensive documentation both locally and online:

- **Online:** [https://blowfish.page/docs/](https://blowfish.page/docs/) (always up-to-date)
- **Local:** `themes/blowfish/exampleSite/content/docs/` (included in the repository)

To view the local documentation:
```bash
# Run the theme's example site
cd themes/blowfish/exampleSite
hugo server

# Or browse the markdown files directly
cat themes/blowfish/exampleSite/content/docs/configuration/index.md
```

The local docs include detailed information on configuration, shortcodes, customization, and all theme features.

## Site Structure

- `content/` - Markdown content files
- `config/_default/` - Site configuration
- `static/` - Static assets (images, files, etc.)
- `themes/blowfish/` - Theme submodule

## Deployment

This site is designed to be deployed via [Netlify](https://www.netlify.com/) with automatic builds from the Git repository.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `hugo server`
5. Submit a pull request

## License

CC BY-NC 4.0