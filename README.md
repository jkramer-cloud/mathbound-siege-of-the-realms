# Mathbound: Siege of the Realms — v0.7.1.1

A browser-based fantasy math tower-defense game for the Naches Learning Hub. **This is a development/playtest build**, not yet a fully balanced classroom release.

## Five playable worlds — 50 levels

| World | Name | Focus | Levels |
|---|---|---|---|
| 1 | Emberwood Valley | Addition | 1–10 |
| 2 | Frostbite Pass | Subtraction | 1–10 |
| 3 | Clockwork Dominion | Multiplication | 1–10 |
| 4 | Crystal Depths | Division | 1–10 |
| 5 | Chaos Nexus | Mixed Operations | 1–10 |

## World 5: Chaos Nexus

The realms converge in one final battlefield. Enemies from Emberwood, Frostbite, Clockwork, and Crystal Depths attack together, with the new **Nexus Overlord** in level 10. The operation focus rotates between addition, subtraction, multiplication, and division; later levels introduce two- and three-step expressions with parentheses. Grade selection changes the size, signs, decimal precision and fraction complexity of questions.

**Nexus Harmony:** Answer one of each of the four operations correctly on the first try without a missed question to earn **+35 Spark, +12% Crystal Burst, +3% Heartstone**. There is no answer time limit. A wrong answer or skipped bonus question resets this four-operation sequence, without undoing already-earned Spark.

## Test offline — no repository required

Open `Mathbound_v071_PLAY_OFFLINE.html` in Chrome or Edge. The same self-contained file is also included in the full ZIP. The offline file contains all art and runs without network requests. Do not open the repository `index.html` separately without its `assets` folder.

## GitHub Pages

When you're ready, create a repository (suggested: `mathbound-siege-of-the-realms`). Upload `index.html`, the complete `assets/` directory, and `README.md` from the *GitHub-ready ZIP* at the repository root. Under Settings > Pages choose `main` and `/ (root)`. No external libraries, npm, or API keys are used.

### Controls

- Select a defender with the on-screen cards or keys **1–4**; click an empty highlighted stone tile to deploy.
- **M** starts an extra math challenge for Spark and Burst energy when available.
- **Space** casts Crystal Burst at 100%.
- **P** pauses/resumes.
- Answer questions with multiple-choice or typed answers. Adaptive mode can switch to typed entry at higher levels.

## Saving and privacy

All world records share the original browser-local key `mathbound_emberwood_v01`, preserving previous campaign progress on the *same site/browser*. New World 5 records use `5:1`–`5:10`, without overwriting earlier worlds. Local HTML offline saves do not automatically transfer to GitHub Pages, school-managed Chromebook browser data may be erased, and no cloud synchronization is implemented. No sign-in is required.

## Development validation and limitations

- World 5 includes 10 levels and the new boss spawn.
- Mathematical correctness and distractor uniqueness were checked on 12,500 generated examples (5 difficulty settings × 10 levels × 250 problems).
- The available test environment blocked opening local files as navigation targets, so browser testing used direct HTML loading. Full 50-level manual playthroughs, tuning of wave balance, and classroom Chromebook playtests remain outstanding.
- The Nexus Overlord inherits an earlier Colossus character sprite with a special prismatic aura; a fully original animated boss sprite is a future polish item.
- This preview has no separate save export/import tool; clearing site data will remove progress.

## v0.7.1: Spark clarity and Crystal Burst visual fix

- **No additional guardians.** Leaf Warden remains the Spark producer: costs 95 Spark, first harvest after approximately 4 seconds, then +30 Spark every 11 seconds (higher at permanent upgrade ranks). A bright `+30 SPARK` text effect, collection flare, and small animated crystals flying to the Spark display make it easier to notice.
- Crystal Burst now emits a luminous left-to-right shockwave. Damage is applied as the wave reaches each enemy; enemies are removed by the normal defeat and reward flow, rather than vanishing immediately when Space is pressed.
- Closed lanes remain unavailable at the original campaign levels but now use lighter boundaries and labels instead of broad dark overlays that obscured the battlefield art.
- No changes to enemy schedules, placement rules, math challenge scoring, guardian costs, permanent upgrades, or the original save key. The victory screen waits until a launched Crystal Burst has finished sweeping the field.
- Tested using a headless browser for rendering and the basic Warden/Crystal Burst interactions; full 50-level classroom balancing remains a playtest item.

## v0.7.1: Spark clarity and Crystal Burst visual fix

- **No additional guardians.** Leaf Warden remains the Spark producer: costs 95 Spark, first harvest after approximately 4 seconds, then +30 Spark every 11 seconds (higher at permanent upgrade ranks). A bright `+30 SPARK` text effect, collection flare, and small animated crystals flying to the Spark display make it easier to notice.
- Crystal Burst now emits a luminous left-to-right shockwave. Damage is applied as the wave reaches each enemy; enemies are removed by the normal defeat and reward flow, rather than vanishing immediately when Space is pressed.
- Closed lanes remain unavailable at the original campaign levels but now use lighter boundaries and labels instead of broad dark overlays that obscured the battlefield art.
- No changes to enemy schedules, placement rules, math challenge scoring, guardian costs, permanent upgrades, or the original save key.
- Tested using a headless browser for rendering and the basic Warden/Crystal Burst interactions; full 50-level classroom balancing remains a playtest item.
