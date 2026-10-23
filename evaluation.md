# How to decide whether FusionLoop is worth keeping

[简体中文](evaluation.zh-CN.md) · [Cycle record](templates/cycle-record.md) · [Home](README.md)

Choose bounded, recurring work. Specify task selection, quality requirements, stopping conditions, and the recipient before starting. Retain every included success, failure, and withdrawal.

## Separate two questions

| Condition | Working approach | Question |
| --- | --- | --- |
| T0 | Existing work, with actual effort and outcomes recorded | What is the baseline? |
| T1 | Explicit outcomes, ownership, acceptance, recovery, and records; no additional agent intervention | Does work design itself help? |
| T2 | Add a specified agent capability to T1 | What additional change comes from the agent? |

Describe existing tools in T1, including any AI already in use. Do not attribute all T1-versus-T0 improvement to a new agent.

This is a comparison framework, not a guarantee of causal identification. Sequential work can be affected by learning, difficulty, staffing, and time. Where feasible, use randomized or interleaved comparable tasks with consistent acceptance. Otherwise report limited observations and alternative explanations. Repeating the same task may reward memory rather than the tool.

## Observe the complete outcome

- **Cycle time:** qualified input to acceptance, including waiting and rework.
- **All human effort:** preparation, execution, review, coordination, repair, and maintenance.
- **Quality and risk:** acceptance, important errors, rejection reasons, and boundary violations.
- **Total cost:** tools, labor, maintenance, and recovery, using consistent definitions.
- **Independent reuse:** whether a second person can deliver under comparable conditions and how much author support remains necessary.

Agree denominators, time windows, and priorities before collecting results. A few cycles can show feasibility or early signals. There is no universal passing sample size; stronger causal claims require a design appropriate to task variability and decision risk.

## What should weaken or change the proposal

If disputes, waiting, and rework do not decline, examine unnecessary steps. If execution speeds up but review slows down, report the net change. If maintenance repeatedly consumes the benefits, simplify or stop. If another user cannot finish independently, keep reuse unvalidated.

Stop and recover when predefined quality, permission, or irreversible-harm limits are breached. Average time savings do not cancel a breached requirement. “No clear improvement” is a valid outcome.

## Evidence in this release

Available: method argument, canvas, prompts, and a constructed example.

Not established by this repository: real T0/T1/T2 comparisons, independent-reuse results, or organizational effects. Future reports should identify versions, scope, selection, actual records, and limitations. Document counts, agent calls, and self-assessment cannot substitute for those outcomes.
