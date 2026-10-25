# GangSheet Quote — free DTF gang sheet calculator

**How much film does a mixed-size DTF order need, which standard sheet fits, and what should you charge?**

Type in the designs on an order (any sizes, any quantities), your film width and the sheet lengths you sell. GangSheet Quote packs them to scale and gives you:

- film length needed (inches or mm)
- the smallest standard sheet that fits, and how much is left over
- film used vs. waste, in %
- cost breakdown: film + ink + powder, labor, setup
- a quote at your margin, rounded the way you like
- what each design "costs" per transfer
- a copy-ready quote text for the customer

**Try it:** https://stealth0xb.github.io/gangsheet-quote/ (runs in your browser, nothing is uploaded)

## Why

Most DTF shops have a gang sheet builder for customers, but when a custom order comes in with mixed sizes, someone still works out film, sheet and price by hand — "we'll get back to you within 24 hours". This tool answers in ten seconds.

## How the packing works

Rectangles are packed row by row (shelf packing), tallest first, with your gap. Two orientation strategies are tried and the one that uses less film wins. It is deliberately conservative: your RIP may squeeze a little more, so you never under-quote film.

## Offline version

The same tool as one HTML file that lives on your computer, works without internet, and gets free updates: **$19 one time** → https://lebbenofficial.gumroad.com/l/gangsheetquote

## Run locally

It's a single `index.html`. Download it and open it in any browser. No build step, no dependencies.

## Contributing

Issues and pull requests welcome. If a layout doesn't match how your shop actually quotes, open an issue with the sizes and quantities — that's exactly what improves the next version.

## License

MIT — Fabjon Lazri
