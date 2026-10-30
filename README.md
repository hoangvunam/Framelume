# Framelume

Crop, clean up and watermark your photos and videos, right on your Mac.

**[Download Framelume 1.0](https://github.com/hoangvunam/framelume/releases/download/v1.0/Framelume-1.0.zip)** (4 MB) · [all releases](https://github.com/hoangvunam/framelume/releases)

Unzip and drag **Framelume.app** to Applications. The app is signed with Developer ID and notarized by Apple, so it opens without a Gatekeeper warning.

## What it does

- **Crop and straighten.** Drag the crop frame on the picture, pick a ratio (square, 16:9, 4:5, 3:2 and more) or type your own. Straighten, fix perspective, flip. Auto finds the horizon for you.
- **Remove dust and objects.** Paint over a dust shadow, a logo or a sticker. Photos are fixed with Lighten, Fill or the LaMa AI model; videos with the ProPainter AI model, and the mask can track a moving object.
- **Watermark.** Text or a logo, placed and sized on the preview, with font, colour, background, corner radius and opacity.
- **Metadata.** View and edit Exif, IPTC, TIFF and GPS for images or the tags of a video, or strip everything before sharing.
- **Many files at once.** Edit one file, save the steps as a preset and apply them to a whole batch, then export them all in one go.

Everything runs on your Mac with Core Image, AVFoundation, Vision and Core ML. No account, no uploads. Exports land next to the original under a new name, so the original is never lost.

## System requirements

- macOS 13 Ventura or later.
- AI object removal for photos: a one-time download of the LaMa model (about 190 MB) from Settings › Object Removal.
- AI object removal for video (optional): a one-time setup from Settings › Object Removal that installs ProPainter and PyTorch (about 1.5 GB). Needs Python 3.10 or later on the Mac; 16 GB of RAM is recommended. ProPainter is licensed under NTU S-Lab 1.0, for non-commercial use only.

## Tiếng Việt

Framelume là ứng dụng macOS để cắt, nắn, xoá vết bụi và vật thể (bằng AI), đóng dấu watermark và sửa metadata cho ảnh lẫn video, chỉnh nhiều file một lúc bằng preset. Mọi xử lý chạy trên máy bạn. Tải bản mới nhất ở mục [Releases](https://github.com/hoangvunam/framelume/releases), giải nén rồi kéo **Framelume.app** vào thư mục Applications. Cần macOS 13 trở lên.

---

This repository only hosts the app downloads. SHA-256 of Framelume-1.0.zip: `09a8994cf07d0d2bbb25591e1d371d0f37e62e6ad1542bc74dfdc2acf1d68165`
