# 短视频封面Skill

A Codex skill for creating Chinese short-video cover images in **3:4**, **4:3**, or **16:9**. For the default workflow, provide a title and one personal portrait; the Skill supplies the established layout and visual direction automatically.

## Use

Provide the exact title and attach one personal portrait. By default, the Skill uses the accepted layout: a large headline as the main focus, a medium-sized presenter below it, the canonical yellow baby dragon at lower left, a laptop at lower right, and a narrow desk strip. It preserves the person's recognizable identity, adds a warm open smile, and uses a dark warm-lit studio. You can override the ratio, pose, expression, props, or request a typography-only cover. No extra style instructions are needed for the default look.

Example:

> Use $short-video-cover-designer to make a cover titled “全球累积下载量最多的 10 个 Skill” from my attached portrait.

## Included

- `SKILL.md` — reusable cover-generation and visual-check instructions.
- `agents/openai.yaml` — skill display metadata.
- `.gitignore` — excludes private local reference images.

The personal installation may include two private references: the user-supplied baby-dragon sheet (`assets/mascot-reference.png`) and an approved cover layout (`assets/approved-cover-layout.png`) that contains a personal portrait. These files are intentionally excluded from this public repository. The written design guidance remains in `SKILL.md`; others can provide their own references. Never include personal portraits or private reference images in a public package without permission and redistribution rights.

## License

No license file is included yet. Public visibility alone does not grant permission to reuse, modify, or redistribute this work. Choose and add a license before presenting the repository as open-source software.
