# String.raw description trial, pilots, 2026-11-18

Raw records for Strument's `doc/experiments/2026-11-string-raw`.

`pilots.tar.xz` holds `pilot/` (line tasks and the csv counter-metric) and
`pilot2/` (block tasks), one directory per session: `done.json`, `stdout.txt`,
`stderr.txt`, `wire.jsonl` (every request and response, through strumentrec),
the session log, `state/` (the session store, blobs included) and `proj/` (the
fixture as the session left it, without its `.git`). Also the runner's logs.
Checked for API keys before committing.

`await-check.tar.xz`: the follow-up live check of top-level `await` (18 MiMo sessions on the block tasks, Strument at `adb92bb`), in the same layout.
