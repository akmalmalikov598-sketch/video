# CODE2VIDEO AI

HTML/CSS animatsiya yoki rasmdan ovozli MP4 video yaratish (Flask + Playwright + FFmpeg + Edge TTS).

## Deploy (Render)
1. Papkani GitHub repo'ga push qiling.
2. Render: New -> Blueprint (yoki Web Service), repo'ni ulang. Runtime: Docker.
3. Deploy tugagach URL'ni oching.

## Lokal ishga tushirish
Docker bilan: `docker build -t code2video . && docker run -p 10000:10000 code2video`
