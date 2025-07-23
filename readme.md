# Minecraft Custom Font Resource Pack

## 📥 Download a Font

1. Visit [Google Fonts](https://fonts.google.com/).
2. Choose and download any font that supports your language (e.g. Thai).
3. Extract the `.ttf` file from to `/assets/ratree/font`

---

## ✏️ Modify the Resource Pack

1. Replace or add your font file inside:
`assets/ratree/font/your-font.tff`
2. Edit `default.json` to point to your `.ttf` file:

```json
{
  "providers": [
    {
      "type": "ttf",
      "file": "your-font.tff", <-----
      "shift": [0.0, 1.6],
      "size": 8.0,
      "oversample": 25.0
    }
  ]
}
