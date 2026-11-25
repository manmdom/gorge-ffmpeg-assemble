# Gorge FFmpeg Assemble

One-command storyboard -> MP4 with Ken Burns motion, xfade transitions, ducked BGM,
ASS captions, two-pass loudness normalisation and H.264/AAC output.

`--bgm auto` uses `make_bgm.py`; `--bgm none` disables music. Requires ffmpeg with libass,
Pillow, NumPy and optionally edge-tts.
