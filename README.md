# Soshiotsuki Feed

The newest secondhand Soshiotsuki listings from resale shops, in one page.

**Live at https://soshiotsuki.hengecorp.com** (feed: https://soshiotsuki.hengecorp.com/feed.xml)

This is one of a family of feeds (Rick Owens, Kiko Kostadinov, Helmut Lang, 205W39NYC, Soshiotsuki) that share one engine.
The code, the look (`themes/soshiotsuki.css`) and **this feed's shop list (`brands/soshiotsuki.json`) live in
[olekpachecodul/rickfeed](https://github.com/olekpachecodul/rickfeed)**. Change them there; this repo picks the change up on its next run.

What's here:
- `.github/workflows/feed.yml`: checks the shops up to every 15 minutes and republishes the page.
- `data/state.json`: what's already been seen (created and updated automatically).

Run it now: Actions tab → Soshiotsuki Feed → Run workflow.
