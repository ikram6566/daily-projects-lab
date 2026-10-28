# DEMO — hallmark mirror works

Run on 2026-10-28 from this copied folder (no changes to the original scripts):

```
node skills/hallmark/scripts/sloplint.mjs /tmp/demo-page.html
```

Sample page: a tiny shop page ("Fresh bread, baked today", one order button).

Result: `sloplint: 2 FAIL, 2 REFLEX, 1 WARN across 1 file(s).`

- FAIL: no `:focus-visible` styling; no `overflow-x: clip` on html/body
- REFLEX: no `:active` / `:disabled` styling
- WARN: missing meta description

This is the expected behaviour — the linter caught real issues in the deliberately plain demo page, proving the copied skill scripts run as-is.
