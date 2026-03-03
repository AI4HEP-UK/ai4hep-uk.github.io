# AI4HEP-UK Project Website

GitHub repository for the [website of the AI4HEP-UK project](https://ai4hep-uk.github.io).


## Developer and Contributor Information

The site is built with [Hugo](https://gohugo.io) and [Bootstrap](https://getbootstrap.com/).
The pages are in Markdown, with most top-level content under `content/`.
News are collected under `content/posts/`.

To make changes to the site, fork and make Pull Requests.
To build locally, ensure you have Hugo and Bootstrap installed.
Refer to their documentation for detailed and up-to-date instructions.

To post news the typical command is:

```bash
hugo new content content/posts/YYYY-MM-DD_my-nice-post.md
```

As a rule, add new pages with the `hugo new` command so that they get placed in the correct folder.

### Updating Hugo and Bootstrap

Refer to the relevant documentation on the [Hugo](https://gohugo.io) and [Bootstrap](https://getbootstrap.com/)
websites for usage with your favourite package manager.
