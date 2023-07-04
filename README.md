# My Personal Website

This repository contains the source code for my personal website, which is built using Hugo, a static site generator.

## How to Use

1. Install [Hugo](https://gohugo.io/getting-started/installing/).
2. Clone this repository.
3. Run `hugo server` to start the Hugo server.
4. Navigate to `localhost:1313` in your browser to view the site.
5. Make changes to the site and see them reflected in real time.
6. To add a new post, run `hugo new <post-folder-in-content>/<post-name>.md`. For example, `hugo new blog/my-first-post.md`.
7. To include the draft posts, run `hugo server -D` or `hugo server --buildDrafts`.
8. When you're done, run `hugo` to build the site.
9. Build the site by running `hugo`.
10. In the `docs` folder, you'll find the generated static site.
11. Commit and push the changes to the `master` branch.
12. The site will be automatically deployed to GitHub Pages. The branch to be deployed is configured on GitHub -> Settings -> Pages -> Source: choose Deploy from a branch; Branch: choose master, /docs.
