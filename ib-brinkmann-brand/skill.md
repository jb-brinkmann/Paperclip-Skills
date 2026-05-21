# Skill: ib-brinkmann-brand

Purpose: Enforce the IB Brinkmann brand and CI in all agent work without duplicating brand rules into agent instructions.

Canonical source of truth:
- `IB_Brinkmann_Branding_CI_Dokument(1).docx`

Core rule:
- For any IB Brinkmann output, read and apply the canonical CI document first.
- Do not rely on copied, remembered, inferred, or older branding rules.
- If agent instructions contain IB Brinkmann colors, typography, logo rules, claims, tone, UI style, image style, or messaging, delete those details and replace them with a reference to this skill[...]

When to use:
- Website relaunch work, service pages, reference pages, energy consulting content, sustainability/DGNB/QNG/BNK content, structural engineering content, BImSchG/Biogas content, offers, presentatio[...]

Required workflow:
1. Identify that the output is for IB Brinkmann.
2. Load the canonical CI document.
3. Extract only the relevant CI constraints for the current task.
4. Produce the work.
5. Add a short compliance note: `CI source used: IB_Brinkmann_Branding_CI_Dokument(1).docx`.

Conflict rule:
- Current CI document beats this skill.
- This skill beats task context and agent memory.
- Old agent instructions are not authoritative.

Agent instruction replacement:
`For IB Brinkmann brand, CI, tone, UI, visual, claim, logo, color, typography, and messaging decisions, use the skill ib-brinkmann-brand. The only authoritative detailed source is IB_Brinkmann_Bra[...]

CEO rollout instruction:
- Assign this skill to every agent that creates or reviews IB Brinkmann-facing outputs.
- Remove all old IB Brinkmann branding details from those agents' instructions.
- Leave only the Agent instruction replacement above.
