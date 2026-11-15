# JoJo's Bizarre Adventure — Static Tribute Site

A responsive, single-page fan tribute built with plain HTML and CSS. The site includes a personal introduction, a look at Stand battles and JoJo's varied influences, a spoiler-marked Death Thirteen example, a guide to the nine manga parts, and source links.

## Files

- `index.html` — page structure and written content
- `style.css` — responsive layout, colors, typography, and decorative artwork
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment
- `.gitattributes` and `.editorconfig` — consistent LF line endings across Windows and other platforms

## Run locally on Windows

Keep `index.html` and `style.css` in the same folder. Open `index.html` in Edge, Chrome, or Firefox. No Node.js, Python, JavaScript build step, or package installation is required.

The stylesheet is linked in the document `<head>` with:

```html
<link rel="stylesheet" href="style.css">
```

The project uses UTF-8 text and LF line endings. The Git message `This diff contains a change in line endings from 'LF' to 'CRLF'.` is a formatting warning, not an HTML/CSS runtime error. The included `.gitattributes` and `.editorconfig` keep these files consistent. In Visual Studio Code, the line-ending indicator in the bottom-right should say `LF`.

## Publish

The repository includes a GitHub Actions workflow that publishes the site to GitHub Pages whenever a commit is pushed to `main`, and can also be run manually from the Actions tab. After the first successful run, the live website URL appears in the deployment summary and in **Settings → Pages**.

## Notes

This is an unofficial, educational fan tribute. JoJo's Bizarre Adventure and its related characters and materials belong to their respective rights holders. Research links are included in the page footer.
