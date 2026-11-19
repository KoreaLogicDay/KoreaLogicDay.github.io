# How to edit the 2027 pages

This folder holds the pages of **The Sixth Korea Logic Day 2027** and the
**Set Theory Winter School**. Everything can be done in the web browser on GitHub.
After each change, the website updates automatically within a few minutes.

## Which file is which

| File | Page |
|:--|:--|
| `index.md` | Main page, English |
| `index_kr.md` | Main page, Korean |
| `abstracts.md` | Abstracts, English |
| `abstracts_kr.md` | Abstracts, Korean |

## Editing a page

1. Click the file name above (in this folder), then click the pencil icon ("Edit this file") at the top right.
2. Change the text. Replace "TBA" / "추후 공지" with the real information.
3. Click the green **Commit changes...** button, then **Commit changes** again.

Tips:

- Text between `<!--` and `-->` is a comment and is not shown on the website.
  The comments contain example lines you can copy.
- The top of each file, between the two `---` lines, holds the title, subtitle and date.
  You may change `title`, `subtitle` and `description`. Do not change the other lines there.
- Formatting: `**bold**`, `_italic_`, `[link text](https://address)`.
  A line starting with `* ` or `- ` is a list item.

## Where to check your changes

While the pages are not public, they can be seen only at these secret addresses
(share them only with the organizers):

- English: https://korealogicday.org/s4foq98m/2027/
- Korean: https://korealogicday.org/s4foq98m/kr/2027/

## Uploading slides and images

- **Slides:** open the folder `2027/slides/` (at the top level of the repository), click
  **Add file**, then **Upload files**. Link to a slide in a page as
  `([slides](/2027/slides/filename.pdf))`.
- **Images** (banner, logos): upload to the folder `assets/` in the same way. Use them as
  `https://korealogicday.org/assets/filename.jpg`.

Use file names without spaces, e.g. `lastname_slides.pdf`.

## Making the pages public

Open the file `_config.yml` (at the top level of the repository) and change

    kld2027_public: false

to

    kld2027_public: true

Then the pages appear at the usual addresses https://korealogicday.org/2027/ and
https://korealogicday.org/kr/2027/. The secret addresses then forward visitors there.
To hide the pages again, change it back to `false`.
