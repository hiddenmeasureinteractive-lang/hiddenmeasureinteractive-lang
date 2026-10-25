# Hidden Measure Interactive

We build independent games and practical open-source tools for Godot developers.

Our tools grow out of problems we encounter during development: preparing a game for more languages, reviewing changes, and catching mistakes before they reach players. We favor local workflows, readable reports, and small changes that developers can inspect.

## Godot Localization Audit

[**Explore the project →**](https://github.com/hiddenmeasureinteractive-lang/godot-localization-audit)

A local command-line tool for reviewing localization in an existing Godot game:

- Find strings that need a closer look, with file locations and reasons.
- Propose `tr()` wrappers for display functions you explicitly select.
- Catch translation placeholder mismatches in CSV catalogs.
- Use readable reports or JSON with your editor and coding tools.

The first release is an **early preview**. It does not modify project files automatically or replace Godot's localization system. Python 3.10+, MIT licensed, no accounts or API keys required.

[English documentation](https://github.com/hiddenmeasureinteractive-lang/godot-localization-audit#readme) · [Türkçe kullanım](https://github.com/hiddenmeasureinteractive-lang/godot-localization-audit/blob/main/docs/README.tr.md)

## Help improve it

Found a string it misclassifies or a useful workflow it misses? Share a small, synthetic example in the [issue tracker](https://github.com/hiddenmeasureinteractive-lang/godot-localization-audit/issues). Reproducible bug reports, documentation fixes, and feedback from real projects are welcome.

We are also developing **MISLEARN**, an independent Godot game. Game development informs these tools; proprietary game content is kept separate from the public repositories.
