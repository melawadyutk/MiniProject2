# Reflection: pytorch_audio

- Commits (WoC): 15856, authors: 1513
- Activity pattern: irregular; gaps of 3+ months: 0
- Longest gap: 2017-11 to 2017-11 (1 months); recovered: Yes
- Current status: Active (last GitHub commit 2026-09-23)

torchaudio has been continuously active since 2017 (15,856 WoC commits by 1,513 authors). Its longest gap is just one month in 2017 and there are no gaps of 3+ months.
The overall pattern is irregular. Tiny until 2019, a big rise and plateau in 2020-2022 (about 3,000 commits a year) once Meta engineers maintained it, a drop to 635 in 2024, a spike in mid-2025, and low activity again.
The 2025 spike was easy to interpret from the commit messages: "Add load_with_torchcodec", "Remove io tutorials", removals of deprecated features by a few Meta engineers. torchaudio moved its audio I/O to TorchCodec and slimmed down, which matches the drop in activity since.
The one-month 2017 gap needs no special explanation. It was an early-stage project and the same people continued afterwards (61% returning authors in the next 12 months).
