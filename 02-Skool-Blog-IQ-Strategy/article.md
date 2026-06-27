# Microsoft Vision (at least mine) — The IQ Era

---

## The problem Microsoft is solving

**Today’s enterprise reality**

- Data is fragmented (ERP, IoT, BI, apps…)
- AI exists but is stateless and generic
- Business context is missing

**Result**

- AI can generate, but it cannot **understand** or **operate** the business.

---

<div style="margin-left:0;padding:1.1rem 1.25rem 1.25rem;border-radius:12px;background:#1e3a5f;color:#f8fafc;box-shadow:none;border:1px solid rgba(255,255,255,0.08);">
<h2 style="margin:0 0 0.55rem 0;font-size:1.25rem;font-weight:600;color:#ffffff;letter-spacing:-0.02em;">The system flow</h2>
<div style="height:1px;background:rgba(255,255,255,0.18);margin:0 0 0.85rem 0;"></div>
<p style="margin:0 0 0.45rem 0;color:#e2e8f0;line-height:1.6;font-size:1.05rem;">Microsoft responds to <strong>fragmented data</strong> and <strong>stateless, generic AI</strong> by splitting responsibility across three layers—so the stack can <strong>understand</strong> the business, <strong>REASON</strong> with governance, and <strong>ACT (REACT)</strong> in the apps and workflows where people already work.</p>
<p style="margin:0 0 1rem 0;color:#e2e8f0;line-height:1.6;font-size:1.05rem;"><span style="font-weight:700;text-decoration:underline;text-underline-offset:0.18em;text-decoration-thickness:2px;text-decoration-color:#20E2B2;">Fabric</span> composes a <strong>unified live context</strong>; <span style="font-weight:700;text-decoration:underline;text-underline-offset:0.18em;text-decoration-thickness:2px;text-decoration-color:#FFB900;">Foundry</span> runs <strong>decision logic and trusted knowledge</strong> on top of it; <span style="font-weight:700;text-decoration:underline;text-underline-offset:0.18em;text-decoration-thickness:2px;text-decoration-color:#5DADE2;">Work IQ</span> brings outcomes back through <strong>Copilot and the apps people already work in</strong> for confirmation and handoff.</p>
<ol style="margin:0;padding-left:1.25em;color:#f1f5f9;line-height:1.65;font-size:0.98rem;list-style-position:outside;">
<li style="margin:0 0 0.35em 0;"><strong>Fabric IQ</strong> → understands (unified context)</li>
<li style="margin:0 0 0.35em 0;"><strong>Foundry IQ</strong> → reasons</li>
<li style="margin:0;"><strong>Work IQ</strong> → acts</li>
</ol>
<div style="height:1px;background:rgba(255,255,255,0.12);margin:0.95rem 0 0 0;"></div>
</div>

---

## Example with a Use Case

<div style="margin-left:0;padding:1rem 1.25rem 1.15rem;border-radius:12px;border:1px solid #e2e8f0;border-top:3px solid #5DADE2;background:linear-gradient(165deg,#ffffff 0%,#f8fafc 45%,#f1f5f9 100%);box-shadow:0 2px 14px rgba(15,23,42,0.06),0 0 0 1px rgba(255,255,255,0.8) inset;color:#0f172a;">
<p style="margin:0;color:#475569;line-height:1.65;font-size:0.98rem;">In a hospital, a nurse needs a medication for a patient, but the dose is not available on the unit. In this hospital, getting it to the ICU is usually a robot task.</p>
</div>

<div style="margin-left:0;margin-top:0.75rem;padding:1.1rem 1.25rem 1.2rem;border-radius:12px;background:#1e3a5f;color:#f8fafc;box-shadow:none;border:1px solid rgba(255,255,255,0.08);">
<p style="margin:0 0 0.6rem 0;font-size:1.02rem;color:#ffffff;">How to read this story</p>
<ul style="margin:0;padding-left:1.2em;color:#f1f5f9;line-height:1.55;list-style-position:outside;">
<li style="margin:0 0 0.45em 0;">Follow one request from start to finish; each step shows which IQ layer is active and what that layer is responsible for there.</li>
<li style="margin:0 0 0.45em 0;margin-left:3em;list-style-type:none;"><span aria-hidden="true" style="display:inline-block;width:10px;height:10px;background:#5DADE2;vertical-align:middle;margin-right:0.55em;box-shadow:0 0 0 1px rgba(0,0,0,0.2);"></span>Work IQ — how people work (Copilot and everyday apps) <span style="display:inline-block;vertical-align:middle;margin:0 0.2em 0 0.35em;line-height:0" title="Maps to this agent role"><svg width="38" height="16" viewBox="0 0 38 16" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false"><circle cx="7" cy="8" r="3" fill="#334155" stroke="#5DADE2" stroke-width="1.2"/><path d="M13.5 8h17" stroke="#5DADE2" stroke-width="2.2" stroke-linecap="round"/><path d="M28 4.5l7.5 3.5-7.5 3.5" stroke="#5DADE2" stroke-width="2.2" fill="none" stroke-linecap="round" stroke-linejoin="round"/></svg></span> <strong>Interaction agent</strong></li>
<li style="margin:0 0 0.45em 0;margin-left:3em;list-style-type:none;"><span aria-hidden="true" style="display:inline-block;width:10px;height:10px;background:#FFB900;vertical-align:middle;margin-right:0.55em;box-shadow:0 0 0 1px rgba(0,0,0,0.2);"></span>Foundry IQ — how the system decides (RAG, choices) <span style="display:inline-block;vertical-align:middle;margin:0 0.2em 0 0.35em;line-height:0" title="Maps to this agent role"><svg width="38" height="16" viewBox="0 0 38 16" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false"><circle cx="7" cy="8" r="3" fill="#334155" stroke="#FFB900" stroke-width="1.2"/><path d="M13.5 8h17" stroke="#FFB900" stroke-width="2.2" stroke-linecap="round"/><path d="M28 4.5l7.5 3.5-7.5 3.5" stroke="#FFB900" stroke-width="2.2" fill="none" stroke-linecap="round" stroke-linejoin="round"/></svg></span> <strong>Decision agent</strong></li>
<li style="margin:0 0 0.15em 0;margin-left:3em;list-style-type:none;"><span aria-hidden="true" style="display:inline-block;width:10px;height:10px;background:#20E2B2;vertical-align:middle;margin-right:0.55em;box-shadow:0 0 0 1px rgba(0,0,0,0.2);"></span>Fabric IQ — what the business <em>is</em> in data (live context, history, operations) <span style="display:inline-block;vertical-align:middle;margin:0 0.2em 0 0.35em;line-height:0" title="Maps to this agent role"><svg width="38" height="16" viewBox="0 0 38 16" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false"><circle cx="7" cy="8" r="3" fill="#334155" stroke="#20E2B2" stroke-width="1.2"/><path d="M13.5 8h17" stroke="#20E2B2" stroke-width="2.2" stroke-linecap="round"/><path d="M28 4.5l7.5 3.5-7.5 3.5" stroke="#20E2B2" stroke-width="2.2" fill="none" stroke-linecap="round" stroke-linejoin="round"/></svg></span> <strong>Data agent + operations agent</strong></li>
</ul>
</div>

### 1. She opens Teams and asks in natural language

- The nurse starts <span style="color:#5DADE2"><strong>Copilot</strong></span> in Teams—for example: *“Bed 4 ICU north needs their stat antibiotic—we don’t have it on the floor. Can someone bring it from the secure pharmacy / central prep? I can’t leave.”*

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Work IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Copilot</strong> = <strong>human interface</strong>: microphone, chat, <strong>identity</strong> (who she is, role, unit), urgency from how she asks</li>
  <li>Does not replace EHR or stock systems; <strong>captures intent</strong> and passes a structured request downstream</li>
  <li>Without Work IQ: more app-switching and retyped context</li>
</ul>
</div>
</div>

### 2. <span style="color:#5DADE2"><strong>Copilot</strong></span> turns speech into a structured task

- Normalizes into entities: patient location, medication line, priority, action type (deliver / pick up / page)  
- Applies **policy at the edge** where needed (e.g., allowed to request that medication class on that unit)  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Work IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Interaction layer</strong>: guardrails the nurse sees, stays in one familiar app on a <strong>smartphone</strong></li>
  <li>She does not “open Foundry or Fabric”—<strong>Copilot</strong> invokes them next</li>
</ul>
</div>
</div>

### 3. A Foundry IQ <span style="color:#FFB900"><strong>agent</strong></span> takes ownership of the reasoning chain

- <span style="color:#FFB900"><strong>Agents</strong></span> as **decision-makers**: a <span style="color:#FFB900"><strong>decision agent</strong></span> receives the structured intent  
- Does not guess beds, stock, or robots; **plans**: missing facts, which queries, in what order  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Foundry IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Reasoning + orchestration</strong>: task interpretation, tool choice (Fabric context, policy <strong>RAG</strong>), path to a decision</li>
  <li>Articulates: what we know, what we still need, what is compliant next</li>
</ul>
</div>
</div>

### 4. Fabric IQ — ontology and graph

- <span style="color:#20E2B2"><strong>Ontology</strong></span> — **defines meaning** for this hospital: what counts as “ICU north bed 4,” the med line, “pharmacy,” “delivery robot,” an active order, a SKU, etc.  
- <span style="color:#20E2B2"><strong>Graph</strong></span> — **connects the business**: patient ↔ location ↔ order ↔ stock ↔ fleet (and related handoffs).  

### 5. Fabric IQ — data and operations agents

- <span style="color:#20E2B2"><strong>Data agents</strong></span> answer: patient location now, SKU vs. active order, stock and where it sits  
- <span style="color:#20E2B2"><strong>Operations agents</strong></span> add: charged robots, blocked corridors, pharmacy load / SLA pressure  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Fabric IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Ground truth</strong> for the business: real-time + historical, one place connecting bed, order, inventory, fleet</li>
  <li>Without it: a chatbot with no unified hospital state</li>
</ul>
</div>
</div>

### 6. Foundry IQ pulls in trusted knowledge (<span style="color:#FFB900"><strong>RAG</strong></span>)

- <span style="color:#FFB900"><strong>RAG</strong></span> injects **trusted knowledge**: retrieves **hospital protocols**, **medication rules** (windows, allergy checks via linked records), **robot SOPs** (Standard Operating Procedures)—from **curated** corpora, not the open web  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Foundry IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>RAG</strong> ties answers to <strong>approved</strong> sources; robot/route/handoff stays under clinical and ops governance</li>
  <li>Fabric often <strong>hosts</strong> that content; Foundry <strong>uses</strong> it for this specific decision</li>
</ul>
</div>
</div>

### 7. Foundry IQ decides: best path under constraints

- Weights stock, distance, battery, corridors, protocol  
- Chooses **best robot**, **route**, **priority** (e.g., preempt lower-urgency work only if policy allows)  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Foundry IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Decision layer</strong>: optimization + compliance</li>
  <li>Outputs an <strong>auditable</strong> recommendation and rationale—not a blind “yes”</li>
</ul>
</div>
</div>

### 8. Work IQ brings the answer back to the nurse’s phone

- <span style="color:#5DADE2"><strong>Copilot</strong></span> shows a short summary + confirm—for example: *“Robot B will bring the verified dose from central pharmacy to ICU north in about 3 minutes. Pharmacy has acknowledged. Confirm dispatch?”*  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Work IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Human-in-the-loop</strong> in the same Teams thread, readable on a small screen, one tap to confirm or change</li>
  <li>The nurse <strong>acts</strong> here; execution is not invisible automation</li>
</ul>
</div>
</div>

### 9. Execution: systems move; people stay informed

- On confirm: signals to robot control and pharmacy; **tracking** in Teams (status, ETA updates)  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Work IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Notifications</strong> and task flow where the nurse already works</li>
</ul>
</div>
</div>

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Fabric IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Records</strong> the run: timestamps, actor, route, exceptions—for ops and compliance</li>
</ul>
</div>
</div>

### 10. Fabric IQ closes the learning loop

- After delivery: stores timing, delays, handoff success on the <span style="color:#20E2B2"><strong>graph</strong></span> (unit, shift, med class, robot)  

<div style="margin-left:6em;padding:0.45em 0 0.9em 1.5em;border-left:4px solid #5DADE2;border-radius:10px;overflow:hidden;color:#1e3a8a;background:#cbd5e1;">
<p style="margin:0 0 0.35em 0;"><strong>Why Fabric IQ</strong></p>
<div style="margin-left:4.5em;padding-left:1.5em;border-left:3px solid #7dd3fc;border-radius:0 8px 8px 0;color:#334155;background:transparent;">
<ul style="margin:0.35em 0 0 0;padding-left:1.5em;color:#475569;">
  <li><strong>Continuous improvement</strong>: richer history for the next stat request (e.g., routes that fail at handoff)</li>
  <li>Foundry can reuse that history; Work IQ can shorten prompts when patterns repeat</li>
</ul>
</div>
</div>

### Scenario steps (quick reference)

<div style="margin:0.5rem 0 1rem;border-radius:16px;overflow:hidden;border:1px solid #e2e8f0;background:#f1f5f9;line-height:0;">
<img src="media/iq-era-scenario-workflow.png" alt="Scenario workflow: Foundry IQ as central brain; Work IQ left, Fabric IQ right; green lane for Fabric step 4 and violet for step 5 — solid spokes Foundry to Fabric, dashed arcs to RAG; gold dashed replan; bottom caption bar matches those six stroke types plus main path" style="display:block;width:100%;max-width:100%;height:auto;" />
</div>

The workflow above is the **story** (what happens step by step). The diagram below is a **minimal implementation lens**: three named **agents** (icon + responsibilities each)—easy to scan next to the detailed scenario.

<div style="margin:0.5rem 0 1rem;border-radius:16px;overflow:hidden;border:1px solid #e2e8f0;background:#f1f5f9;line-height:0;">
<img src="media/iq-era-implementation-architecture.png" alt="Implementation views: Interaction agent (Work IQ), Orchestrator agent (Foundry IQ), Context agent (Fabric IQ); bidirectional arrows between adjacent agents" style="display:block;width:100%;max-width:100%;height:auto;" />
</div>

---

## The shift

<div style="margin:0.35rem 0 1rem;padding:1.1rem 1.25rem 1.15rem;border-radius:12px;background:#1e3a5f;color:#f1f5f9;border:1px solid rgba(255,255,255,0.1);font-size:1.2rem;line-height:1.65;box-shadow:none;">
<table style="width:100%;border-collapse:collapse;font-size:inherit;line-height:inherit;color:inherit;">
<thead>
<tr>
<th style="text-align:left;padding:0.5rem 0.75rem 0.55rem 0;border-bottom:2px solid rgba(255,255,255,0.28);font-weight:700;color:#ffffff;letter-spacing:0.02em;">From</th>
<th style="text-align:left;padding:0.5rem 0 0.55rem 0.75rem;border-bottom:2px solid rgba(255,255,255,0.28);font-weight:700;color:#ffffff;letter-spacing:0.02em;">To</th>
</tr>
</thead>
<tbody>
<tr>
<td style="vertical-align:top;padding:0.85rem 0.75rem 0.15rem 0;border-bottom:1px solid rgba(255,255,255,0.14);color:#f1f5f9;">Tools (Data + AI + Apps)</td>
<td style="vertical-align:top;padding:0.85rem 0 0.15rem 0.75rem;border-bottom:1px solid rgba(255,255,255,0.14);color:#f1f5f9;">A unified intelligent system that <strong style="color:#ffffff;font-weight:700;">reasons</strong> and <strong style="color:#ffffff;font-weight:700;">acts</strong>, on a live, unified view of the business</td>
</tr>
</tbody>
</table>
</div>

---

## The IQ system (three layers)

### 1. Fabric IQ — Understanding the business

**What it does**

- Unifies enterprise data
- Builds semantic models
- Adds <span style="color:#20E2B2"><strong>ontology</strong></span> + <span style="color:#20E2B2"><strong>graph</strong></span>
- Enables real-time + historical understanding
- Provides <strong>analytic</strong> + <strong>operational</strong> agents over the same unified business view

**Output**

- A shared business language

---

### 2. Foundry IQ — Reasoning & deciding

**What it does**

- Builds AI <span style="color:#FFB900"><strong>agents</strong></span>
- Connects to enterprise knowledge
- Uses <span style="color:#FFB900"><strong>RAG</strong></span> (Retrieval-Augmented Generation)

**Output**

- Context-aware intelligent decisions

---

### 3. Work IQ — Interacting & executing

**What it does**

- Embeds AI into daily workflows
- Understands meetings, chats, tasks
- Interfaces via <span style="color:#5DADE2"><strong>Copilot</strong></span>

**Output**

- Natural human interaction with AI

---

## Where **agents** live (clarified)

| Layer | Agent type | Role |
|--------|------------|------|
| Work IQ | <span style="color:#5DADE2"><strong>Interaction Agent</strong></span> | UX / <span style="color:#5DADE2"><strong>Copilot</strong></span> |
| Foundry IQ | <span style="color:#FFB900"><strong>Decision Agent</strong></span> | Reasoning |
| Fabric IQ | <span style="color:#20E2B2"><strong>Data Agent</strong></span> | Explain data |
| Fabric IQ | <span style="color:#20E2B2"><strong>Operations Agent</strong></span> | Monitor & react |

---

### One-line takeaway

Microsoft IQ turns enterprise data into **shared understanding**, understanding into **intelligent decisions**, and decisions into **real-world actions**.
