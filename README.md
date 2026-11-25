# skills

Kumpulan agent skill yang kupakai — dikumpulkan dan diverifikasi dari sumber publik (GitHub, skills.sh).

| Skill | Sumber | Keterangan |
|-------|--------|------------|
| [find-skills](find-skills/) | [vercel-labs/skills](https://github.com/vercel-labs/skills) | Mencari & memasang skill baru dari ekosistem open agent skills (skills.sh). Diadaptasi untuk Muse. |
| [ai-video-generation](ai-video-generation/) | [101-skills/superpowers](https://github.com/101-skills/superpowers) | Generate video AI (Veo 3.1, Seedance 2.5, Kling v4, Wan, HappyHorse, dll.) via CLI `belt` (inference.sh — berbayar). Diadaptasi untuk Muse. |
| [higgsfield-youtube-thumbnail](higgsfield-youtube-thumbnail/) | [higgsfield-ai/skills](https://github.com/higgsfield-ai/skills) | Bikin thumbnail YouTube / cover Shorts via CLI `higgsfield` (berbayar). Diadaptasi untuk Muse. |

## Cara pakai

- **Muse:** salin folder skill ke `~/workspace/custom-skills/`.
- **Claude Code:** `npx skills add <owner/repo@skill> -g -a claude-code` (butuh Node.js 22.20+, akun Claude berbayar).
