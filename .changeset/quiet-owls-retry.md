---
'@mastra/memory': patch
---

Fixed Observational Memory saving a cut-off reply when an observer or reflector model stream ended early (`finishReason: 'other'`). These calls now retry the whole request instead of continuing from the partial output.
