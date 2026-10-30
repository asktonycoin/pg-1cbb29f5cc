# How to swap client logo + name

Open `index.html` and edit the CONFIG block near the top of the `<script>`:

```js
const CONFIG = {
  clientName: "Acme Labs",
  logoUrl: "logo.jpg",   // put logo.jpg next to index.html, or use a full https URL
  accent: "#5fa8a0",     // optional brand accent
  accentDeep: "#3d7a74",
  ...
};
```

1. Replace `clientName` with the company name.
2. Drop their logo file beside `index.html` as `logo.jpg` (or `.png`) and set `logoUrl` to that filename.
3. Optionally change `accent` / `accentDeep` to their brand colors.
4. Push / refresh the GitHub Pages link.

Leave `logoUrl: ""` to keep the dashed "Client logo" placeholder.

Steppas mark in the nav is `steppa-mark.png` (not the client logo).
