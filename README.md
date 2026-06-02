[README.md](https://github.com/user-attachments/files/28527947/README.md)
# Pricing cards — designer practice

A single static page (`index.html`) with three pricing cards. No build step, no framework.
Open `index.html` in a browser to see it. Edit it in Cursor, commit, push.

## How to run

Double-click `index.html`, or in the terminal:

```
open index.html        # macOS
start index.html       # Windows
```

## Practice tasks (easy to hard)

1. Change the page background colour. Find `--page-bg` at the top of the `<style>` block.
2. Change the button colour. Edit `--button-bg` and `--button-hover`.
3. Change a price. The prices are plain text inside each card (`price__amount`).
4. Edit the text on a card — title, subtitle, or an item in the `Includes` list.
5. Add a fourth bullet to the "Enscape Solo" card. Copy one `<li>...</li>` line.
6. Add a fourth card. Copy a whole `<article class="card">...</article>` block and change its content.
7. Move the "Preferred choice" badge from Premium to a different card (move the `<span class="badge">` line).

## Notes

- Colours, font and shape live in the `:root` variables at the top of the file. Start there.
- Each card is one `<article class="card">` block with the same structure, so they are easy to copy.
