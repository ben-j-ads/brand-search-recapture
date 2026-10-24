# Branded Search Incrementality

People search your brand name and click your ad. Some of them would have bought anyway through the normal search result. This page takes five plain numbers and tells you whether your brand ads are paying for themselves.

Open `index.html` in any browser. No build step, no dependencies, no network calls.

- **Verdict:** whether the brand ads pay off at the share you enter.
- **Shows:** what the brand ads cost, the profit after that cost, and the share of buyers who must be new for the ads to break even.
- **Arithmetic:** cost = clicks x cost per click. Break-even share = cost / (sales x profit per sale). The full formulas are on the page.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

The share who would have bought anyway is a guess until you test it. Default is 50%. Example figures are made up.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
