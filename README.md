# Politician Wikipedia Articles Drafts

This repository contains draft articles for Indian politicians, prepared in Markdown format for collaboration and version control before submission to Wikipedia.

## How to Use

- Drafts are stored in the `drafts/` folder.
- Each file corresponds to a politician.
- Use GitHub pull requests to review and improve drafts collaboratively.
- When ready, convert Markdown to Wikipedia markup and submit on Wikipedia.

## Conversion

To convert Markdown to Wikipedia markup, you can use [Pandoc](https://pandoc.org/):

```bash
pandoc drafts/mahesh-bansal.md -f markdown -t mediawiki -o drafts/mahesh-bansal.wiki
