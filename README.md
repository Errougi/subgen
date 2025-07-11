# 🖥️ Subgen

> `Subgen` is a CLI tool for generating subtitles for your video/audio files.

---

## 📌 Command: `subcut gen`

Generate subtitles using `faster-whisper`.

```bash
py subgen.py <video.mp4> [--language <lang>] [--model <model>] --output <subs.vtt>
```

Example:

```bash
 py subgen.py ./samples/jfk.wav -m base ./samples/jfk.vtt
```

### Options:

- `--output`: Destination `.vtt` file path
- `--language`: (Optional) language code (e.g. `en`, `fr`, `ar`)

---

### Description:

- Automatically applies:
  - Resolution/aspect ratio from template
  - Subtitle position/styling from template
- Shortcut for creating platform-ready exports
