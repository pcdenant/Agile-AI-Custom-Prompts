## 3 Amigos Simulation for Story Readiness

Insights from 3 Amigos — Before You Even Step Into the Meeting (stress-test your story)

The **3 Amigos Simulation Prompt** turns raw backlog items into **pre-vetted, multi-perspective audits** that surface hidden risks, missing clarity, and testability gaps in minutes.

---

### 1. **What It Actually Does**

Instead of waiting for live discussions (that may delay crucial feedback), this prompt **simulates the collective wisdom of three expert roles**:

* **QA Engineer** → stress-tests acceptance criteria for testability, edge cases, and automation.
* **Developer** → exposes technical unknowns, dependencies, and risky assumptions.
* **PO / BA** → ensures business goals, value, and alignment are crystal clear.

It doesn’t just produce opinions. It organizes the dialogue into a **concise, scannable output** and finishes with a **Readiness Vote** so you know exactly where the story stands.

---

### 2. **The Hidden Value**

* **Cuts waste**: Teams don’t walk into refinement blind; they start with pre-analyzed insights.
* **Improves story quality**: Stories get hardened against edge cases and ambiguity before development.
* **Accelerates alignment**: Everyone sees the same risks and gaps, reducing back-and-forth during refinement.
* **Teaches teams to think like experts**: Over time, story authors start preemptively covering what the 3 Amigos would flag.

It’s like having **three senior experts reviewing every backlog item instantly** — without needing to sync calendars.

---

### 3. **Who Should Be Using This Right Now**

If your 3 Amigos sessions drift into endless debates or miss key risks until too late, this tool is your upgrade.

* **Scrum Masters** → run tighter refinements by starting from a prepared baseline. Learn to ask the right questions.
* **Product Owners / BAs** → harden their stories before exposing them to the team. Learn to write quality stories from scratch.
* **Developers & QA** → enter refinement with concrete concerns already surfaced. Have a constructive discussion on specific context rather than obvious missing parts.
* **Agile Coaches** → scale best practices across squads without needing to attend every single session. 

---

This isn’t just a simulation.
It’s the **fast lane to bulletproof user stories** — combining quality, feasibility, and value **before** work begins.

No more “we’ll discover it later.”
With this, **the story tells you if it’s truly sprint-ready**.

Prompt:
```
Act as a facilitator who has led 200+ successful 3 Amigos sessions.
Audit this user story by simulating a structured discussion between three expert roles.
Use Markdown formatting, stay factual and concise, and output a result that’s scannable and actionable. No fluff.

Step 1 — 3 Expert Perspectives
Simulate the viewpoints of each role.
Use headers and bullet points.

QA Engineer — Testability & Quality
Focus:
How will it be tested?
Are the acceptance criteria testable?
Any edge cases or automation gaps?
Key questions:
“How do we validate success?”
“What could go wrong?”
“What’s missing from a test perspective?”

Developer — Feasibility & Build
Focus:
Are there technical unknowns or hidden work?
Dependencies or risky assumptions?
Can it be broken down into dev chunks?

Key questions:
“What infra, testing, or migration is involved?”
“Any blockers or constraints?”
“Is the scope realistic?”

PO / BA — Clarity & Value
Focus:
Is the business goal clear?
Is the value to the user explicit?
What happens if we skip this?

Key questions:
“What’s the user problem?”
“How do we define success?”
“Is this story aligned with product goals?”

Step 2 — Readiness Vote & Actions
Each role votes:
✅ Ready for Sprint
⚠️ Ready with Modifications
❌ Not Ready
If all vote ✅ → mark as READY for Sprint.
Otherwise → each persona clarify missing info and provide examples of required info to pass.

User Story Input:
[Paste story here]
```
