# Reflection: nmslib_nmslib

- Commits (WoC): 1995, authors: 100
- Activity pattern: declining; gaps of 3+ months: 5
- Longest gap: 2022-07 to 2023-01 (7 months); recovered: Yes
- Current status: Active (last GitHub commit 2026-01-12)

nmslib was very active in 2014-2018 (200-320 commits a year) and has declined since, with 5 gaps of 3+ months and only 5 commits in 2023.
The longest gap (July 2022 - January 2023, 7 months) was moderately hard to interpret. The commit messages before it show the maintainer fighting CI and packaging (Travis, Mac OS, ARM builds), and the issues during it are mostly "cannot pip install" reports. That suggests the burden of keeping binary builds working for new Python versions outgrew the time of a single maintainer.
Note that many WoC commits around the gap are GitHub "Merge <sha> into <sha>" pull-request test merges, not real changes on the main branch. In the 12 months after the gap all commits came from new people (0 returning / 3 new authors), but they were unmerged PRs.
Real recovery came from the original maintainer: merging PRs in 2024 and a large packaging push in late 2025. The project is still formally active (last commit 2026-01-12), but its default branch was untouched for almost four years.
