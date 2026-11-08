# Strand Notes
Preview: `node build.js --drafts --serve`, then open http://localhost:8080
Publish: Cloudflare Pages, build command `node build.js`, output `dist`.
Article: content/posts/<name>.md   Product: content/products/<name>.md   Images: static/img/
Article fields: title, slug, date (YYYY-MM-DD), category, description, image, pin, picks: [product names], popular: true, draft: false
Product fields: title, category, asin, bestFor, why, image, popular: true, draft: false
In an article, put {{product:file-name}} on its own line to show a product card.
Set url, email, amazonTag in config.json.
