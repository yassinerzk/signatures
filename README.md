# Email Signature

This project contains a responsive email signature designed to be embedded in Gmail (or other email clients) and hosted on GitHub.

## Project Structure

- `index.html`: The main signature file with **inline CSS**. This is the file you should use for Gmail.
- `styles.css`: The external stylesheet. Useful for development or if you are using a tool that inlines CSS automatically.

## How to use in Gmail

1. Open `index.html` in a web browser (Chrome, Firefox, etc.).
2. Press `Ctrl + A` (or `Cmd + A` on Mac) to select everything on the page.
3. Press `Ctrl + C` (or `Cmd + C`) to copy.
4. Go to your Gmail settings (Gear icon > See all settings).
5. Scroll down to the **Signature** section.
6. Create a new signature or edit an existing one.
7. Paste (`Ctrl + V` or `Cmd + V`) the content into the signature box.
8. Scroll to the bottom and click **Save Changes**.

## GitHub Hosting

You can host this repository on GitHub.
1. Initialize a git repository: `git init`
2. Add files: `git add .`
3. Commit: `git commit -m "Initial commit"`
4. Push to your GitHub repository.

### Hosting Images
For the signature to work correctly, the images (icons and banner) must be publicly accessible on the internet.
- Currently, the signature uses public icons from a CDN (Flaticon) and a placeholder banner.
- **Recommended**: Upload your actual banner image and specific icons to this GitHub repository.
- After pushing to GitHub, click on an image file in the repository, click "Download" or "Raw" to get the direct URL (or use GitHub Pages), and replace the `src` attributes in `index.html` with those URLs.

## Customization

To change the details:
1. Open `index.html` in a text editor (VS Code, Notepad, etc.).
2. Locate the text you want to change (e.g., "John Doe", "Head of Marketing").
3. Update the text.
4. Update links (e.g., `href="mailto:..."`, `href="https://..."`).
