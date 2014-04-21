# Atlanticsalmonforum.org website details

## Overview

- **domain**: [atlanticsalmonforum.org](http://atlanticsalmonforum.org)
- **services used**:
	- [Github Pages](http://pages.github.com) - hosting
	- [Typekit](http://typekit.com) - typography
	- [JotForm](http://jotform.com) - abstract submission

The code is available at [https://github.com/salmonhabitat/atlanticsalmonforum](https://github.com/salmonhabitat/atlanticsalmonforum).

GitHub Pages is a cost-effective, resilient service that leverages Jekyll to build and serve webpages. Pages are generated server-side, backed by Github's CDN services, and rely on `git`, a decentralized version control system that makes it easy for developers to collaborate. By using GHP, we maintain complete control over the content of our websites, and don't rely on backends like Wordpress, which present security issues if not actively maintained.

#### Making changes

Edits can be made 2 ways:
	1. `clone` the git repository at `https://github.com/salmonhabitat/atlanticsalmonforum.git`, and use the editor you are comfortable with to make changes. A knowledge of Git is required. This is the more technical option, one suitable for web developers.
	2. Using the github login information provided, log in to [Prose.io](http://prose.io), and edit the files using the web interface. The less technical option. 

#### Structure

The code is heavily commented. For specific details on how things work, view the source.

At a broader scale, the site consists of two main components:
	1. The [`layout`](https://github.com/salmonhabitat/atlanticsalmonforum/blob/gh-pages/_layouts/default.html) page provides an basic platform on which additional pages can be built.
	2. The main content/copy is located in the [`_includes/`](https://github.com/salmonhabitat/atlanticsalmonforum/tree/gh-pages/_includes) directory.

Typically, edits will need to made only to the files in the `includes/` directory.

#### Assets

Assets include the CSS used to style the webpage, and any images used. PDF's created prior to 2014 are hosted by NOAA, all others are hosted on Amazon S3. Future years sessions can be hosted wherever is most easily accessible, so long as the links are updated appropriately. Also note that rather than manually entering hundreds list items, a template is used to iterate through the [various talks](https://github.com/salmonhabitat/atlanticsalmonforum/blob/gh-pages/_data/session-1.yml).
