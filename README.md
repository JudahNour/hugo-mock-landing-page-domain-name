# hugo-mock-landing-page
Mock landing page for the fake product "SpeedrunSplits." This was done for Homework 1 of CIS 3500 at Penn

## Workflow Description
This project is automatically built and deployed to GitHub Pages using a GitHub Actions workflow. The workflow is triggered on pushes to the `main` branch and performs the following steps:

1. Check out the repository code
2. Set up the Hugo environment
3. Build the static files using Hugo
4. Deploy the built files to the `gh-pages` branch