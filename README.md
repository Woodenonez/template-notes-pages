# Template for Notes as GitHub Pages
This is a template for deploying notes as GitHub pages. This is for my personal use, but you can use it as a starting point for your own notes. To do so, change the relevant fields in the `_config.yml` file and edit the `index.md` file to add your notes.

## Usage
1. Clone this repository.
2. Set `baseurl` and `title` in [_config.yml](./_config.yml).
3. Edit [index.md](./index.md) to add your notes.
4. Add your notes in the [notes](./notes) directory, following the given structure.

## Render and preview
To render the notes, ensure you have [Jekyll](https://jekyllrb.com/) installed. Run
```bash
bundle exec jekyll serve
```
to render the notes and preview them in a browser at `http://localhost:4000/`.