# SAMP game cache

This repository is consumed by the Android launcher. Each channel has a
`files.json` manifest and one ZIP archive per game file under `cache/`.

Use `../tools/build-cache.py` from the launcher repository to generate the
channel contents. Do not put credentials in this repository; the launcher
downloads the public cache anonymously.