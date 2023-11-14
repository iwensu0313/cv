# Steps to updating your website

1. Updating the website:
* To edit the **About me** page, edit `content/about/_index.md` directly
* To add to the portfolio, create a new markdown file in `content/portfolio`. Add a date prefix for easier sorting of oldest to newest

2. Run `hugo server` in the terminal to view changes to the website locally

3. Once happy with the changes, commit and push the changes to the `main` branch. This will trigger GitHub Actions to rebuild the website.