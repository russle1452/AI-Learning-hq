# Mission Contract: ____

<!-- Adapted from Mori's agent guide (Phase 2, weeks 23–25). One file per agent mission. -->

| Field | Contents |
| --- | --- |
| **Outcome** | What result must exist when this is done? |
| **Inputs** | What information may the agent use? (files, MCP tools, sources) |
| **Output** | The exact artifact: format, location, filename |
| **Definition of done** | Measurable checks only. No "good", "useful", "comprehensive" |
| **Constraints** | What must never happen |
| **Approval gates** | Which actions need me (all 🔴 actions, at minimum) |
| **Trigger** | What starts it (manual / event). Schedule only once proven |

## Permissions
- 🟢 **Automatic:** search, read, summarize, compare, classify, draft
- 🟡 **Allowed after diff review:** edit internal files, update JSON data, create deliverables
- 🔴 **Always ask:** send, publish, delete, spend, contact people, change permissions, touch production

## Retry policy
| Situation | Action |
| --- | --- |
| Tool error | Retry twice |
| Invalid output format | Repair once |
| Conflicting evidence | Stop and ask |
| Reviewer fails it | Return to the step that failed |
| 3 failed review rounds | Escalate to me |

## Release log (three runs before automating)
| Run | Date | Mode | Completed? | Interventions | Time to accepted result | What I fixed in the system |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | | Observe | | | | |
| 2 | | Correct (no reminders) | | | | |
| 3 | | Release (hands off) | | | | |

---

## Setup prompt
```
I want you to own this mission: [MISSION]

Before doing any work, convert it into a Mission Contract with:
Outcome, Inputs, Output, Definition of Done, Constraints,
Approval Gates, Trigger.

If anything important is ambiguous, ask before execution.
Do not begin until the finish line is measurable.
```
