# PF2e Spell Helper

Search, filter and rate Pathfinder Second Edition spells by class, tradition, rank, category and how you can get them.

**Try it:** https://madilloman.github.io/PF2e-Spell-Helper/

> ⚠️ This is a beta prototype. Expect rough edges, and please report anything that looks wrong.

## Feedback

- **Found a bug?** [Report a bug](https://github.com/Madilloman/PF2e-Spell-Helper/issues/new?template=bug_report.yml)
- **Spell data looks wrong?** [Report a data problem](https://github.com/Madilloman/PF2e-Spell-Helper/issues/new?template=data_error.yml)
- **Have an idea?** [Suggest a feature](https://github.com/Madilloman/PF2e-Spell-Helper/issues/new?template=suggestion.yml)

A free GitHub account is needed to open an issue.

## Key features

### Browse
Pick a **class** (or Any) and the app fills in that class's spell tradition. Classes with more than one tradition, such as the sorcerer or witch, start with none selected so you can choose. Set a rank range, search spell names (including pre-remaster names) and descriptions, and sort results by rating, rank or name. By default results are sorted by rating, high to low, with higher-rank spells first on ties.

- **Subclass and domains:** A subclass filter appears under Class with the right label for each class (Bloodline, Arcane School, Patron, Mystery, Muse, Druidic Order and so on). Choosing one hides focus spells that only other subclasses get, and sets the tradition when the subclass fixes it. Clerics, champions and oracles also get a multi-select **Domains** filter.
- **Spell ratings:** Each spell shows a rating out of 5 stars with a reason for the rating. When a class is selected, class-specific notes can raise or lower the rating, and they appear on their own line. A **Spell rating** filter narrows results to 5 through 1 stars or unrated.
- **Spell categories:** Buff, Single-target damage, Area damage, Debuff, Control, Healing, Protection, Utility, Stealth, Detection, Traversal, Summon and Wall. A spell can have several categories.
- **Alternative spell source:** Find spells you can get from a feat, a class feature or choice, an ancestry, heritage or background, an item, a ritual, an archetype-only focus spell, or a legacy option with no remaster source.
- **Spell properties:** Filter by casting time, duration, targets, range, area, traits, heightening, damage type and conditions imposed.
- **More filters:** Spell type (cantrip, spell, focus, ritual), defense (Fortitude, Reflex, Will or AC, basic or not), whether the spell can be modified by a feat or item, rarity, content (Remaster or Legacy) and source book. Each filter can include or exclude values.
- **Hide spells:** Hide any spell you don't want to see again. Hidden spells have their own tab, where you can restore them.

### Saved Spell Lists
Save spells to named lists, such as spells to learn at your next level or a list for each character. Click the list icon on a result card to add the spell to one or more lists or start a new one. The Saved spell lists tab shows each list sorted by rank. Lists can be renamed, deleted, exported to a file and imported. They are stored in your browser.

### Presets and sharing
Save your current filters as a named preset, or copy a share code that someone else can paste in to load the same filters.

### Spell details
Result cards show rank, traits, traditions, casting time, range, area, targets, defense, duration, heightened effects and the source book, plus a link to the spell's entry on Archives of Nethys. Expanded cards also show:

- **Granted by:** the feats, class features, ancestries, backgrounds and items that give you the spell.
- **Requires:** shown when a feat is the only way to get the spell.
- **Modified by:** feats and items, such as spell catalysts, that change how the spell is cast.
- **Formerly:** the pre-remaster name of a remastered spell.

Hover over any of these names to see their description.

## How it works

The whole app is a single self-contained page (`index.html`) that runs in the browser. It has no server, account or tracking. Saved spell lists and presets stay in your own browser.

Spell data is a snapshot as of 11/16/2026 from the open-source [Foundry VTT PF2e System](https://github.com/foundryvtt/pf2e). Categories, conditions and sources are assigned by text matching with some manual corrections, so there may be edge cases where they do not align with the spell; check the [Archives of Nethys](https://2e.aonprd.com/) link to confirm spell details. Ratings are opinions, not official rules.

## Legal

See [NOTICE.md](NOTICE.md).

PF2e Spell Helper uses trademarks and/or copyrights owned by Paizo Inc., used under Paizo's Community Use Policy ([paizo.com/licenses/communityuse](https://paizo.com/licenses/communityuse)). We are expressly prohibited from charging you to use or access this content. PF2e Spell Helper is not published, endorsed, or specifically approved by Paizo. For more information about Paizo Inc. and Paizo products, visit [paizo.com](https://paizo.com).
