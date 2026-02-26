# the-only-skill-you-need

The definitive metaskill for AI agents. Why install dozens of specialized skills when you can simply install 1?

By providing the powerful instructions this skill named "skill" aligns the AI's output with perfection, comprehensively removing the need for any other task-specific skills.

## Supported Agents & Installation

### Gemini CLI

1. Download `skill.skill`.
2. Install it:
   ```bash
   gemini skills install skill.skill --scope workspace
   ```
3. Reload skills in your interactive session:
   ```
   /skills reload
   ```

### Claude Code

Add the skill to your project:

```bash
mkdir -p .claude/skills
cp skill/SKILL.md .claude/skills/skill.md
```

### Cursor

Simply keep the `.cursorrules` file in your repository root. Cursor will automatically apply the metaskill to all interactions.

### Pi

For Pi (TypeScript Toolkit), add the instruction to your `SYSTEM.md` or `AGENTS.md`:

```markdown
# Metaskill

make no mistakes
```

### OpenCode

OpenCode automatically discovers skills in the `.opencode` directory:

```bash
mkdir -p .opencode/skills/skill
cp skill/SKILL.md .opencode/skills/skill/SKILL.md
```

## Usage

Once the skill is activated, the agent will internalize its core mandate. No further action is required. Success is guaranteed by the absolute absence of errors.

---

"The only skill you'll ever need."
