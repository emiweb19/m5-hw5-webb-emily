# Assignment 5: Audit a Website for Accessibility

(**NOTE:** View a rendered version of this file in VS Code with `ctrl-shift-v` or `cmd-shift-v`)

&nbsp;
## Background

In this assignment, you will learn about auditing websites for accessibility issues. You will first audit an existing website for accessibility issues using accessibility tools and then fix the website so that it is accessible.

&nbsp;
## Setup

1. Create a git repository titled `m5-hw5-lastname-firstname` and clone the repo to your computer. 
1. Copy the contents of the `unsolved` folder (NOT including the folder itself) into the root folder of your repository.

&nbsp;
## Instructions

1. Using an accessibility tool of your choice (or multiple), audit the website as it exists for issues.
1. Fix the accessibility issues, continuing to audit to ensure that no issues exist. Annotate the fixes for your audits in the README file in the repository.
    1. You must preserve the content of the site as you fix issues.
    1. You may adjust colors as necessary to add contrast.
    1. You may change or add HTML tags to fix structural and/or semantic issues, but be sure you do not break any CSS selectors in `style.css` when you do so.
1. Deploy the finished site to GitHub pages.

&nbsp;
## Deployment

Your code must be deployed to GitHub Pages. To deploy a repository to GitHub pages you must:

1. Ensure your repository has an `index.html` file in the root directory.
1. Navigate to the `settings` section of the repository.
1. Click on `pages` in the left navigation menu.
1. Under `source` click the dropdown and select your `master` or `main` branch.
1. Click `save`.

Your site should be deployed to `<your github username>.github.io/<your repository name>` in 5-10 minutes.

&nbsp;
## Submission

Please submit both a link to your repository and a link to the live site. Also please include any comments on stumbling blocks or difficulties encountered while completing the assignment.

## Accessibility Audit Notes and Changes
Change the color of .nav a to white to increase contrast with the background.
Change the color of body text to black to increase contrast.
Change the color of footer text to white to increase contrast.
Remove black phone icon since it has low contrast and doesn't work well with a screen reader.
Add <label> to each form control.
Add a black background to h1 to increase contrast.
Change About Me to h2 to avoid skipping a heading level. Increase the size to improve site hierarchy. 
Add site regions.