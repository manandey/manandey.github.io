# Website Migration - Changes Summary

## What's New ✨

### Clean Template Migration
- Switched from Jekyll (al-folio) to Jon Barron's plain HTML/CSS template
- **No build process required** - just open `index.html`!
- Removed all Jekyll dependencies, Ruby, Gemfile, etc.

### Enhanced Content 📚
- **18 Publications** (2019-2025) with latest from Google Scholar
- **5 US Patents** (1 granted, 4 filed)
- **6 Major Awards** including Salesforce hackathon finalist
- **Activities & Service** section with reviewer/volunteer roles
- Updated bio with current Salesforce position

### Vibrant Design 🎨
- **Colorful gradient images** for all publications
- **Enhanced CSS** with hover effects and smooth transitions
- **Bold section headers** with colored underlines
- **Highlighted key papers**: BLOOM, StarCoder, T0, Consent in Crisis (2,600+ citations each)
- Improved link colors and hover states

### Key Publications Featured
1. **BLOOM** - 176B parameter multilingual LLM (2,600+ citations)
2. **StarCoder** - 15.5B Code LLM (2,100+ citations)
3. **T0** - Zero-shot task generalization (2,600+ citations)
4. **Consent in Crisis** - AI data commons analysis (NeurIPS 2024)

## File Structure

```
.
├── index.html              # Main website (669 lines)
├── stylesheet.css          # Enhanced styling with colors
├── images/
│   ├── MananDey.jpg       # Profile photo
│   ├── bloom.jpg          # Colorful publication thumbnails
│   ├── starcoder.jpg      # (17 gradient images created)
│   └── ...
├── README.md              # Setup and deployment guide
└── CHANGES.md             # This file
```

## Backup Location
Original al-folio site backed up to:
`~/Desktop/manandey.github.io-backup-20260614-112258`

## Next Steps 🚀

1. **Test the website**: Already open in your browser!
2. **Commit changes**:
   ```bash
   git add -A
   git commit -m "Migrate to vibrant Jon Barron template"
   git push origin new-template-clean
   ```
3. **Create PR**: Merge `new-template-clean` → `main`
4. **Deploy**: GitHub Pages will automatically deploy

## Customization Tips 💡

### Adding a New Publication
```html
<tr bgcolor="#ffffd0">  <!-- Add this for highlight -->
  <td style="padding:16px;width:20%;vertical-align:middle">
    <img src='images/your_paper.jpg' width="160">
  </td>
  <td style="padding:8px;width:80%;vertical-align:middle">
    <a href="paper_url"><span class="papertitle">Title</span></a>
    <br>Authors<br><em>Venue</em>, Year<br>
    <a href="link">arXiv</a><p></p>
    <p>Description</p>
  </td>
</tr>
```

### Color Scheme
- Links: `#2E86DE` (blue) → `#EE5A24` (orange) on hover
- Headers: `#2C3E50` with `#3498DB` underline
- Strong text: `#E74C3C` (red)
- Highlight: `#FFF9C4` (yellow)

---

**Total Time**: ~45 minutes
**Files Changed**: Removed 200+ Jekyll files, added clean HTML/CSS
**Result**: Fast, beautiful, maintainable academic website! 🎉
