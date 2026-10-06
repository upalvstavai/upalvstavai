# Hi, I'm Ivan 👋

I debug **Godot 3.x and 4.x** projects. I reproduce one concrete problem, trace its cause, make a focused fix, and provide tests or clear verification evidence.

## What I work on

- gameplay and state bugs
- input, camera, UI, and scene lifecycle problems
- saves, resources, and data validation
- performance regressions and runaway background work
- small, reviewable fixes for existing Godot projects

## Public results

So far, maintainers have merged **6 fixes across 3 open-source projects**.

- [Civic Nightmare #113](https://github.com/Daniele-Cangi/civic-nightmare/pull/113) — repaired a stale texture UID that broke import and loading
- [Civic Nightmare #114](https://github.com/Daniele-Cangi/civic-nightmare/pull/114) — added coverage for corrupt and incompatible save data
- [Civic Nightmare #115](https://github.com/Daniele-Cangi/civic-nightmare/pull/115) — added validation for character dialogue data
- [Civic Nightmare #116](https://github.com/Daniele-Cangi/civic-nightmare/pull/116) — added and tested a missing C.L.A.U.D.I.A. callback
- [Mad Productivity #42](https://github.com/Mad-Cookies-Studio/mad-productivity/pull/42) — fixed timer state surviving pause, finish, and restart
- [ReSun #489](https://github.com/ReSun-Developers/ReSun/pull/489) — stopped production after the final supporting factory disappears

> “Clean, focused changes with solid tests.” — [Civic Nightmare maintainer](https://github.com/Daniele-Cangi/civic-nightmare/pull/116#issuecomment-6017266970)

## How I handle a project

I work in an isolated copy, keep changes small and reviewable, and never push to the original repository without permission. A useful first report includes the exact Godot version, expected and actual behavior, reproduction steps, and relevant logs with secrets removed.

## Contact

- Open a conversation through my [Godot debugging thread on itch.io](https://itch.io/t/7066332/godot-free-i-will-diagnose-and-fix-one-reproducible-bug-in-3-small-projects)
- Contact me through [GitHub](https://github.com/upalvstavai)

AI-assisted workflow; reproduction, diffs, and test results are reviewed before delivery.
