# New Session Studios website

Simple static website for New Session Studios Pty Ltd, designed for GitHub Pages.

## Files

- `index.html` - Main business homepage
- `privacy.html` - General privacy policy for the business website
- `chord-groove-privacy.html` - Privacy policy for Chord Groove
- `support.html` - Support page for app store listings
- `style.css` - Shared styling
- `CNAME` - Custom domain for GitHub Pages
- `.nojekyll` - Disables Jekyll processing

## Deployment

1. Create a GitHub repository, for example `newsessionstudios.com.au`.
2. Upload these files to the root of the repository.
3. In GitHub, go to Settings -> Pages.
4. Set Source to `Deploy from a branch`.
5. Choose branch `main` and folder `/root`.
6. Save.
7. Set the custom domain to `newsessionstudios.com.au` and enable HTTPS once available.

## DNS summary

For the apex domain `newsessionstudios.com.au`, create A records pointing to GitHub Pages:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

For `www.newsessionstudios.com.au`, create a CNAME pointing to your GitHub Pages default domain, such as:

- YOUR_GITHUB_USERNAME.github.io

Replace `YOUR_GITHUB_USERNAME` with your GitHub username or organization name.
