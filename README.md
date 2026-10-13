# Hi, I'm Ivan 👋

I debug **Godot 3.x and 4.x** projects. I reproduce concrete problems, trace their causes, make focused fixes, and provide tests or clear verification evidence.

## What I work on

- gameplay, state, input, camera, UI, and scene lifecycle bugs
- editor plugins, resources, saves, and data validation
- physics edge cases, performance regressions, and runaway background work
- small, reviewable fixes for existing Godot projects

## Public results

Maintainers have merged **15 fixes across 9 open-source projects**. You can verify the [complete merged PR list](https://github.com/search?q=author%3Aupalvstavai+is%3Apr+is%3Amerged&type=pullrequests).

### Engine, editor, and plugin fixes

- [Godot Rapier Physics #650](https://github.com/appsinacup/godot-rapier-physics/pull/650) — fixed shared-resource `Shape2D` collision queries that could panic in the Rust backend
- [Cyclops Level Builder #257](https://github.com/blackears/cyclopsLevelBuilder/pull/257) — removed stale vertex, edge, and face edit gizmos from the 3D viewport
- [Godot Open World Database #23](https://github.com/DigitallyTailored/Godot-Open-World-Database/pull/23) — stopped a terrain regeneration feedback loop that froze the editor
- [Tau Plot #57](https://github.com/ze2j/tau-plot/pull/57) — made collapsed-domain coordinate mapping consistent across axes and inversion modes

### Gameplay and application fixes

- [Mad Productivity #42](https://github.com/Mad-Cookies-Studio/mad-productivity/pull/42) — fixed timer state surviving pause, finish, and restart
- [ReSun #489](https://github.com/ReSun-Developers/ReSun/pull/489) — stopped production after the final supporting factory disappears
- [Zombie Apocalypse #71](https://github.com/DewaldOosthuizen/zombie-apocalypse/pull/71) — repaired Godot 4 tween callback regression tests

### HammerForge fixes

- [#985](https://github.com/saworbit/hammerforge/pull/985) — stopped dock binding from overwriting bake settings
- [#986](https://github.com/saworbit/hammerforge/pull/986) — preserved every bake option through settings export and import
- [#987](https://github.com/saworbit/hammerforge/pull/987) — fixed spawn validation inside solid brushes
- [#988](https://github.com/saworbit/hammerforge/pull/988) — protected related cordon metadata from inconsistent Inspector edits

### Civic Nightmare fixes

- [#113](https://github.com/Daniele-Cangi/civic-nightmare/pull/113) — repaired a stale texture UID that broke clean imports
- [#114](https://github.com/Daniele-Cangi/civic-nightmare/pull/114) — added coverage for corrupt and incompatible save data
- [#115](https://github.com/Daniele-Cangi/civic-nightmare/pull/115) — added validation for character dialogue data
- [#116](https://github.com/Daniele-Cangi/civic-nightmare/pull/116) — added and tested a missing C.L.A.U.D.I.A. callback

> “Clean, focused changes with solid tests.” — [Civic Nightmare maintainer](https://github.com/Daniele-Cangi/civic-nightmare/pull/116#issuecomment-6017266970)

> “A well-diagnosed fix… Great catch.” — [Godot Open World Database maintainer](https://github.com/DigitallyTailored/Godot-Open-World-Database/pull/23#issuecomment-6058862750)

## How I handle a project

I work in an isolated copy, keep changes small and reviewable, and never push to the original repository without permission. A useful first report includes the exact Godot version, expected and actual behavior, reproduction steps, and relevant logs with secrets removed.

## Contact

- Open a conversation through my [Godot debugging thread on itch.io](https://itch.io/t/7066332/godot-free-i-will-diagnose-and-fix-one-reproducible-bug-in-3-small-projects)
- Contact me through [GitHub](https://github.com/upalvstavai)

AI-assisted workflow; reproduction, diffs, and test results are reviewed before delivery.
