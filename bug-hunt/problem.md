# Bug Hunt: 10 broken snippets and 3 broken layouts

## The problem

Every file in this pack is broken. Each one says what it should show. Your job is to make it do that.

## Part 1: the snippets (folder `snippets`)

Open each `snippet-NN.html` in the browser with the Console open (F12), and open the file in your editor.

For every snippet:

1. Read what it should show.
2. Reproduce the bug: refresh and look at the Console and the page.
3. Isolate it: find the exact line.
4. Fix it, refresh, and confirm it now shows what it should.
5. Write one line on the cause.

Snippets 08, 09 and 10 have no red error. For those, you need to trace the values with `console.log`.

## Part 2: the layouts (folder `layouts`)

Open each `layouts/layout-N/broken/index.html` with DevTools on the Elements panel. Use device mode at 375px and 1280px.

For every layout:

1. List each thing that looks wrong, at both sizes.
2. Find the evidence for each in the Styles pane, the Computed tab or the box model.
3. Fix it live first, then copy the fix into `styles.css`.
4. Write one line on the cause of each.

What each layout should look like:

- **Layout 1, navbar:** the logo on the left, the four links in a row in the middle, the Enrol button on the right, all on a dark bar. On a phone nothing may spill out of the bar.
- **Layout 2, hero:** text on the left, picture on the right, and a small "4.9 average rating" card sitting on the bottom left corner of the picture. On a phone the text sits above the picture and nothing scrolls sideways.
- **Layout 3, features:** six cards, three per row on a desktop and one per row on a phone, with the footer at the end of the page, never on top of the cards.

## Your notes

Copy this and fill it in:

```
Snippet 01:
Snippet 02:
Snippet 03:
Snippet 04:
Snippet 05:
Snippet 06:
Snippet 07:
Snippet 08:
Snippet 09:
Snippet 10:
Layout 1:
Layout 2:
Layout 3:
```
