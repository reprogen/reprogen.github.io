# reprogen.github.io

Homepage for ReproGen Shared Tasks

Repository for website https://reprogen.github.io

## Editing

You can modify the pages directly on GitHub, and your changes will be pushed to the website immediately.

- Modify the main page (`index.md`):

https://github.com/reprogen/reprogen.github.io/blob/main/index.md

- Modify the specific pages (`cd _pages`):

https://github.com/reprogen/reprogen.github.io/tree/main/_pages

- Modify the navigation:

[/_data/navigation.yml](./_data/navigation.yml)

The url (e.g., `/programme/`) in the navigation file should match the page permalink (e.g., `permalink: /2021/accepted-papers/`).


## Running locally

You can also modify the website locally to preview the changes. For that, the following is needed:

1. Install [Jekyll](https://jekyllrb.com/docs/installation/)
2. Clone the repository: `git clone https://github.com/reprogen/reprogen.github.io.git`
2. Navigate to the repository directory (`cd reprogen.github.io`)
3. Run `bundle install`
4. Run `bundle exec jekyll serve`
5. To preview the site, in your web browser, navigate to http://localhost:4000

### Credits

Thanks Hendrik and Dimitra for providing the starter code.
