# Mishra Research Lab website

A responsive, static HTML/CSS/JavaScript website designed for GitHub Pages. No Jekyll, build process, server, or paid hosting is required.

## Files
- `index.html`: homepage
- `research.html`: research areas
- `projects.html`: project summaries
- `publications.html`: selected-publication layout (verify all citations before publishing)
- `people.html`: PI and team
- `news.html`: news and updates
- `contact.html`: contact page
- `assets/css/style.css`: design system and responsive styling
- `assets/js/main.js`: mobile navigation and current year
- `.nojekyll`: tells GitHub Pages not to run Jekyll processing

## Publish using GitHub's website (no command line needed)

1. Sign in to https://github.com/sukhdevmishra.
2. Create a **new public repository** named exactly `sukhdevmishra.github.io`.
3. Open the new repository and select **Add file → Upload files**.
4. Unzip this download on your computer. Upload the **contents** of the `mishra_research_lab` folder, not the enclosing folder itself. `index.html` must appear in the root of the repository.
5. Commit the uploaded files to the `main` branch.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Select branch `main` and folder `/ (root)`, then click **Save**.
9. Wait a few minutes and open https://sukhdevmishra.github.io/.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Important before public launch

This is a design-complete starter, not a verified institutional publication record. Please:
- Confirm the exact official institute name and designation.
- Replace the contact email placeholder with an official public email.
- Replace publication examples with exact verified citations, DOI/PubMed links, and author order.
- Confirm current project status, funders, collaborators, and which details may be made public.
- Add approved photographs and team profiles.
- Replace placeholder Google Scholar and ORCID links with your actual profile URLs.
- Check that any project descriptions are suitable for public release.

GitHub Pages sites are public. Do not upload confidential, unpublished, restricted, or personally sensitive information.

## Editing content

Edit the relevant `.html` file directly in GitHub using the pencil icon, then commit the change. CSS changes belong in `assets/css/style.css`. Every page shares the same stylesheet and JavaScript.
