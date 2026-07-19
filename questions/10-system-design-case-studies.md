# 10. System Design / Case Studies

Open-ended, senior-level scenarios synthesizing themes across the entire repo. As with the format established in other repos in this series, these are typically extended discussions rather than questions with one correct answer — evaluate reasoning quality, appropriate skepticism, and whether biological, structural, materials, and business considerations are integrated together rather than treated as separate silos.

---

### 10.1 🔴 Design the end-to-end process you would follow for a client project: designing a lightweight, structurally efficient roof canopy structure for a large outdoor public gathering space, with a client brief that explicitly requests "genuine biomimetic design, not just something that looks natural."

**What a strong answer covers:**
- Starting from the performance-criteria-driven approach discussed in category 2.14 — establishing specific structural, spanning, weight, budget, and manufacturability requirements before selecting any biological reference.
- A structured biomimetic search (category 2.4-2.5) reframing the engineering challenge in functional terms (long-span, lightweight, load-efficient overhead structure) rather than starting from an appealing organism.
- Should identify genuinely relevant candidate biological references with real structural mechanics grounding — likely candidates include form-active shell/membrane structures (category 3.6-3.7), branching load-path structures (category 3.16, tree canopy structural logic), or spider web tension-network structures — and should explicitly evaluate multiple candidates rather than fixating on the first appealing option (category 2.7).
- Should explicitly plan for topology optimization / computational design (category 7) informed by the chosen biological principle, not treating the biological reference as the final geometry.
- Should address manufacturability early (category 5.7, 5.16) given the "lightweight, structurally efficient" requirement likely implies complex geometry.
- Should propose a testing/validation plan appropriate to a real public structure (category 8, including the code-compliance/alternative-means pathway discussed in category 6.11, since a genuinely novel structural system for a public assembly space is a safety-critical application).
- A strong answer explicitly addresses how they'd honestly communicate to the client whether the final design achieves genuine functional biomimicry versus where it might necessarily diverge from strict biological fidelity for manufacturability/cost reasons (category 4.19, 2.9) — resisting the temptation to overstate biomimetic purity to satisfy the client's stated preference if the actual engineering reality is more nuanced.

---

### 10.2 🟡 A structural engineering firm without prior biomimetic design experience wants to build internal capability in this area. What would you recommend as a first project, and why?

**What a strong answer covers:**
- Should recommend starting with a project that has a well-validated, well-established biological principle (echoing the rigor distinctions drawn throughout category 1, favoring examples like the Eastgate Centre-style passive ventilation principle, or straightforward material-grading/topology-optimization work, over more speculative or less rigorously validated biological references) rather than an ambitious, novel research-stage biomimetic material or structural system.
- Should recommend a project scope where failure or underperformance carries manageable, non-safety-critical consequences (echoing the risk-appropriate scoping discussed in adjacent safety-critical engineering contexts) — a smaller-scale, non-structural or lower-stakes application (an interior feature, a non-load-bearing facade element) rather than a primary structural system for a firm's first biomimetic project.
- Should emphasize building genuine interdisciplinary capability (category 2.6) as part of this first project, not just having engineers work from secondary sources — potentially bringing in external biomechanics/biology consulting expertise for this first project specifically to help establish good habits and avoid the common pitfalls discussed throughout category 1 and 2.
- Should propose using this first project explicitly as a learning and internal-methodology-building exercise (developing the firm's own structured design process discussed in category 2, its own biomimetic reference library per category 2.10, and its own computational/testing workflow) rather than treating it purely as a one-off deliverable.

---

### 10.3 🔴 You're reviewing a colleague's biomimetic structural design proposal before it goes to a client. The proposal is visually striking and well-presented, directly referencing a specific organism's structure, but on closer technical review, you're not confident the actual structural mechanism claimed is well-supported by the cited biological research, and the computational validation seems to rely on a single, favorable load case. How do you handle this review?

**What a strong answer covers:**
- Should treat this as a legitimate, important technical review responsibility rather than something to soften or avoid raising because the proposal is visually compelling or the colleague may be invested in it — echoing the intellectual honesty and rigor themes discussed throughout category 1.20, 2.9, and 8.15.
- Should specifically and concretely trace the biological claim back to its cited source (per the evaluation process outlined in category 1.20) rather than raising a vague, unsubstantiated concern — being able to point to exactly what's under-supported or overstated in the biological claim.
- Should specifically flag the single-load-case validation gap as a genuine technical risk (per category 7.6 and 8.13's discussion of the importance of comprehensive, multi-load-case and combined-loading validation), not just a stylistic preference for more thorough analysis.
- Should propose a constructive path forward — specific additional validation, computational analysis, or literature review needed to either substantiate or appropriately revise the claim — rather than simply rejecting the proposal outright.
- Should handle the interpersonal dimension professionally and collegially (echoing the constructive feedback principles found throughout well-run engineering review processes), focusing on the technical substance and the shared goal of the proposal actually being sound before it reaches the client, not on criticizing the colleague personally.

---

### 10.4 🟡 A manufacturer wants to develop a new consumer product (e.g., a bicycle helmet, a piece of protective sports equipment) using biomimetic principles for impact energy absorption. Walk through how you'd approach identifying and validating a suitable biological reference.

**What a strong answer covers:**
- Should apply the dynamic-versus-static distinction discussed in category 1.19 and 3.17 — recognizing that impact energy absorption is fundamentally a dynamic loading problem requiring dynamic-specific biological references and dynamic-specific testing methods, not static structural analysis alone.
- Should identify genuinely well-validated biological impact-resistance references (mantis shrimp club structure and certain other well-studied impact-resistant biological structures have more robust research support than some more popularly-cited but less rigorously validated examples) and should specifically apply the skepticism/verification process discussed in category 1.18-1.20 to whatever specific biological claim is being considered, given how frequently impact-protection biomimicry claims (echoing the woodpecker example) circulate with varying degrees of actual scientific rigor behind them.
- Should propose an appropriate dynamic/impact testing validation plan (category 8, particularly emphasizing that impact/dynamic testing requires specific test methods distinct from the static/fatigue testing discussed elsewhere) with direct comparative benchmarking against existing, currently-used conventional protective equipment materials and designs (category 8.9), since a consumer safety product absolutely requires demonstrating genuine, quantified improvement over existing solutions, not just an interesting biological narrative.
- Should address relevant product safety certification/regulatory requirements specific to protective equipment (echoing the code-compliance and novel-system validation challenges discussed in category 6.11, applied to a consumer product safety certification context rather than a building code context).

---

### 10.5 🔴 Two team members disagree on a biomimetic structural material research project: one believes the team should continue pursuing a promising but still lab-scale-only material because its performance data looks excellent, while the other is concerned the team hasn't seriously validated the scale-up/manufacturability pathway and is at risk of over-investing in a direction that may prove impractical at production scale. How would you help resolve this disagreement?

**What a strong answer covers:**
- Should take both positions seriously as reasonable — echoing the balanced disagreement-navigation approach modeled in other repos in this series — rather than assuming either team member is simply right.
- The continue-pursuing position's legitimate case: excellent lab-scale performance data is genuinely valuable and worth further investment to understand fully, and prematurely abandoning promising research based on unproven scale-up concerns (rather than actual demonstrated scale-up failure) could mean walking away from a genuinely valuable direction too early.
- The scale-up-concern position's legitimate case: echoing category 4.14's discussion of scale-up as one of the most common bottlenecks in this field specifically, continuing to invest heavily in refining lab-scale performance without in parallel seriously investigating scale-up feasibility risks significant wasted investment if scale-up ultimately proves impractical — and the earlier this is investigated, the earlier that risk can be identified and addressed or the project appropriately redirected.
- A strong answer proposes a resolution structured around explicitly and concretely investigating the scale-up question in parallel with (not instead of) continued lab-scale refinement — echoing the "least capability sufficient" and early-risk-identification principles discussed in adjacent safety/research-management contexts — rather than treating this as a binary choice between the two team members' positions, and should note that this kind of parallel-track de-risking approach is a common, sensible resolution to this exact category of disagreement in applied research management generally.

---
