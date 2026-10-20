---
"@vskstudio/takt-vue": minor
---

Support `@vskstudio/takt-core` 0.12. `<Takt>` and `TaktPlugin` accept `redactUndecodablePaths` (default `true`: a path that cannot be decoded is masked as `/[redacted]`; `false` decodes it leniently). `<takt-analytics>` gains the `redact-undecodable-paths` and `file-extensions` attributes. The package root re-exports `normalizeHost`, `TrackOptions` and `Payload`, and `./directives` re-exports `InitOptions`. The peer dependency is raised to `@vskstudio/takt-core` 0.12.0, which accepts the brace and `<regex>` route syntaxes. Minor bump: new public options and a raised peer range.
