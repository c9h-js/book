# Contributing

The Cottonmouth Book is entirely open-source, and we welcome all contributions!

This book is built using [mdBook](https://github.com/rust-lang/mdBook), a static
documentation site generator implemented in Rust by the Rust Team.

## Markdown

All pages are written in
[Markdown](https://rust-lang.github.io/mdBook/format/markdown.html) and saved in
the `src/` directory.

### Summary file

The `src/SUMMARY.md` file is used to generate the book's navigation menu.

New pages must be added to this file so they are included in the navigation menu
(this doesn't happen automatically).

## Style guide

We use [MarkdownLint](https://github.com/igorshubovych/markdownlint-cli) to
enforce consistency across all Markdown files that make up this book.

After cloning this book's repository, you can download the MarkdownLint CLI by
installing the repo's NPM dependencies (`npm ci` or `yarn install
--frozen-lockfile`).

Finally, you can run the lint script (`npm run lint` or `yarn lint`) to check
all Markdown files (`src/**/*.md`) for formatting errors/warnings.

> Note: You should run MarkdownLint **before** submitting any PRs!

## Contributors

Outside of the Cottonmouth Team, these amazing people have helped shape The
Cottonmouth Book into what it is today:

- None as of yet: you could be the first 💪!
