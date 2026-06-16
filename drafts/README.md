# Local Drafts

Start the local AEM development server with this folder as content source:

```sh
npx -y @adobe/aem-cli up --no-open --forward-browser-logs --html-folder drafts
```

Then open:

- `http://localhost:3000/drafts/`
- `http://localhost:3000/drafts/blocks-demo`
- `http://localhost:3000/drafts/plain-example`

These files are only local test content. They are useful when no Google Docs or previewed CMS page exists yet.

`nav.plain.html` and `footer.plain.html` are loaded as local fragments by the header and footer blocks.
