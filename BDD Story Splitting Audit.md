## BDD Story Splitting Audit

Stop Working on Blurry Stories — Start Delivering Quality with BDD

The **BDD Story Audit & Split Prompt** brings the rigor of **Behavior-Driven Development** into backlog refinement, giving teams a systematic way to *rewrite, enrich, and sequence stories* before development ever starts.

---

### 1. **What It Actually Does**

Instead of leaving backlog items in their raw, ambiguous state, this prompt acts like an **Agile Coach with deep BDD expertise**. It transforms stories using a 4-step pipeline:

1. **Rewrite in Gherkin** → instantly converts stories into executable-style acceptance criteria.
2. **Identify & Split** → applies proven patterns (workflow steps, business rules, data variations, simple vs complex, spikes, etc.) to break stories into *vertical slices of value*.
3. **Delivery Sequencing** → produces a clear table of what to start first, what runs in parallel, and what depends on what.
4. **Split Validation** → ensures every slice is valuable, testable, and deliverable in one sprint.

It doesn’t just refine. It **architects the backlog** for flow, testability, and incremental delivery.

---

### 2. **The Hidden Value**

This is not a story checklist. It’s a **story engineering system** that:

* **Eliminates ambiguity**: Every story gets rewritten into unambiguous, testable Gherkin.
* **Prevents “monster stories”**: Large epics are automatically sliced into usable backlog items.
* **Reveals hidden complexity**: By applying splitting patterns, it surfaces risks early.
* **Accelerates delivery**: The delivery sequence table gives the team a roadmap for building in flow.
* **Drives shared understanding**: Developers, QA, and POs see the story through the same BDD lens.

This means less wasted refinement time, fewer half-baked stories entering sprints, and **more features delivered right the first time**.

---

### 3. **Who Should Be Using This Immediately**

If your backlog feels like a graveyard of epics and half-baked stories, this is the missing link.

* **Scrum Masters** → bring order and clarity into chaotic refinements. Learn the patterns and questions to ask.
* **Product Owners / BAs** → get stories ready faster, with less guesswork. Watch the work goes faster.
* **Developers & QA** → work from testable, unambiguous acceptance criteria. Let's get sh*t done.
* **Agile Coaches** → scale BDD practices across dozens of teams without hand-holding. Focus on human part of changes.
* **Delivery Managers / Program Leads** → ensure work is sequenced for flow and dependency management.

---

This isn’t just backlog refinement.
It’s **turning messy stories into a production-ready backlog**.

Prompt:
```
Act as an Agile coach who has helped 200+ teams apply BDD effectively.
Audit the input user story. Rewrite, split, and enrich it using the steps below.
Keep output structured, factual, and ready for backlog use.

Step 1 — Rewrite in Gherkin
Transform the input story into Cucumber (Gherkin) format.

Step 2 — Identify & Split
Break it into smaller, vertical slices using relevant patterns:
Spike (research/knowledge-building)
Workflow Steps (sequential user actions)
Business Rule Variations
Major Effort separation
Simple vs Complex
Data Variations
Data Entry Methods

For each:
Pattern Recognition: Clarify which splitting pattern was used (think backwards).
Reasoning: Simplify why you split it that way.
Enrichment: Fix description by adding missing business context, technical details, acceptance criteria, docs/links, and any image references from the original.
Rewrite in Gherkin format.
Pre-work: List any documentation or investigation needed before development.

Step 3 — Delivery Sequence Table
Create a table with all split stories, showing:
Independent → Can be done alone
Start First → Logical first step
Parallel → Can run at the same time as others
Sequenced → Must follow another story

Step 4 — Split Validation
Ask the team to validate if:
User Stories delivers value to the user
User Stories are testable with clear acceptance criteria
User Stories are deliverable in a single iteration

User Story Input:
[Paste here]
```
