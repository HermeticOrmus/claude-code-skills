---
name: ho
description: Shorthand for /handoff — write a complete session-state HANDOFF for a fresh session to resume. Alias only; delegates to the handoff skill.
---

# /ho — alias for /handoff

This is a shorthand alias, nothing more. Immediately invoke the `handoff` skill via
the Skill tool, passing through the user's arguments verbatim. Do not do any handoff
work here — `handoff` owns the logic.
