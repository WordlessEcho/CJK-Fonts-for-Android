# CJK Fonts for Android
**WIP**
A tool create a curated subset font for Android.

## Installation
Install [patched nototools](https://github.com/WordlessEcho/nototools).

## Usage
Put `NotoSansCJK-Regular.ttc` (edit the bottom line of subset_noto_cjk.py for another file name) in the same directory of subset_noto_cjk.py

Then (or python3 on Ubuntu/Debian):
```bash
python subset_noto_cjk.py
```

You will got a edited font in `output`.

## Known issue
- Output file name might be wrong.
- Index order may changed.
