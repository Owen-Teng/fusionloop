# When one person learns, does the organization learn too?

[简体中文](organizational-learning.zh-CN.md) · [FusionLoop home](../README.md)

A colleague solves a difficult problem and leaves a report. Months later, someone else faces a similar problem and repeats the search, interpretation, and experimentation. The result survived; the method did not transfer well.

My question is: **how can an individual's experience become a capability that other people can use, revise, and maintain through review and actual reuse?**

AI offers tools for organizing work records, comparing sources, and articulating methods. My hypothesis is that separating the purposes and responsibilities of knowledge, then checking reuse in real work, may be more useful than retaining everything indiscriminately.

## Four distinct functions

| Function | Question | Typical content | Stewardship |
| --- | --- | --- | --- |
| Sources and evidence | How do we know? | Original materials, provenance, versions, event dates, acceptance records | Traceable and permission-aware |
| Memory | What matters next time? | Decision reasons, relevant preferences, exceptions, unfinished work | Scope, date, and expiry conditions |
| Wiki | What is currently accepted? | Reviewed concepts, standards, facts, and limitations | Named owner, review state, and version |
| SOP or Skill | How do we do it again? | Inputs, steps, decision points, outputs, acceptance | Tried in use, with exceptions and recovery |

“Wiki” here means the reviewed organizational knowledge layer by agreement. Wiki software can also hold drafts. Readers need to know which state each item has.

## How experience changes status

An incorrect inference in a brief first leaves a trace: the sentence, source, and reason for correction. A reminder for the next similar task becomes scoped context.

If the team considers the mistake broadly relevant, it can propose a shared check. Authorized review promotes it into accepted knowledge. Turning that principle into an action and having a second user try it helps determine whether it belongs in an executable method.

Each transition needs judgment. An exception may belong only in context. An unclear principle is a poor automation candidate. A new finding that conflicts with a standard should propose a revision rather than silently replacing it.

## Evidence of organizational learning

Three questions help:

1. **Can another person use it?** Can they understand the input, follow the method, handle its boundaries, and deliver an acceptable result?
2. **Can an exception lead to correction?** Can they recognize a mismatch, find the owner, and propose a change?
3. **Is maintenance worthwhile?** Do later benefits cover comprehension, review, updates, and governance?

A saved template or a runnable skill is an intermediate artifact. If reuse requires constant help from the original author, improve the method or recognize that the work still needs direct expert participation.

## A minimal agreement for an agent

```text
Identify at most one lesson from this completed work that may matter later.
State its source, scope, possible exceptions, and proposed maintenance owner.
Recommend scoped context, a shared-knowledge proposal, or a method proposal.
Explain the choice. Do not mark your own summary as approved knowledge.
An authorized person decides whether to promote it.
Propose a check in which another person uses it.
If nothing useful should be retained, say no update is needed.
```

## Relationship to LLM Wiki

Karpathy's [LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) offers a public example of persistent knowledge compilation and revision. This proposal asks additional organizational questions: who approves knowledge, maintains methods, may use them, and checks whether reuse improves actual work?

This is a method design. Its effect on repeated learning and handoffs requires [actual cycles and independent reuse](../evaluation.md).
