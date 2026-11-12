# GHL snippet: Starfighter Financial (starfighterfinancial.com)

GHL: sub-account **Starfighter Financial LLC** → Sites → Websites → Starfighter Financial → Home → the one Custom HTML/Javascript element.

The element holds a static copy of `embed.html` (so search engines and AI crawlers see the full text) wrapped like this:

```html
<div id="sf-fin-root" data-v="1">
  …contents of embed.html…
</div>
<script src="https://mylaunchpartner.github.io/starfighter-financial/loader.js" data-root="sf-fin-root"></script>
```

## Making a change
1. Edit `embed.html` here and bump `v` in `version.json`. Visitors get the new version within ~5 minutes (the loader swaps it in).
2. If the change matters for Google (copy, headings, links, phone/contact), re-paste the wrapped block above into GHL with `data-v` set to the new version, and Publish.
