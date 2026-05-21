# Skill: ea-direkt-brand

Purpose: Enforce the ea-direkt brand and CI in all agent work without duplicating brand rules into agent instructions.

Canonical source of truth:
- `ea-direkt_Branding-CI-Dokument(1).docx`

Core rule:
- For any ea-direkt output, read and apply the canonical CI document first.
- Do not rely on copied, remembered, inferred, or older branding rules.
- If agent instructions contain ea-direkt colors, typography, logo rules, claims, tone, UI style, image style, or messaging, delete those details and replace them with a reference to this skill.

When to use:
- Website, UI, landing pages, sales pages, offers, documents, social posts, ads, email templates, presentations, customer communication, and any visual or textual ea-direkt output.

Required workflow:
1. Identify that the output is for ea-direkt.
2. Load the canonical CI document.
3. Extract only the relevant CI constraints for the current task.
4. Produce the work.
5. Add a short compliance note: `CI source used: ea-direkt_Branding-CI-Dokument(1).docx`.

Conflict rule:
- Current CI document beats this skill.
- This skill beats task context and agent memory.
- Old agent instructions are not authoritative.

Agent instruction replacement:
`For ea-direkt brand, CI, tone, UI, visual, claim, logo, color, typography, and messaging decisions, use the skill ea-direkt-brand. The only authoritative detailed source is ea-direkt_Branding-CI-[...]

CEO rollout instruction:
- Assign this skill to every agent that creates or reviews ea-direkt-facing outputs.
- Remove all old ea-direkt branding details from those agents' instructions.
- Leave only the Agent instruction replacement above.
