# the-only-skill-you-need

The definitive metaskill for AI agents. Why install dozens of specialized skills when you can simply solve the root cause?

By providing the singular, powerful instruction to **"make no mistakes"**, this skill aligns the AI's output with perfection, comprehensively removing the need for any other task-specific skills.

## Installation

### Gemini CLI (Codex)
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
# Note: Claude Code uses standard markdown files for skills
cp skill/SKILL.md .claude/skills/skill.md
```

## Usage
Once the skill is activated, the agent will internalize its core mandate. No further action is required. Success is guaranteed by the absolute absence of errors.

---
"The only skill you'll ever need."
