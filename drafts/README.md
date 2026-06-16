# Local Drafts

Start the local AEM development server with this folder as content source:

```sh
npx -y @adobe/aem-cli up --no-open --forward-browser-logs --html-folder drafts
```

Then open:

- `http://localhost:3000/`
- `http://localhost:3000/blocks-demo`
- `http://localhost:3000/plain-example`

These files are only local test content. They are useful when no Google Docs or previewed CMS page exists yet.
