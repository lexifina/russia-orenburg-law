<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Orenburg Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:53 UTC, Orenburg Oblast: Official Internet Portal of Legal Information (region56): 14 addresses read; 2 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Orenburg Oblast: Official Internet Portal of Legal Information (region56)](http://publication.pravo.gov.ru/documents/block/region56) | `zakony-<year>/` | daily | 2026-11-28 05:53 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:52](checks/2026-11.md#ru-pravo-orenburg-20261128t055214z) | pravo-orenburg | 14 | 2 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-orenburg-law/compare/07e85fd36f17...3360ed1d7c10) |
| [2026-11-27 05:43](checks/2026-11.md#ru-pravo-orenburg-20261127t054336z) | pravo-orenburg | 14 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:47](checks/2026-11.md#ru-pravo-orenburg-20261126t054735z) | pravo-orenburg | 14 | 5 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-orenburg-law/compare/c48add10313f...4f7c14d7b8f2) |
| [2026-11-25 06:22](checks/2026-11.md#ru-pravo-orenburg-20261125t062215z) | pravo-orenburg | 14 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:23](checks/2026-11.md#ru-pravo-orenburg-20261124t142337z) | pravo-orenburg | 14 | 41 | 0 | 0 | 0 (0) | changes found | [3](https://github.com/lexifina/russia-orenburg-law/compare/a36be6a6f1ec...8db2375be90f) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
