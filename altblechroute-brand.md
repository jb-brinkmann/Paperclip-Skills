# Skill: altblechroute-brand

Purpose: Enforce the Altblechroute brand and CI in all agent work without duplicating brand rules into agent instructions.

Canonical source of truth:
- `Altblechroute_Branding_CI_Dokument(1).docx`

Core rule:
- For any Altblechroute output, read and apply the canonical CI document first.
- Do not rely on copied, remembered, inferred, or older branding rules.
- If agent instructions contain Altblechroute colors, typography, logo rules, claims, tone, UI style, image style, or messaging, delete those details and replace them with a reference to this skill.

When to use:
- Website, route pages, POI pages, partner pages, workshop/host/event content, maps, signs, print, social posts, newsletters, presentations, and any visual or textual Altblechroute output.

Required workflow:
1. Identify that the output is for Altblechroute.
2. Load the canonical CI document.
3. Extract only the relevant CI constraints for the current task.
4. Produce the work.
5. Add a short compliance note: `CI source used: Altblechroute_Branding_CI_Dokument(1).docx`.

Conflict rule:
- Current CI document beats this skill.
- This skill beats task context and agent memory.
- Old agent instructions are not authoritative.

Agent instruction replacement:
`For Altblechroute brand, CI, tone, UI, visual, claim, logo, color, typography, and messaging decisions, use the skill altblechroute-brand. The only authoritative detailed source is Altblechroute_Branding_CI_Dokument(1).docx. Do not maintain copied CI details in these instructions.`

CEO rollout instruction:
- Assign this skill to every agent that creates or reviews Altblechroute-facing outputs.
- Remove all old Altblechroute branding details from those agents' instructions.
- Leave only the Agent instruction replacement above.
