# Spark Amp Control support & policies

Public support and policy pages for the independent Spark Amp Control macOS app (called SparkControl in the app).

## Published pages

- Home: https://sparkcontrolapp.github.io/tos/
- Support: https://sparkcontrolapp.github.io/tos/support/
- Privacy Policy: https://sparkcontrolapp.github.io/tos/privacy/
- Terms of Use: https://sparkcontrolapp.github.io/tos/terms/
- MCP setup and capabilities: https://sparkcontrolapp.github.io/tos/mcp/

Support contact: highway.shark4q@icloud.com. Reviewer-only contact details are not stored in this public repository.

## Edit or preview

This is a buildless static site. Edit the HTML pages and `assets/site.css` directly. All fonts and visual assets are local; there is no JavaScript, analytics, or contact-form service.

```sh
python3 -m http.server 8094
```

Open http://127.0.0.1:8094/ . GitHub Pages publishes `main` from the repository root. `.nojekyll` keeps the site buildless. All internal links work below the `/tos/` project path and also on a custom domain.

## Policy maintenance

The privacy text reflects the app’s local storage, Positive Grid requests, local MCP server, diagnostics, permissions, and optional support emails. Update it when data practices change. The Terms page links Apple’s Standard EULA; it does not supply a custom replacement EULA. Do not put credentials, reviewer passwords, access tokens, private diagnostics, or confidential review notes in this repository.

App Store Connect privacy-label answers must separately account for third-party processing; the local app privacy manifest and this page do not fill in that declaration.

## App images

`assets/screenshots/` contains optimized WebP exports of the developer-provided app captures, displayed proportionally with descriptive alternative text. The homepage shows the editor, library, and looper; Support shows the first-connection screen. Each image opens at its larger size. No generated demo screenshots or third-party network image services are used. The supplied AI image is not published because it displays the account email.
