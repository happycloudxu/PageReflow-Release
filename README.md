# PageReflow

**PageReflow** turns a PDF into one self-contained HTML file - accessible,
keyboard-operable and readable by a screen reader. It is a Windows desktop app,
distributed through the Microsoft Store.

## Install

Install PageReflow from the
[Microsoft Store](https://apps.microsoft.com/detail/9n088ljn0bk3). The package carries
everything the app needs, so nothing else has to be installed first: no Python, no separate
runtime, no unsigned-executable prompt, and the Store keeps it updated.

The Store edition is whichever build last cleared certification, the window shows the exact
version it is running, and it needs 64-bit Windows 10 or 11.

## What it does

- Three modes in the window: **Exact layout** (the page drawn as its own vectors, so text
  stays sharp and selectable at any zoom), **Exact layout** as a picture per page at the
  DPI you pick (for scans and diagram-heavy pages), and **Interactive checklist**, which
  turns a printable form into tickable rows. A page that has no vectors of its own falls
  back to a picture on its own, with a note saying so.
- **Reflowable text** - real headings, lists, tables and paragraphs - comes with the
  source distribution (`--mode text`); the Store build offers the three modes above.
- Output is a single `.html` file with every stylesheet, script and image inlined - no
  network access, no side files, works offline and from a USB stick.
- Keyboard and screen-reader support throughout the GUI and the generated pages.

## Support and privacy

Bugs, feature requests and questions belong in
[Issues](https://github.com/happycloudxu/PageReflow-Release/issues). There is no email
address and no ticketing system.

PageReflow collects nothing and makes no network connection; the
[privacy policy](privacy.html) says exactly what stays on your machine.
