# QuickSite templates — generated

This folder is **generated** by `scripts/publish-templates.mjs` in the
[quicksite monorepo](https://github.com/QuickSiteSpace/quicksite). Do not
edit anything here by hand — changes get stomped on the next publish.

## Regenerating

From the monorepo root:

```bash
npm run publish:templates
```

That writes into this folder. Review the diff, then commit + push from
the website repo:

```bash
cd ../website
git add templates
git commit -m "Refresh template previews"
git push
```

## Source of truth

Each template's authoring file lives at
`quicksite/extension/src/templates/<id>.html` — a standalone HTML
document you can open directly in a browser. The extension imports these
at runtime; this folder is just a public mirror of the same files plus a
gallery index.
