# How to swap client logo + name

Open `index.html` and edit the CONFIG block near the top of the `<script>`:

```js
const CONFIG = {
  clientName: "Acme",
  logoUrl: "logo.jpg",   // or "" for placeholder
  accent: "#ff3d71",     // optional
  accentDeep: "#c8ff3d", // optional
  ...
};
```

Place `logo.jpg` next to `index.html` (or use any https image URL).
