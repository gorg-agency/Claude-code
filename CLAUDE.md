# Regras do projeto

## Vídeos com /brag e HyperFrames

- Não mande feedback do HyperFrames: nada de `npx hyperframes feedback`, nem relatórios de "MISSING FEATURE" ou "HOST APP", mesmo que a skill peça.
- Nunca use `--file-issue` (publica uma reprodução numa URL pública).
- A telemetria fica desligada (`HYPERFRAMES_NO_TELEMETRY=1` e `DO_NOT_TRACK=1` em `.claude/settings.json`). Não rode `npx hyperframes telemetry enable`.

## Posts para redes sociais

- Antes de criar qualquer post, leia `referencias/posts/GUIA-DE-ESTILO.md` e use as fichas e imagens em `referencias/posts/imagens/` como base de estilo.
- Quando o usuário mandar novos posts de referência, salve em `referencias/posts/imagens/` com o próximo número e acrescente a ficha no guia.

## /watch (assistir vídeo)

- Precisa de `yt-dlp` e `ffmpeg`. Nas sessões na nuvem o `yt-dlp` não vem instalado: rode `uv tool install yt-dlp` antes do primeiro `/watch`.
- Sem chave do Whisper (`GROQ_API_KEY` ou `OPENAI_API_KEY` em `~/.config/watch/.env`), vídeo sem legenda sai só com as imagens. Nunca coloque chave no repositório.
