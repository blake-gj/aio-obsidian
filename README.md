# Obsidian Publish Assets Repository

This private repository serves as a centralized storage location for all assets used on my [Obsidian Publish](https://publish.obsidian.md/) site. These assets include, but are not limited to:

- Images
- Custom CSS
- JavaScript snippets
- Icons
- Fonts
- Any additional resources required for theming or functionality

---

## Purpose

The purpose of this repository is to:

1. **Centralize Asset Management**  
   Keep all resources for the Obsidian Publish site in one place for easier organization and access.

2. **Version Control**  
   Track changes to assets over time, ensuring easy rollback and modification.

3. **Ease of Deployment**  
   Integrate with automation or manual workflows for deploying updated assets to the Obsidian Publish site.

---

## Repository Structure

```plaintext
├── css/
│   ├── publish.css        # Main stylesheet for Obsidian Publish
│   └── [additional CSS files]
├── js/
│   ├── [JavaScript files] # Optional JS for added functionality
├── images/
│   ├── [image files]      # Site images (e.g., logos, icons, diagrams)
├── fonts/
│   ├── [font files]       # Custom fonts for the site
├── backups/
│   ├── [previous versions of critical assets]
├── README.md              # This file
```

---

## Usage Instructions

1. **Adding Assets**
   - Place new assets in the appropriate folder according to the repository structure.
   - Ensure filenames are descriptive and follow a consistent naming convention.

2. **Syncing with Obsidian Publish**
   - Pull or download the required assets into your Obsidian vault.
   - Reference these assets in your Markdown files using relative paths or URLs as needed.

3. **Updating Styles**
   - Edit the `publish.css` file to update site styles.
   - Test changes locally before pushing them to ensure compatibility.

4. **Backing Up**
   - Use the `backups/` folder to save older versions of critical assets before overwriting.

---

## Notes

- This repository is private to maintain control over sensitive assets.
- Ensure any updates made here are reflected in the published site by syncing and deploying as necessary.

---

## Future Plans

- Explore automation to streamline asset deployment to the Obsidian Publish site.
- Enhance the theming and functionality of the site with additional assets as needed.

---

## License

This repository is private, and all assets stored here are proprietary and intended solely for personal or organizational use.
