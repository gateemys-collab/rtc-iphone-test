# Fonts

| font | used for | how | licence |
|---|---|---|---|
| Fusion Pixel Font 12px proportional zh_hans (TakWolf, https://github.com/TakWolf/fusion-pixel-font) | all Chinese UI labels | rasterised **once at build time** by `tools/make-ui.py` into 1-bit PNGs (`public/assets/ui/text/`); the font file itself is **not** shipped in `dist/` | SIL Open Font License 1.1 — `LICENSES/fonts/fusion-pixel-OFL.txt` |
| Noto Sans CJK Bold (Google/Adobe) | 「请横屏游玩」 rotate hint (step 1, `tools/make-rotate-hint.py`) | rasterised once into `public/assets/ui/rotate-hint.png` | SIL Open Font License 1.1 |

The font copy at `tools/fonts/` is a build-time tool input (copied from `../art/_work/fonts/f12/`).
