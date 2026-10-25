# Peeking animation demo

A blank white page using the public widget embedded in https://liquid-glass.ybouane.com/.

Character animation and widget: ybouane, https://peeking.ybouane.com/.
The script and both transparent video formats are served locally. Video bytes are preserved from the original source without re-encoding. WebM (VP9) is used in Chromium, with HEVC alpha for Safari.

Quality changes: render all canvas surfaces at the source video's 890 x 1340 resolution, use high-quality image smoothing, remove the original canvas DPI cap, and increase the responsive character size. Original footage is 30 fps; no additional source detail or interpolated frames are claimed.

The initial appearance starts after 1.2 seconds. The character repeats idle peeks and responds to hover/tap. Analytics are disabled. Automatic animation is disabled when reduced motion is requested.

Preview: `python3 -m http.server 8766 --directory dist`.
