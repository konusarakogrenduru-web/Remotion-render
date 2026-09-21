# Wool Omnibus — Hugh Howey  ·  _science-fiction_

> Bu kitabın **hub klasörü**. Kitaba dair her şey (config, meta, prompt, upload pack) burada; render çıktıları `public/` ve `out/` altında, aşağıda linkli.
> Meta durumu: **claude-hand-refined** ✓

## Dosyalar

| | Konum | Not |
|---|---|---|
| 🎬 Final video | `out/wool-omnibus.mp4` _(yok)_ | render çıktısı |
| 🖼️ Thumbnail | [`out/thumbnail-wool-omnibus.png`](../../out/thumbnail-wool-omnibus.png) | YouTube kapak |
| 📝 YouTube pack | [`books/wool-omnibus/youtube.md`](youtube.md) | başlık/açıklama/tag/bölümler |
| 💬 Captions (CC) | [`public/captions/wool-omnibus.clean.vtt`](../../public/captions/wool-omnibus.clean.vtt) | YouTube'a "With timing" yükle |
| 💬 Captions (ham) | [`public/captions/wool-omnibus.vtt`](../../public/captions/wool-omnibus.vtt) | kelime-zamanlı (karaoke kaynağı) |
| 🎙️ Audio | [`public/audio/wool-omnibus.m4a`](../../public/audio/wool-omnibus.m4a) | NotebookLM sesi |
| 🖼️ Scene images | [`public/scenes/wool-omnibus/`](../../public/scenes/wool-omnibus) | Flux görselleri |
| ✍️ NotebookLM prompt | [`books/wool-omnibus/prompt.notebooklm.md`](prompt.notebooklm.md) | orijinal analiz açısı |
| 📖 Manifest | [`books/wool-omnibus/book.json`](book.json) | book.json (slug/başlık/engine) |
| ⚙️ Vox config | [`books/wool-omnibus/config.vox.json`](config.vox.json) | render config (beats/captions) |
| ⚙️ YouTube meta | [`books/wool-omnibus/youtube-meta.json`](youtube-meta.json) | SEO/meta + thumbnail brief |
| 🎞️ Render chunks | `out_Vox-wool-omnibus_chunks/` _(yok)_ | ara mp4 parçaları + parts.txt |

## Yükleme sırası
1. `out/wool-omnibus.mp4` yükle
2. Başlık + açıklama (bölümler tıklanabilir olur) + tag → [youtube.md](youtube.md)
3. Thumbnail → `out/thumbnail-wool-omnibus.png`
4. CC → `wool-omnibus.clean.vtt` ("With timing")
5. **Altered content = Yes** (sentetik ses)

## Yeniden üretmek
```bash
node scripts/make-book.js --slug=wool-omnibus --title="Wool Omnibus" --author="Hugh Howey" --genre=science-fiction
```
