# Contribution guide

1. Clone the repo from GitHub (if needed)
1. Checkout and pull the most recent `master` branch
1. Create a branch for your changes
1. Make your changes (e.g., [team updates](#updating-the-team-page), [project updates](#updating-an-existing-project-page), [news updates](#adding-a-news-item))
1. Commit your changes to your branch
1. Push your branch to GitHub
1. Create a Pull Request to merge with `master` and assign it to @huytran1 for review
1. Delete your local branch once the PR has been accepted

## Updating the team page

Update the team page by updating `/_pages/team.md`.

## Updating or adding a project page

Update a project page by updating its `/_research/project-name.md` file (including the `last_modified_at:` line in the header).

Add a new project page by creating a new `/_research/project-name.md` file (use `/docs/templates/research-project.md` as a template).

## Updating or adding a news item

Update a news item by updating its `/_posts/news-name.md` file (including the `last_modified_at:` line in the header).

Add a new news item by creating a new `/_posts/news-name.md` file (use `/docs/templates/research-project.md` as a template).

# Installation

1. Install [Jekyll](https://jekyllrb.com/docs/installation/) (if needed). The installation should include Ruby, Bundler, and Jekyll. I would suggest a local install.
1. Clone the repo from GitHub
1. Change to the project directory and install Gemfile dependencies

        $ bundle install

1. Test the site locally

        $ bundle exec jekyll serve
        # view the site in your web browser (http://127.0.0.1:4000/)

# Publishing the site

These steps are based on [this site](http://davidensinger.com/2013/04/deploying-jekyll-to-github-pages/).

1. Clone the repo from GitHub (if needed)
1. Checkout and pull the most recent `master` branch
1. Test the site locally

        $ bundle exec jekyll serve
        # view the site in your web browser (http://127.0.0.1:4000/)

1. If it looks good, build the site locally

        $ bundle exec jekyll build

1. Commit and push any changes to your `master` branch

        $ git add .
        $ git commit -m "change message"
        $ git push origin

1. Copy the content in `_site/` to a temporary directory (e.g., `../_site-temp/`)
1. Delete your local `gh-pages` branch

        $ git branch -D gh-pages

1. Fetch branches from GitHub

        $ git fetch

1. Checkout and track the `gh-pages` branch

        $ git switch gh-pages

1. Delete everything in the root directory of the `gh-pages` branch except for `.git` and `.gitignore`
1. Copy-paste everything from the temporary directory (e.g., `../_site-temp/`) to the root directory (so the `gh-pages` branch only contains static site files and git directories)
1. Commit and push your changes to the `gh-pages` branch

        $ git add .
        $ git commit -m "update site files"
        $ git push origin

1. Checkout the `master` branch (which contains the source files)

        $ git checkout master

# Acknowledgements

This site was created using the [starter template](https://github.com/mmistakes/mm-github-pages-starter/generate) for the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes), with some modifications to the theme (mostly found in `/_sass/minimal-mistakes.scss`). I cloned the Minimal Mistakes repo to install the theme because the Jekyll Scholar plug-in seems to have issues with the github-pages Gem, which seemed to cause problems with using the theme as a remote theme.

[Jekyll Scholar](https://github.com/inukshuk/jekyll-scholar) is used to generate the publications page.
