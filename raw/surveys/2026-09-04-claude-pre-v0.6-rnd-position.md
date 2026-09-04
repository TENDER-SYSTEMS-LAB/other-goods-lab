# OTHER GOODS — Independent Pre-v0.6 Critique

Status: adversarial evaluation of pre-v0.6 conclusions. Not a v0.6 design.

---

## 0. Headline Position

The single most consequential fact about this R&D stage is not in the brief: **nothing has been built.** Five rounds of evaluation exist and zero working commercial surfaces exist. Every hypothesis under review (post-purchase depth, price logic, order history at six months, register fidelity) is a claim about an interface and a claim about time. Both are being adjudicated in prose. Prose is the wrong instrument. A store's credibility lives in page weight, checkout latency, email formatting, tax lines, tracking numbers, and support tone, none of which can be evaluated as a title list.

The second most consequential fact: **four independent LLM evaluations converging is one opinion sampled four times.** Systems trained on overlapping corpora share priors about what "too sentimental" and "too poetic" mean. The convergence on WORKING BUT NEEDS CORRECTION is weak evidence about the artwork and strong evidence about the evaluator population. This document is the fifth sample and should be discounted accordingly.

Both facts point the same direction: the project should stop specifying and start transacting.

---

## 1. Methodology Critique

### 1.1 The apparatus is outgrowing the work

The visitor sees a store. They never see Product Grammar, Commerce Type, Product Role, or the Behavior Sheet. These are production tools, and production tools are justified only by leverage: do they make it cheaper to produce SKU 87 than SKU 12? Right now the taxonomy is being used to *evaluate* fourteen items, which is a job that judgment does faster. Any field that does not accelerate future production or force a real design decision should be deleted.

Concrete test for every methodological artifact: *if the catalog reaches 120 SKUs, does this field save time or cost time?* Product Grammar taxonomy costs time. Price Logic saves time, because it makes pricing decidable by someone other than the founder.

### 1.2 Evaluation cadence now exceeds production cadence

Six versions of critique, one collection. This is the failure pattern where the criticism becomes the artwork's primary output. It is worth naming plainly because it is currently invisible from inside the process: the project is generating high-quality documents about a store that does not exist, and each document makes the next document easier to write and the store harder to start.

### 1.3 Overfitting to machine criticism

The v0.4 → v0.5 correction (away from sentiment, toward institutional and industrial states) may have been correct. It may also be the taste of the evaluator being mistaken for the needs of the work. Language models systematically flag emotional directness as a weakness and reward specificity, technical register, and structural novelty. That is exactly the correction the project made. The project has now spent two versions moving toward a set of preferences that no human visitor holds.

Recommendation: before v0.6, run one evaluation round with **non-LLM readers who have never seen the brief.** Show them a mocked product page with no context and ask one question: what is this. The answers are worth more than four more evaluations of this kind.

### 1.4 The formula has not been broken, only re-skinned

Current title inventory: `17,400 Hz`, `Unit 12B, Unoccupied`, `$8.00 Price Drop, 10 Minutes After Purchase`, `First 12 Sheets Discarded Before Printing`, `Upper-Right Corner, Dented in Transit`, and now `Distance to Home: 1,847 mi`, `Repair Scope: Partial`. One shape: **[precise datum, specified to an unnecessary decimal].** Register Fidelity does not break this shape; it supplies more sources for the same shape. A visitor scrolling forty of these decodes the machine in under two minutes, and once decoded, the store stops being a store and becomes a puzzle with a known key.

The generator problem is real and none of the proposed rules address it.

---

## 2. Hypothesis A — Reduce to 12–16 and Deepen

**Verdict: correct as R&D policy, wrong as catalog policy. Do both.**

The §18 self-criticism is right: 12–16 highly engineered products reads as a boutique or a gallery checklist, not as commercial infrastructure. Realism in retail comes from the long tail. A real store is 90% unremarkable stock, and the unremarkable stock is what makes the strange item land, because the strange item arrives inside an environment that is visibly not trying.

Proposed correction:

- **12–16 fully-behaved products.** Full lifecycle, full sheet, built end to end.
- **40–60 background stock items.** Name, price, category, one image, a dull description. No lifecycle design. These are not filler. They are the ground the figures stand on.

The background stock also solves format fatigue for free: the strange titles stop reading as a formula when 80% of the catalog is dull. Currently every item is load-bearing, which is why every item reads as authored.

This is also a cheap experiment. Fifty dull SKUs cost a weekend and would tell the project more about its own realism than another critique round.

---

## 3. Hypothesis B — Commerce Must Do Conceptual Work

**Verdict: the principle is right. The trichotomy is dead weight.**

Commerce-Generated / Activated / Displayed is a three-way label applied *after* a judgment has already been made, and the judgment is made by a test the project already has: **what disappears if Commerce is removed?** The Failure Test is operational, binary, and decides admission. The trichotomy produces arguments at the margins (is `17,400 Hz` Activated or Displayed?) with no downstream consequence for any design decision.

Remove the trichotomy. Keep the Failure Test. Add one threshold: if the Failure Test answer is "the framing," the product is a caption and does not enter.

---

## 4. Post-Purchase Rule

Current rule: *design it if it reveals depth, do not force it if it adds only a joke.*

**This rule is unfalsifiable and therefore not a rule.** No team has ever believed its own addition was merely a joke. It is a statement of taste wearing a rule's clothing, and it will approve whatever the project already wants to do.

**Replacement: post-purchase behavior is mandatory to specify, optional to be eventful.**

Every product must have a written answer for confirmation, fulfillment, order history at six months, return, and repurchase. The answer is permitted to be *nothing happens*. Silence is a legitimate and sometimes superior design: an item that confirms with boilerplate, never ships, and sits unchanged in order history forever is doing more work than an item that stages a surprise in month six. The failure mode is not plainness. It is unconsidered default.

### 4.1 The reach problem

There is a harder issue the brief does not raise. Post-purchase depth at six months requires the visitor to have created an account, paid, and returned voluntarily half a year later. The realistic return rate approaches zero. The project is currently planning to invest its deepest conceptual work in the surface with the smallest audience.

Two honest responses:

1. **Build for push, not pull.** Email reaches people passively. A shipping notification, a recall notice, or a price-drop alert arriving in March, unprompted, from a store the person forgot they used, is the strongest available delivery mechanism for this work and costs almost nothing. Order history is pull. Email is push. Prioritize accordingly.
2. **Admit the documentation function.** Some post-purchase design exists for the archive and the eventual documentation of the work rather than for visitors. That is acceptable, but it should be budgeted as documentation, not as audience experience.

---

## 5. Price Logic and Inventory Logic

**Verdict: mandatory as a field. Not mandatory as a distinctive answer.**

Yes, make both fields required. The critique that price currently functions only as evidence-of-store is accurate.

But there is an inverted danger the brief does not flag. If Price Logic is mandatory in the sense of *interesting*, every product acquires a bespoke pricing gimmick, and a store where all forty prices are conceptually loaded is not a store. It is a puzzle box with a cart. Real commercial systems are overwhelmingly flat: one currency, one tax rule, one shipping table, mostly round arbitrary numbers.

Proposed constraint: **at most one product in four may have non-trivial price behavior. The remainder must be flat and arbitrary.** Same ratio for inventory. Deviation is only legible against uniformity.

### 5.1 Inventory is under-used relative to price

Price is the surface everyone thinks about. Inventory is more expressive and cheaper. "In stock: 3" versus "In stock: 1" versus "Currently unavailable" versus "This item does not sell out" versus "1 remaining" that never decrements no matter how many people buy. Scarcity is the most emotionally active number in retail and the project has barely touched it.

Specifically unexplored: **does one person's purchase reduce another's access?** For most of the catalog this can only be answered by lying, and the lie is the interesting part.

### 5.2 Missing surfaces: tax and shipping

Neither appears anywhere in the brief. Sales tax on `Yesterday`. A shipping weight for `17,400 Hz`. An estimated delivery date for a counterfactual. These lines are free, mandatory in any credible checkout, and more native to the work than any bespoke pricing gimmick, because nobody reads them as authored. They read as system.

---

## 6. Register Fidelity

**Verdict: an improvement over Dryness. Insufficient on its own. Subordinate it to Register Variance.**

Three objections.

**It converts a naming problem into a research problem.** Approximate register is worse than no register. A logistics reader detects a fabricated claims code instantly, and once detected, the store's credibility collapses faster than sentimental naming would have collapsed it. Register fidelity requires actual reference documents: real CAPA reports, real conservation estimates, real acoustic specs. If the project is not willing to source those, Dryness was safer.

**It is a recognizable device.** Found institutional language is one of the most heavily worked seams in conceptual art. Applied across 100 SKUs it produces exactly the outcome §7 fears: a polished conceptual database. Register fidelity does not escape house style; it selects a different house style with a longer pedigree.

**Real catalogs are not register-consistent.** This is the decisive objection. A marketplace listing page contains keyword-stuffed titles, terse manufacturer SKUs, badly machine-translated descriptions, chatty small-vendor copy, and inconsistent capitalization, all adjacent. A store where every title is register-perfect is *less* realistic than one with noise, because perfection implies a single author, and a single author is the one thing a store must not have.

**Recommendation: Register Variance over Register Fidelity.** Fidelity governs individual items. Variance governs the catalog. The catalog should contain at least a few titles that are genuinely ugly: over-optimized, keyword-stuffed, poorly translated, redundant. One deliberately bad listing does more for realism than ten well-researched ones.

---

## 7. Temperature Range vs. Cold Correction

**This is the strongest idea in the entire brief and it is currently framed as a warning rather than as the thesis.**

The formulation "one normal commercial system handling objects of radically different emotional, physical, institutional, moral, and conceptual temperatures" is not a caution against overcorrection. It is a better statement of what the artwork is than the current statement seed.

Under this reading:

- The artwork is **the equanimity of the system**, not the products. The products are its material.
- The discomfort is produced by identical treatment of non-identical things. A dented corner, a frequency, and an irreversible harm passing through the same checkout with the same tax line and the same return policy.
- The admission criterion changes from "is this a good product?" to **"does this occupy a temperature the catalog does not yet have?"** This is a stronger criterion because it is not satisfiable by generating more of what already works, which is precisely the format-fatigue failure.
- The dull background stock in §2 becomes structurally necessary rather than pragmatic. Room temperature is a temperature.
- The moral territory becomes necessary rather than optional, because without it the range is truncated at one end.

One caution. Range without calibration is tonal whiplash. There is currently no evidence the project can hold `17,400 Hz` and irreversible moral harm in the same interface without the flatness that makes the first one funny making the second one flippant. That is an empirical question about tone and it can only be answered by building two adjacent product pages and looking at them.

Recommendation: promote this from a warning to the operating thesis, and test it immediately with a two-page adjacency mockup.

---

## 8. Moral Residue as a Territory

### 8.1 Is it genuinely new ontology?

Partly, and the genuinely new element is not the one the brief names.

"Morality" is not new ontology. Philosophy in a product page is a framing, not a thing. What *is* structurally new is **non-transferable obligation**.

Every existing OTHER GOODS product is unownable but imaginatively transferable. You cannot own yesterday, but the fiction of buying it is coherent because commerce's core primitive, transfer, can be pretended. Moral debt is different in kind: it is already assigned, cannot be reassigned, and does not discharge on payment. It is the first material in the catalog that **commerce cannot even pretend to move.** That gives the store something to visibly fail at, which is a stronger position than something to frame.

Keep the ontology. Discard the word "moral."

### 8.2 The source contamination problem

The Nolan essay is an acceptable private ignition source but it must be burned off completely. Two residues to watch:

- **The heroic arc.** Any trace of stages 1–10 in product sequencing makes this a fan-theory artwork with a shopping cart.
- **The therapeutic arc.** Read plainly, the source structure is omnipotence → collapse → love → acceptance → finite action. That is the standard therapeutic recovery narrative. §16 explicitly bans therapy language, and the territory's origin *is* therapy language wearing a film-criticism jacket. The ban and the source are in direct conflict, and the conflict is currently unacknowledged.

### 8.3 The real risk is not sentimentality. It is accusation and appropriation.

The brief worries this territory reopens the sentimental problem. It does not. It opens two worse ones.

**Accusation.** Products about memory implicate nobody. Products about harm implicate the buyer. The moment a listing implies *you did something*, the store stops being flat and starts being a moral instrument pointed at the visitor. Flatness is the entire formal achievement. Do not spend it on a lesson.

**Appropriation.** Unspecified moral residue is abstract and safe. Specified moral residue borrows real suffering as novelty stock. The Oppenheimer lineage in the source makes this an active hazard: any product that reads as adjacent to identifiable historical atrocity converts the work from unsettling to contemptible. Hard rule: **no product in this territory may reference an identifiable event, population, or harm.**

### 8.4 Verdict

**TEST ONLY.** Admit two or three instances into v0.6 as ordinary products. Do not declare a territory, do not name it in any customer-facing or internal-structural way, and do not build a taxonomy branch for it. If the instances survive contact with a built page next to a dented corner, it becomes a territory in v0.7 by evidence rather than by announcement.

---

## 9. Candidate A — `What Payment Cannot Undo`

**Verdict: REWORK. Keep the ontology. Kill the title.**

The ontology is the strongest thing in the new batch. The title is the weakest.

**The title is a proposition, not a noun.** Every strong item in the catalog is a thing or a state: `Yesterday`, `17,400 Hz`, `Unit 12B, Unoccupied`. This is a sentence that states its own thesis on the label. It inverts the central principle. The work becomes immediately understandable and only the act of purchasing is puzzling, which is the opposite of the intended arrangement.

**It names what it claims not to name.** Declining to say "guilt" while saying "what payment cannot undo" is a fig leaf. The abstraction is fully present, just periphrastic.

**It sounds like wall text.** A visitor who reads it knows they are in an artwork. Everything after that is decoration.

### Better names

| Name | Register | Note |
|---|---|---|
| **`Paid in Full`** | Standard billing stamp | Preferred. Real phrase, universally legible, states closure while the item never ships. The irony is entirely structural and entirely unstated. |
| `Balance: $0.00` | Account statement | Purest register fidelity. Slightly colder, slightly less legible on a listing grid. |
| `Account Settled` | Collections / AR | Serviceable, less sharp. |
| `Final Payment` | Installment plans | Weaker; implies a series that does not exist. |

Recommended: **`Paid in Full`**, with a self-referential price (see §11, item 2). Reworked in this form it would rank second in the batch.

---

## 10. Candidate B — `Self-Assigned Responsibility`

**Verdict: DROP as a product. The ontology survives elsewhere.**

This is a category label, not a product. It has no object, no image, no price rationale, and no commerce hook beyond a form field. The proposed data block (Assigned by: Self / Scope: Expanded / Control: Limited) is a spec sheet for an abstraction, which is decorative precision. It is also psychology vocabulary, one register removed from therapy language.

The ontology (accepting liability nobody assigned you) is sound and reappears in stronger concrete form as **`Voluntary Recall`** and **`Non-Transferable Item`** in §11.

Note: this is the weakest candidate on merit but it is not the most dangerous, because obviously weak ideas die on their own.

---

## 11. Candidate C — `Repair Scope: Partial`

**Verdict: REWORK. Sound ontology, unearned numbers.**

Strength: repair and warranty language is genuinely native to commerce, so the register does not have to be imported.

Weakness: **the 18% is arbitrary, and arbitrary precision is decorative precision.** It is the exact failure mode §18 warns about. A number that derives from nothing signals authorship, and authorship breaks the system fiction.

Two fixes, both good:

1. **Derive the number from a countable object.** See `18 of 100 Panels Replaced` in §11. If the fraction is countable, the precision is earned.
2. **Make it a service, not a SKU.** A repair option addable to other orders, which restores a stated fraction and states the remainder as permanent. This is stronger than the product version, and it makes the partiality visible at checkout rather than asserted on a page.

Better names: `Partial Restoration — Estimate`, `Repair Estimate: Partial`, or the concrete panel version.

---

## 12. Candidate D — `Distance to Home: 1,847 mi`

**Verdict: DROP. This is the one to be hardest on.**

It is the most emotionally attractive and the most conceptually empty item in the batch, which is the most dangerous combination available, because attractive weak ideas survive review.

**Commerce does nothing to it.** What does purchase accomplish? If the number decreases, it is a progress bar. If it does not, the store is a display case. Neither is commerce doing work. It fails the Failure Test outright: remove the store and the phrase is unchanged.

**It implies a narrator.** Whose home? The visitor's home is not 1,847 miles away. The number belongs either to nobody, in which case it is meaningless, or to an unnamed homesick protagonist, in which case a character has entered a store that has no characters. Every other product in the catalog is authorless. This one has a person standing behind it, and that person is the artist.

**It is the exact thing §16 forbids.** It works identically in a poetry book. Better, in fact.

Keep the emotional temperature it represents. Find a different carrier.

---

## 13. Candidate E — `Control Over Final Outcome — Unavailable`

**Verdict: KEEP as a system mechanic. Never as a SKU. Rename.**

Correctly identified as system-level. As a SKU it is a punchline delivered once. As a persistent storefront element it is structural, and it is the best idea in the batch.

**Too explicit as worded.** "Control over final outcome" is philosophy vocabulary in a shop window. Real stores say `Protection plan unavailable for this item`, `Not eligible for return`, `Cannot be gift-wrapped`. The move requires **a mundane name with a total implication**. Candidates: `Outcome Assurance`, `Result Protection`, `Outcome Coverage`. Presented as a standard add-on tier alongside ordinary warranty options.

**The critical refinement: availability must vary.** If the option is greyed out identically on every page, it is a joke told forty times. If it is **purchasable for $4.00 on `Upper-Right Corner, Dented in Transit`** and unavailable on the heavier items, then the storefront is making moral and metaphysical distinctions through a warranty dropdown, silently, without commentary. That is the single strongest non-product intervention available to this project.

Rule: it must be genuinely purchasable somewhere, and the copy must never wink.

---

## 14. Candidate Comparison

| Candidate | Product Strength | Commerce Necessity | Accessibility | Freshness | Residue | Risk | Verdict |
|---|---:|---:|---:|---:|---:|---|---|
| Control Over Final Outcome — Unavailable | 4 | 5 | 4 | 4 | 4 | Didactic if named literally; joke if uniform across all pages | **KEEP** (as mechanic) |
| Repair Scope: Partial | 3 | 4 | 3 | 3 | 3 | Decorative precision; unearned numbers | **REWORK** |
| What Payment Cannot Undo | 3 | 3 | 4 | 2 | 4 | Title states its own thesis; reads as wall text | **REWORK** |
| Distance to Home: 1,847 mi | 2 | 1 | 5 | 2 | 3 | Implies a narrator; survives without the store | **DROP** |
| Self-Assigned Responsibility | 1 | 1 | 2 | 1 | 2 | Category label; psychology register | **DROP** |

**Ranking, strongest to weakest as submitted:**

1. Control Over Final Outcome — Unavailable
2. Repair Scope: Partial
3. What Payment Cannot Undo
4. Distance to Home: 1,847 mi
5. Self-Assigned Responsibility

Reworked as `Paid in Full` with self-referential pricing, #3 moves to #2.

---

## 15. Eight Better Instances

Constraints observed: no film IP, no abstract nouns, no inspirational or therapeutic register, no religious merchandise, no poetry-book-portable fragments.

### 1. `Voluntary Recall`
**Concept.** A product the seller recalls after sale, though no customer reported a fault and none exists.
**Why Commerce matters.** The entire product is a post-purchase event: a recall notice arrives by email months later, a refund is offered and is visibly inadequate, and the recall record stays in order history whether or not the item is returned. There is no product page experience worth having. The purchase only exists to make the notice possible.
**Risk.** Reads as brand satire if the notice copy has any wink in it. The notice must be indistinguishable from a real regulatory recall email.

### 2. `Paid in Full`
**Concept.** An account marked settled while what it settled continues.
**Why Commerce matters.** Price is self-referential: the item costs exactly the sum of the buyer's prior orders in this store, and is unavailable to anyone with no purchase history. Commerce is not illustrating the idea, it is computing it. The receipt is the artifact.
**Risk.** Gimmick if the mechanic is explained anywhere. The price must simply appear, correct and unexplained.

### 3. `Statute of Limitations: Expired`
**Concept.** An obligation that is still real and is no longer enforceable.
**Why Commerce matters.** Price decays on a published schedule to $0.00. When it reaches zero the item remains listed, in stock, and purchasable. Free is not discharged, and the store says nothing about the difference. This is the rare case where price logic carries the whole concept and the title carries none of it.
**Risk.** The decay must be visible over real calendar time, which requires the store to persist. Cannot be faked in a mockup.

### 4. `Non-Transferable Item`
**Concept.** The only item in the store that cannot be gifted, resold, returned, or removed from an account once bought.
**Why Commerce matters.** It refuses commerce's founding primitive. Every transfer control on the page is present and visibly disabled, for this item only. The disabled buttons do the work. Nothing is stated.
**Risk.** Currently a rule rather than a thing. Needs a concrete referent sitting under the name, or it becomes a policy exhibit.

### 5. `Restitution — Recipient Unknown`
**Concept.** A payment made toward a party who cannot be identified.
**Why Commerce matters.** Checkout completes normally. Order status reads *Awaiting recipient* permanently. It cannot be cancelled, cannot be refunded, and never fulfills. It is the purest available demonstration of commerce completing a transaction and discharging nothing.
**Risk.** If real money is taken, this is ethically live and possibly legally exposed. Blocked on the money decision in §17.

### 6. `18 of 100 Panels Replaced`
**Concept.** A restoration in which a countable, specified fraction was actually repaired and the remainder was not.
**Why Commerce matters.** Sold per panel. Buy one through eighteen. Nineteen is not available and the cart enforces it. Inventory hard-caps at the repairable fraction, so finitude is expressed as a stock limit rather than as a statement.
**Risk.** Requires a plausible restoration register. Get the conservation vocabulary wrong and it collapses.

### 7. `Corrective Action Completed`
**Concept.** A documented fix, correctly executed, that does not reduce the chance of recurrence.
**Why Commerce matters.** Repurchase is the mechanic. It can be bought repeatedly, each purchase is logged in order history, and the recurrence field on the page never changes value no matter how many are bought.
**Risk.** Inert without a strong product image. This one lives or dies on the photograph.

### 8. `Third-Party Damage, Not Covered`
**Concept.** Documented damage caused in transit by a party who cannot be identified or reached.
**Why Commerce matters.** A real claims form exists and can be submitted. It always returns the same result: no liable party identified. The claim can be resubmitted indefinitely.
**Risk.** Too close to `Upper-Right Corner, Dented in Transit`. It must differ by the absence of a responsible party, not by the damage. If the difference is not immediately legible, cut it.

---

## 16. Product Behavior Sheet — Field Review

### Essential (keep)
- Customer-facing Name
- Price + **Price Logic**
- Inventory + **Inventory Logic**
- Order Confirmation
- Fulfillment
- Order History after six months
- Return
- Repurchase
- **Failure Test**

### Bureaucracy (cut)
- **Commerce Type** — subsumed by the Failure Test. See §3.
- **Product Grammar** — a taxonomy of an unfinished set. Premature and self-confirming.
- **Product Role** — undefined in practice; will be filled with restatements of the concept.
- **Resale if relevant** — optional fields invite padding. Fold into Return, or make it mandatory.
- **Representation logic** — this is not a field. It is a mockup. Replace with an actual page.

### Missing (add, in priority order)

1. **Product Image / Photography Brief.** The largest omission by a wide margin. A store without images is not a store, it is a list. What is a photograph of `Yesterday`? Of `Corrective Action Completed`? This is the hardest unsolved production problem in the project and it appears nowhere in the sheet. Every product needs a specified image approach before it needs a return policy.
2. **Customer Support Script.** What does support reply when a buyer writes "my order hasn't arrived"? Support is the deepest, most human, and most underexploited surface in the whole system, and it is entirely absent.
3. **Reviews.** Prior buyers establish that other people accepted this as a product. Reviews are the cheapest realism instrument available and the most conceptually productive, because a review is a stranger treating the impossible as ordinary.
4. **Tax and Shipping treatment.** See §5.2.
5. **Adjacency / Cross-sell.** "Customers who bought this also bought." Free, invisible, and capable of making claims the product pages cannot.
6. **Second-Visit Test.** What does a bored, unimpressed visitor see? Most products are designed for the ideal reader. The catalog needs at least one field that assumes indifference.
7. **Fulfillment Cost.** Practical and non-negotiable if money moves. Can this obligation actually be met?

---

## 17. Adversarial Critique

Strongest available attacks, in order of force.

**1. The project is producing criticism, not artwork.** Six rounds of evaluation, zero built surfaces. The most probable ending for OTHER GOODS is not failure but a beautifully documented store that never opens. Every additional evaluation round makes this outcome more likely, including this one.

**2. It is correcting toward the taste of a language model.** Four "independent" evaluations sharing training priors is one opinion with error bars. The v0.4 verdict "too sentimental" may be a property of the evaluator class rather than the work. Two versions of correction have now been spent on it. No human stranger has ever been asked.

**3. Systemic complexity is being mistaken for depth.** Price Logic, Inventory Logic, six-month order history, lifecycle sheets. Each is defensible. Together they describe a machine whose intricacy nobody will ever perceive, because visitors do not read systems, they read pages. A visitor's total exposure is roughly twenty seconds on a listing grid and ninety seconds on one product page. The project is optimizing everything except those two minutes.

**4. The Commerce lifecycle is now more interesting than the products, and the honest response is inversion.** If the store is the artwork and products are material, the current method is backwards. Design the system first: checkout, emails, policies, support voice, tax lines. Then let the system demand products. Under that inversion, half the R&D apparatus dissolves.

**5. Register Fidelity is a gimmick with a longer pedigree.** It replaces one recognizable house style with a more heavily-worked one, and it does not touch the underlying generator, which is [precise datum]. The formula survives every proposed rule.

**6. Moral seriousness may be tonally unpayable here.** The flat register that makes `17,400 Hz` quietly funny is the same register that will make irreversible harm read as flippant. §7 claims the range is the point. The counterargument is that range without demonstrated tonal control is whiplash, and there is currently zero evidence the project can hold both. This is the most likely way v0.6 fails.

**7. Twelve to sixteen engineered products makes the store less convincing, not more.** Density is realism. Curation is the tell.

**8. The deepest work is aimed at the smallest audience.** Six-month order history requires an account, a payment, and a voluntary return half a year later. Realistic reach is near zero. See §4.1.

**9. Nobody has decided whether money moves.** Every hypothesis under review is contingent on this and none of them names it. See §17-I below.

---

## 18. Forced Decisions

**A. Should v0.6 reduce to 12–16 products and go deeper?**
**YES**, with correction: 12–16 deep plus 40–60 undesigned background SKUs. Depth and density are not in competition; they are different production tracks.

**B. Should full lifecycle behavior become a core evaluation criterion?**
**YES** — mandatory to specify, optional to be eventful. "Nothing happens" is a permitted and sometimes superior answer.

**C. Should Price Logic be mandatory?**
**YES** as a required field, **NO** as a requirement for distinctiveness. Cap non-trivial pricing at roughly one product in four. Flat and arbitrary is the default and must remain available.

**D. Should Inventory Logic be mandatory?**
**YES**, same qualification. Inventory is currently the most under-exploited and most emotionally active surface in the store.

**E. Is Register Fidelity stronger than the previous Dryness rule?**
**YES**, but it is not sufficient and it does not break the generator. Subordinate it to Register Variance at the catalog level.

**F. Should Moral Residue enter v0.6 as a new territory?**
**TEST ONLY.** Two or three instances, admitted as ordinary products, with no territory declared, no taxonomy branch, and a hard ban on identifiable events or populations.

**G. Should `What Payment Cannot Undo` enter v0.6?**
**REWORK.** Ontology in, title out. Enter as **`Paid in Full`** with a self-referential price.

**H. Which one candidate should definitely NOT enter v0.6?**
**`Distance to Home: 1,847 mi`.** Not because it is the weakest on merit — `Self-Assigned Responsibility` is — but because it is the one most likely to be kept for the wrong reasons. It is emotionally attractive, commercially inert, and it smuggles a narrator into an authorless store.

**I. Single most important unresolved question before v0.6?**
**Does real money change hands?**

Everything downstream is contingent on this and it is named nowhere in the brief. If a visitor cannot actually pay, then Price Logic is decoration, six-month order history has no substrate, returns cannot be issued, and the intended question "what did I just accept as a product?" never fires, because nothing was accepted and nothing was at stake. If a visitor *can* pay, the project acquires real consumer-protection obligations, real fulfillment duties, real refund paths, and real ethical exposure on items like `Restitution — Recipient Unknown`. Both answers are viable. Neither can be deferred, because they specify different artworks.

---

## Overall Verdict

**READY WITH ONE REQUIRED CORRECTION.**

The required correction: **v0.6 must be a built transactional slice, not another document.** Take three products, ideally one warm, one cold, one moral, and build them end to end: listing grid, product page with a real image, cart, checkout with tax and shipping lines, confirmation email, order history, return path. Everything currently under debate becomes decidable in an afternoon once those three pages exist side by side. Nothing currently under debate is decidable in prose.

---

## Strongest Current Insight

§7. One normal commercial system handling objects of radically different temperatures. This is not a caution against overcorrection, it is a better thesis than the current statement seed, and it is the only proposed criterion that cannot be satisfied by producing more of what already works. It reframes the artwork as the equanimity of the system rather than the strangeness of the goods, which makes dull stock necessary, moral stock necessary, and format fatigue structurally impossible.

---

## Biggest Overcorrection Risk

Making every product individually load-bearing. Mandatory Price Logic, mandatory lifecycle, mandatory register fidelity, and a catalog of only sixteen highly-engineered items together produce a store in which nothing is ordinary. Ordinariness is the load-bearing element. A store where every item rewards attention is not a store, and the visitor will read it as a gallery within seconds, at which point the entire formal achievement is spent.

---

## View on Register Fidelity

An improvement over Dryness, adopt it, but demote it. Fidelity governs the item; **variance governs the catalog.** Real commercial listings are register-inconsistent because they have many authors, and inconsistency is the strongest available signal that no single person wrote the store. Deliberately include a few ugly, keyword-stuffed, badly-translated titles. Also note that fidelity done approximately is worse than dryness, because domain readers detect fabrication instantly. If real reference documents will not be sourced, do not adopt this rule.

---

## View on Moral Residue

The valuable thing here is not morality, it is **non-transferable obligation** — the first material in the catalog that commerce cannot even pretend to move. Keep that. Discard the word "moral," discard the ten-stage source structure entirely, and note that the source's arc is the standard therapeutic recovery narrative, which the project has explicitly banned. The real risks are accusation, which spends the store's flatness on a lesson, and appropriation, which converts real suffering into novelty stock. Admit two or three instances as ordinary products. Declare nothing.

---

## Best New Candidate

**Control Over Final Outcome — Unavailable**, reworked as a mundane warranty tier (`Outcome Assurance` or similar) whose availability *varies across the catalog*. Purchasable for $4.00 on a dented corner, unavailable on the heavier items. The storefront then makes metaphysical distinctions silently, through a dropdown, without a single word of commentary. The strongest non-product intervention available to this project.

---

## Weakest New Candidate

**Self-Assigned Responsibility.** A category label with psychology vocabulary, no object, no image, and no commerce hook. Its data block is a spec sheet for an abstraction.

(Distinct from the most *dangerous* candidate, which is `Distance to Home: 1,847 mi` — weak but attractive, and therefore likely to survive.)

---

## One Product You Would Add

**`Statute of Limitations: Expired`** — an obligation that remains real and is no longer enforceable. Price decays on a published schedule to $0.00; at zero the item stays listed, in stock, and purchasable, and free is not the same as discharged. It carries price logic, future tense, non-transferable obligation, and genuine register fidelity simultaneously, and the title states nothing about what it means.

---

## One Methodological Rule You Would Remove

**The Commerce Type trichotomy (Generated / Activated / Displayed).** It is a label applied after a judgment the Failure Test already makes, it produces unresolvable margin arguments, and it changes no downstream design decision. Keep the Failure Test and add one threshold: if the answer is "the framing," it is a caption and does not enter.

---

## One Thing That Must Be Decided Before v0.6

**Whether real money moves.** A simulated store and a transacting store are different artworks with different obligations, different post-purchase substrates, and different ethical exposure. Price Logic, six-month order history, returns, and `Restitution — Recipient Unknown` all mean different things under each answer. Decide it first. Everything else in this document is downstream of it.
