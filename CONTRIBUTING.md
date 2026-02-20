# Contributing to Guelph Webring

Thanks for contributing.

## Add your site

1. Fork this repository.
2. Edit `index.html` and add your entry in `webringData.sites`:

```json
{
  "name": "Your Name",
  "year": 20XX,
  "website": "https://your-site.com",
  "links": {
    "instagram": "https://instagram.com/your-handle",
    "twitter": "https://x.com/your-handle",
    "linkedin": "https://linkedin.com/in/your-handle"
  }
}
```

3. Keep entries valid JSON and include `https://` in URLs.
4. Open a pull request.

## Basic checks

- Ensure your site URL loads.
- Ensure search and navigation still work.
