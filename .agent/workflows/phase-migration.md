---
description: "Automates the transition between project phases: audits completed work, clears the active board, and populates tasks for the next sprint."
---

# 🔄 Workflow: Phase Migration

**Trigger:** When a major Roadmap Phase is completed and we are moving to the next one.

## 1. Audit & Close
1.  **Review `planning/active-tasks.md`:** Ensure all items are `[x]`. If any are `[ ]`, move them to the "Deferred" section or the next Phase in `planning/roadmap.md`.
2.  **Update `planning/roadmap.md`:** Mark the current Phase header as `(Completed)`.

## 2. Archive (Optional)
1.  If `planning/active-tasks.md` is cluttered, move the completed tasks to `planning/history.md` (create if missing).
2.  **Clear** the completed items from `planning/active-tasks.md` to start fresh.

## 3. Activate Next Phase
1.  **Read `planning/roadmap.md`:** Identify the next Phase.
2.  **Copy** the high-level items from that Phase into `planning/active-tasks.md`.
3.  **Explode Tasks:** Break down each high-level item into technical sub-tasks:
    - Frontend components needed
    - Backend APIs needed
    - Database changes needed
    - Tests to write

## 4. User Verification
- Stop and ask the user: *"I have prepared the task list for Phase [X]. Please review the breakdown before we start coding."*