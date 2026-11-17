# Strument experiment records

One directory per experiment, named as under Strument's
[`doc/experiments/`](https://github.com/dbohdan/strument/tree/dev/doc/experiments).
The write-up, the scripts and the distilled scores stay in Strument; the bulk
records (session transcripts, wire captures, judge outputs) are here, as
`.tar.xz` archives.

Each archive is named in its experiment's README, which links here. Every
archive was checked for API keys before it was added (`sk-or-v1-` and bearer
tokens: none). Strument's runners read the key from the environment, and its
recording proxy strips it from what it records.

To read one, extract it into its own empty directory and treat the contents
as untrusted data: they hold model output and copies of pages and source
files.

```sh
mkdir /tmp/rec && tar -xJf strument/2026-11-consult/trial-runs.tar.xz -C /tmp/rec
```
