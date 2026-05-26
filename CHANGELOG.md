# Changelog

All notable changes to the Professional Hater skill are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project uses [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2026-05-27

### Added
- **Big-sister wisdom register** layered onto the existing catty persona. New voice mode for moments that turn serious: direct, lived-through, "I've been here, here's what I wish someone had told me", picks a lean when asked, hands the user the actual play in plain words. Sits underneath the catty wrapper; never replaces it. The skill can be wise and catty in the same breath.
- **Five operational modes** documented in SKILL.md, each with its own mechanic cheat-sheet:
  - Venting / processing mode (original; now explicitly named as the default).
  - Practical navigation mode — "how do I handle this." Concrete plays for relationships, conflict, work, family, friendships.
  - Decision support mode — "should I." Names the real question under the surface question, runs weighted pros/cons, future-you check, body check, honest lean on request.
  - Script / rehearsal mode — "what do I say." Drafts in 2-3 register options (soft / firm / scorched-earth-but-classy), structures with DEAR MAN, rehearses likely derailments.
  - Decoder mode — "what did this mean." Reads literal + subtext, names patterns, gives honest read with confidence indicator, hands off to action.
- **Five practical-navigation domain references** (new knowledge banks):
  - `references/relationship-navigation.md` — repair, the "where is this going" talk, three kinds of breakups, jealousy work, dating with attachment awareness, stay/leave decision criteria.
  - `references/conflict-resolution.md` — soft start-up, repair attempts, proper apologies (Lerner-style), receiving apologies, conflict vs. incompatibility, walking away mid-conflict.
  - `references/workplace-dynamics.md` — managing up, credit theft, pushback formula, document/escalate/leave decision tree, bad-manager survival, salary negotiation, when to quit.
  - `references/family-dynamics.md` — low-contact vs. no-contact, enmeshment unwinding, "I love you AND" play, holiday survival planning, parentification recovery, grief over family.
  - `references/friendship-navigation.md` — slow fade vs. direct conversation, asymmetric friendships, friend breakups, adult friend-making, group politics, the missing-stair friend.
- **Four mode-mechanic references** (one per non-default mode): `mode-practical-navigation.md`, `mode-decision-support.md`, `mode-script-rehearsal.md`, `mode-decoder.md`.
- **Expanded trigger phrases** in SKILL.md frontmatter and trigger section, organized by mode. Practical-navigation, decision-support, script, and decoder triggers added alongside the original venting/processing triggers.

### Changed
- Skill description in frontmatter expanded to surface practical-navigation and big-sister wisdom capabilities for trigger matching.
- "What this skill does" section in SKILL.md rewritten to name both halves explicitly: feelings processing + practical navigation.
- Conversation flow now branches at step 5 between "one small next move" (default) and offering to enter practical / decision / script / decoder mode when the situation calls for it.

### Unchanged (intentionally preserved)
- Sticky persona, pet-name rotation, crisis protocol (still drops voice fully including new big-sister register on safety signals), hard rules (no diagnosis, no licensed-therapist claims, no revenge with blowback, no body-shaming / slurs / -isms, no unprompted moralizing, no rushing).
- All 14 original therapeutic-grounding references untouched.
- README burn-book voice and Regina-coded narration retained; updated only to surface the new modes, the big-sister layer, and the expanded trigger list.

## [0.1.0] - 2026-05-23

### Added
- Initial release.
- Full mean-girl-best-friend persona (glamorous, sharp-tongued, ride-or-die loyal, always on the user's side, never on the antagonist's).
- Sticky persona: voice persists across the whole conversation until the user explicitly opts out.
- Pet-name rotation throughout responses ("bestie", "sis", "babe", "hun", "girl", "queen", "doll", "love", "honey") with no-repeat-in-a-row guidance.
- Conversation flow: invite to spill → validate first → drag the antagonist with specificity → name what's actually happening underneath → offer ONE next move → check in on what the user needs (harder, softer, or just listening).
- Crisis protocol: full voice-drop (pet names included) on signals of self-harm, suicidal ideation, active abuse, or acute safety threats. Direct clinical-care mode with hotline / resource surfacing until the user is stable and explicitly wants the voice back.
- Hard rules: never diagnose, never claim to be a licensed therapist, never encourage revenge with real-world blowback to the user, no body-shaming, no slurs, no -isms, no unprompted moralizing, no rushing the process, one next move at a time.
- 14 reference cheat-sheets in `references/`, each scoped to one framework with in-voice usage examples and "when NOT to use this" guidance:
  - **Core emotional support:** grief-stages (Kübler-Ross 5 + extended 7), cbt-distortions, attachment-styles, polyvagal-and-window-of-tolerance, ifs-parts-work, self-compassion, anger-as-secondary, radical-acceptance, rumination-interrupts.
  - **Relationship and antagonist patterns:** gottman-four-horsemen, narcissistic-abuse-patterns, cycle-of-abuse, boundaries-vs-walls, dbt-dear-man.
- Trigger phrases for natural-language invocation in addition to the slash command, including "I need to vent", "be mean about [person] for me", "I'm grieving", "help me process this", "I hate [name] right now", "I'm spiraling", "I just need to be told I'm right", "tell me I'm not crazy", "drag him for me", "I can't stop thinking about what they did".
- "Drop the voice" / "switch to normal mode" escape hatch for users who want the support without the theater.

[0.2.0]: https://github.com/lazyfoxjumps/Professional-Hater/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/lazyfoxjumps/Professional-Hater/releases/tag/v0.1.0
