# Manan Dey's Personal Website

A clean, minimal academic personal website built with plain HTML/CSS, based on [Jon Barron's website template](https://github.com/jonbarron/jonbarron_website).

## About

I am a Senior Member of Technical Staff at Salesforce, working on the Developer Experience Team. My research interests lie in Machine Learning, Deep Learning, and Natural Language Processing, with over 10,000 citations across major publications including BLOOM, StarCoder, and T0.

## Features

- **Simple & Fast**: Plain HTML/CSS with no build process
- **Clean Design**: Jon Barron's elegant, research-focused layout
- **Complete Profile**: Publications, patents, honors & awards
- **Highlighted Papers**: Key contributions clearly marked
- **Responsive**: Works beautifully on all devices

## Quick Start

1. Clone this repository
2. Update `index.html` with your information
3. Replace `images/MananDey.jpg` with your photo
4. Add publication thumbnails to `images/`
5. Deploy to GitHub Pages

## Customization

### Adding Publications

Add a new table row (`<tr>`) in the publications section:

```html
<tr>
  <td style="padding:16px;width:20%;vertical-align:middle">
    <div class="one">
      <img src='images/your_paper.jpg' width="160">
    </div>
  </td>
  <td style="padding:8px;width:80%;vertical-align:middle">
    <a href="paper_url">
      <span class="papertitle">Your Paper Title</span>
    </a>
    <br>
    Authors including <strong>Your Name</strong>
    <br>
    <em>Venue</em>, Year
    <br>
    <a href="arxiv_link">arXiv</a>
    <p></p>
    <p>
    Brief description of your work.
    </p>
  </td>
</tr>
```

### Highlighting Papers

Add `bgcolor="#ffffd0"` to the `<tr>` tag to highlight important papers.

### Styling

- Edit `stylesheet.css` for colors and fonts
- Modify table widths and padding in `index.html`

## Deployment

### GitHub Pages

1. Push changes to GitHub:
   ```bash
   git add -A
   git commit -m "Update website"
   git push origin main
   ```

2. Enable GitHub Pages in repository settings:
   - Go to Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/` (root)

3. Your site will be live at `https://yourusername.github.io`

### Custom Domain

1. Add a `CNAME` file with your domain
2. Configure DNS settings with your provider
3. Update GitHub Pages settings

## Local Development

No server required! Just open `index.html` in your browser:

```bash
open index.html
```

## Project Structure

```
.
├── index.html          # Main website file
├── stylesheet.css      # Styling
├── images/            # Images and photos
│   ├── MananDey.jpg   # Profile photo
│   └── *.jpg          # Publication thumbnails
├── blog/              # Optional blog (from old template)
└── README.md          # This file
```

## Backup

The original al-folio Jekyll site is backed up at:
`~/Desktop/manandey.github.io-backup-20260614-112258`

## Credits

- Template: [Jon Barron](https://jonbarron.info/)
- Original Jekyll theme: [al-folio](https://github.com/alshedivat/al-folio)

## License

The template is available as open source under the terms of the MIT License.

---

**Note**: This is a clean, static HTML website. No Ruby, Jekyll, or build process required!
