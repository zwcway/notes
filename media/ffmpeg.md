## 生成音频频谱
```
ffmpeg -i input.aac -filter_complex "showwavespic=s=640x120" -frames:v 1 output.png
```
