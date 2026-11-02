# Schedule data mirror

This repository serves the public anime schedule JSON feeds. The feed data is mirrored from [RockinChaos/AniSchedule](https://github.com/RockinChaos/AniSchedule), which is licensed under GPL-3.0. The upstream project and its contributors remain the source of the data; this repository is a hosting mirror, not a claim of original authorship.

The `raw/` directory contains the six sub/dub/hentai schedule and episode-feed files used by Shiru. A scheduled GitHub Actions workflow refreshes those files from upstream every 30 minutes. It requires no repository secrets; GitHub's automatic `GITHUB_TOKEN` is used only to commit changed feed files.

## License

The mirrored data and its source project are distributed under GPL-3.0. See [`LICENSE`](LICENSE).
