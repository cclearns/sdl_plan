# My 6-Week English Plan

A static site with no build step. Students answer eight steps and download their plan as a Word (.docx) file.

## Publish on Netlify

1. Sign in at https://app.netlify.com
2. Open https://app.netlify.com/drop
3. Drag this whole folder (or the zip) onto the page.
4. Netlify gives you a link such as https://random-name.netlify.app. Rename it under Site configuration > Change site name.

To update the site later, drag the new folder onto the site's Deploys page.

## Files

- index.html: the whole page (text, menus, and the Word export)
- jszip.min.js: the library that builds the .docx file (JSZip 3.10.1, MIT license)
- netlify.toml: tells Netlify to publish this folder as it is

## Change the content

All menus and texts are near the top of the script in index.html. The fixed start date is the line `var START="2026-10-22";`.

Answers are saved only in each student's own browser. Nothing is sent to a server.
