# Skils-

Mis skills para Claude. Cada skill vive en `skills/<nombre>/` con su `SKILL.md`.

## Origen de las skills

| Fuente | Skills | Licencia |
|---|---|---|
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 9 (`hyperframes*`, `slideshow`, `figma`, `media-use`, `style-sampling`, `reverse-any-video`, `remotion-to-hyperframes`) | Apache-2.0 |
| [remotion-dev/skills](https://github.com/remotion-dev/skills) | 13 (`remotion-*`) | Ver nota abajo |
| [digitalsamba/claude-code-video-toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | 16 (`video-toolkit`, `remotion`, `ffmpeg`, `blender`, `elevenlabs`, ...) | MIT |
| [iart-ai/motion-skills](https://github.com/iart-ai/motion-skills) (índice de 19 packs) | 56 | MIT |

Licencias en `licenses/`.

Notas:
- `remotion-dev/skills` no incluye archivo de licencia; revisa https://www.remotion.dev/docs/license antes de usar Remotion comercialmente.
- `lower-thirds` existe en dos packs de iart-ai (`tiktok-video-skills` y `lower-thirds-skills`); se conservó la versión del pack dedicado.
- Algunas skills de `claude-code-video-toolkit` asumen el resto del toolkit (herramientas y plantillas del repo original).
- La skill `figma` de hyperframes puede chocar con la skill oficial de Figma.

## Instalar

```bash
git clone https://github.com/sebastianoyarbide20-lgtm/Skils-.git
mkdir -p ~/.claude/skills && cp -r Skils-/skills/* ~/.claude/skills/
```
