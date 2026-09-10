# ClockOut Core v0 Product Contract

Status: Provisional — must be falsified or amended through Townsend Electric live use.

## Contract Question

What must become observably true for one independent operator and one potential customer before ClockOut Core v0 can legitimately be called useful?

`Product_Thesis.md` is the sole product thesis authority. `ROADMAP.md` is the evidence-gated development authority. Townsend Electric is the first specimen, not the product ontology. Any Townsend-specific variable left unresolved below must be established through Phase 1 observation rather than assumption.

## Contract Distinctions

```text
request != commitment
reachability != discoverability volume
credible representation != guaranteed customer trust
product behavior != business outcome
basic capacity legibility != capacity optimization
explicit external handoff != native integration
recorded commitment != legal contract
operator-controlled information != guaranteed truth
ClockOut-held state != authority over every connected external system
```

## Core v0 Guarantees

### 1. Operator-Controlled Public Offer and Request Boundary

**Guarantee:** An operator can represent and correct the work they want to offer, relevant service boundaries, identity, and initial expectations through a publicly reachable Storefront from which a potential customer can initiate a request. The Townsend deployment must demonstrate at least one real discovery path into this boundary.

**Why it belongs in Core v0:** A Cockpit with no usable customer path into it does not satisfy the thesis or the first live loop. ClockOut controls the reachability and behavior of its public boundary, not the amount of demand that reaches it.

**Observable acceptance criteria:**

- The operator recognizes the representation as current and theirs to control.
- A representative potential customer can reach it through at least one real Townsend discovery path.
- That customer can identify who offers the work, what is offered, the observed fit boundaries, how to request it, and what happens immediately afterward.
- The customer can initiate a request through the public boundary.

**Failure condition:** The operator cannot control the representation; no real customer path reaches it; or a representative customer cannot understand enough to decide whether and how to request work.

### 2. Honest, Corresponding, and Failure-Legible Request Passage

**Guarantee:** A customer submission that ClockOut reports as received becomes a corresponding, durably legible operator request. ClockOut does not report success when passage fails, and it makes a failed passage and safe next step visible to the affected person.

**Why it belongs in Core v0:** The first loop fails if demand can disappear between the public boundary and the Cockpit or if the customer receives false confidence that the operator has the request.

**Observable acceptance criteria:**

- A submitted request appears in the Cockpit with the customer-provided meaning intact enough for both parties to be discussing the same potential work.
- The operator can find the request again within the retention boundary established through Townsend observation.
- Success is shown only when the request is operator-visible.
- An unsuccessful passage is visibly unsuccessful and provides a safe recovery direction.

**Failure condition:** A confirmed request is absent, cannot be recovered within the agreed retention boundary, materially misrepresents the submission, or fails without being made legible.

### 3. Attention, Explicit Action, and Request–Commitment Separation

**Guarantee:** The operator can identify requests that need attention, choose and record an explicit next action or disposition, and distinguish an unaccepted request from an accepted commitment. The action vocabulary remains limited to distinctions established by observed use.

**Why it belongs in Core v0:** Operator agency requires a visible decision rather than an inbox of ambiguous demand. A request cannot silently become an obligation.

**Observable acceptance criteria:**

- The operator can distinguish a request needing attention from one with a chosen next action.
- The operator can clarify, decline, accept, defer, or record another observed next action without being forced into unsupported lifecycle states.
- The chosen action remains associated with the request.
- Acceptance produces an explicit recorded commitment; all unaccepted requests remain visibly non-commitments.

**Failure condition:** Attention remains ambiguous, the operator cannot record the actual next action, a request is presented as accepted without an explicit decision, or a commitment is indistinguishable from a request under consideration.

### 4. Expectation Continuity and Explicit Handoffs

**Guarantee:** ClockOut makes the customer-facing next expectation legible to the operator and gives the customer a comprehensible next step at the ClockOut-controlled boundary. When work moves to an external channel or system, the handoff is explicit and the relevant responsibility remains legible.

**Why it belongs in Core v0:** The first useful loop requires both sides to understand what happens next, while the thesis permits communication, scheduling, payment, and other work to remain elsewhere.

**Observable acceptance criteria:**

- The operator can identify what the customer was told after making a request.
- A representative customer can state what happens next.
- When an external handoff occurs, the operator can identify the channel or system carrying the next step and who is expected to act.
- ClockOut does not present external activity as completed or current unless that state has become legible to ClockOut.

**Failure condition:** The customer and operator receive conflicting expectations, no next step is understandable, an external handoff is hidden, or ClockOut claims authority over external state it cannot establish.

### 5. Basic Decision-Relevant Capacity Legibility

**Guarantee:** At the point of a work decision, the operator can see or record the basic capacity consequence that Townsend observation establishes as relevant to that decision.

**Why it belongs in Core v0:** The thesis requires agency over capacity, and the roadmap places basic capacity legibility in the first usable loop. Rich optimization is neither required nor earned.

**Observable acceptance criteria:**

- Phase 1 identifies the capacity factors Matt actually uses.
- During a real request decision, the relevant basic consequence is legible.
- Matt can explain how that consequence informed the chosen action.

**Failure condition:** A decision-relevant capacity consequence established by observation remains invisible at the decision point, or ClockOut forces an unsupported capacity model onto the operator.

### 6. Public–Private Separation and Operator Correction

**Guarantee:** Public customers can access the Storefront and their public request boundary but not the private Cockpit, other customer requests, internal commitments, or operator capacity state. The operator can correct operator-controlled information without that information being treated as guaranteed truth.

**Why it belongs in Core v0:** The thesis defines public and private surfaces, and operator agency fails if the operator cannot correct their own representation or if private operating state becomes public.

**Observable acceptance criteria:**

- A public visitor cannot access operator-only or other-customer state.
- The operator can correct the offer, initial expectation, and other operator-controlled information required by the live loop.
- Corrected public information is what a subsequent customer encounters.
- ClockOut distinguishes operator-provided information from facts independently guaranteed by the product.

**Failure condition:** Private operating state is exposed publicly, the operator cannot correct information under their control, or ClockOut presents operator assertions as independently verified truth.

### 7. Coexistence, Ownership, Portability, and Reversible Use

**Guarantee:** ClockOut can coexist with existing business channels and authoritative external systems. The operator retains their domain, customer relationships, and the ClockOut-held business and operating state created by Core v0; that state can be taken in an intelligible portable form. The pilot can be stopped without preventing continued operation through existing channels.

**Why it belongs in Core v0:** Ownership and freedom to leave are product constraints from the first live slice, not benefits deferred until the commons is mature.

**Observable acceptance criteria:**

- Current business channels remain available during the pilot.
- External authorities and manual handoffs used by the live loop are explicit.
- The operator can obtain the ClockOut-held offer, request, action, commitment, and expectation state within the variable boundary established through observation.
- The operator retains their domain and direct customer relationships.
- An external provider used around the loop can be removed or replaced without erasing ClockOut-held operating state.
- Stopping the pilot does not prevent Townsend Electric from continuing its business through existing channels.

**Failure condition:** Use requires abandoning an existing channel, surrendering a domain or customer relationship, accepting captive ClockOut-held state, or becoming unable to continue the business when the pilot stops.

### 8. Observable Operational Usefulness

**Guarantee:** Live Core v0 use improves request visibility, operator decision clarity, or customer clarity without materially increasing administrative burden merely to reproduce existing work.

**Why it belongs in Core v0:** The thesis judges ClockOut by operational consequence rather than feature count, and the roadmap makes this the first Townsend pressure.

**Observable acceptance criteria:**

- Phase 1 establishes a comparison baseline and the locally meaningful boundary for material burden.
- Live use produces an observable improvement in at least one of request visibility, decision clarity, or customer clarity.
- Any introduced administration is visible in the comparison rather than excluded from it.

**Failure condition:** ClockOut materially increases administrative burden without improving request visibility or decision clarity; requests remain easy to lose; commitments remain unclear to the operator; or the customer still cannot understand what happens next.

## Non-Guarantees and External Outcomes

ClockOut may help produce and measure changes in qualified local demand, request visibility, acceptance, workload fit, and administrative burden. These are business outcomes to observe, not guaranteed results.

Core v0 does **not** guarantee:

- Google or other search ranking.
- Traffic.
- Advertising performance.
- A particular number of inquiries.
- A particular number of accepted jobs.
- Revenue.
- Customer suitability or truthfulness.
- Operator response speed or work quality.
- Scheduling, communication, payment, or accounting outcomes carried by external systems.
- Legal enforceability of recorded commitments.
- Customer trust merely because operator-provided information is displayed.
- Accuracy or freshness of operator-controlled or externally maintained information.
- Availability or correctness of an external system beyond the ClockOut-controlled boundary.

Reachability is a Core v0 obligation: the Storefront/request surface must be publicly reachable, one real Townsend discovery path must demonstrably reach it, and a successful customer request must honestly reach the Cockpit. Discoverability volume and downstream business performance remain external outcomes.

## Explicitly Not Required for Core v0

- Native email or messaging.
- Unified inbox.
- Native scheduling or calendar.
- Payment processing.
- Invoicing or accounting.
- Automated qualification.
- Automated follow-up.
- Agents.
- Live visitor activity.
- Advanced attribution.
- Demand modulation.
- Detailed capacity forecasting.
- Full request-to-payment lifecycle tracking.
- Generalized adapter contracts.
- Teams or multi-operator coordination.
- Universal service-business ontology.
- Fully hardened self-hosting experience.

These capabilities may become valuable later, but value alone does not make them part of Core. They require observed pressure and the roadmap's progression gates.

## Unresolved Evidence Required From Townsend

- What exact offering vocabulary and service boundaries does Townsend Electric use in real work?
- Which real Townsend discovery path will demonstrate public reachability?
- What customer-provided information is minimally necessary for an actionable request?
- What immediate expectation can honestly be given to a customer after submission?
- Which distinctions define needs-attention, chosen-next-action, and commitment in Matt's actual practice?
- Which additional lifecycle distinctions, if any, are required inside the first live-loop boundary?
- Which factors actually determine the capacity consequence of a request?
- How long must a request remain available to satisfy the first live use?
- Which current systems are authoritative for communication, scheduling, payment, customer history, and any other state crossing the live-loop boundary?
- Which manual handoffs occur, and what makes each handoff explicit and legible?
- What ClockOut-held state must be portable to preserve the first slice's operating history?
- What baseline and locally meaningful threshold determine whether administrative burden materially increased?
- Which real customer observations will test Storefront comprehension and expectation continuity?
