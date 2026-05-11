# 🎨 ColorLens — Color Palette Extractor

An interactive browser-based tool for extracting, analyzing and replacing colors in any image. No backend, no dependencies — runs entirely in the browser.

## ✨ Features

- **Palette Extraction** — upload any image and instantly get its dominant color palette with color names, HEX and RGB codes, and percentage distribution
- **Color Replace** — select any color from the palette and replace it with a new one using HSL-based algorithm for natural, smooth results
- **Live Preview** — changes update in real time as you adjust tolerance and opacity
- **HEX Input** — enter a color manually by HEX code or use the color picker
- **Tolerance & Opacity** — fine-tune the replacement range and blend strength
- **Color Distribution Chart** — visual bar chart showing percentage of each color in the image
- **Export Options** — download the edited image, download the palette as PNG, or copy colors as CSS variables

## 🖼️ Preview
![Preview](thumbnail.png)

## 🚀 How to use
1. Drop an image or click to upload
2. Explore the extracted color palette on the right
3. Click **Replace** on any color to open the replace panel
4. Pick a new color via color picker or type a HEX code
5. Adjust Tolerance and Opacity — preview updates live
6. Click **Download Image** to save the result

## 🛠️ Built with
- HTML5 Canvas API
- Vanilla JavaScript — HSL color space for natural color replacement
- CSS3