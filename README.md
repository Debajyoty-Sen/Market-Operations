# Diagnosing Contextual Content Moderation Gaps in the India–Bengali Market

## Executive Summary

Contextual offensive content in the Indian–Bengali market is systematically under-detected, leading to delayed enforcement and silent harm.

- AI moderation avoids over-flagging benign content but misses a significant share of offensive posts
- Missed content remains live ~2× longer, increasing user harm
- Risk concentrates in comments, crisis periods, and contextual content
- Market-specific operational interventions are required to close the gap

---

## Content Volume Distribution

### High-volume, user-generated content dominates the moderation workload

<img width="580" height="509" alt="volume by type" src="https://github.com/user-attachments/assets/d895a106-a3c4-45b2-b8b1-0f1d4202597b" />


- **Comments ≈ 50%** of total content volume
- **Posts (~30%)** and **Ads (~15%)** form smaller shares
- User interactions, not ads, drive moderation exposure

---

## Platform Risk Profile

### Facebook carries higher and more diverse moderation risk than Instagram

<img width="580" height="511" alt="platform vs content type" src="https://github.com/user-attachments/assets/eae8a1db-12b0-42ab-8b6a-289379461ccc" />

- Facebook dominates overall volume and content diversity
- Instagram is comment-heavy, amplifying conversational risk
- Platform mix affects how enforcement capacity must be allocated

---

## Content Classification

### Most content is socially or politically expressive, limiting keyword-based detection

<img width="432" height="411" alt="dist of text categories" src="https://github.com/user-attachments/assets/655b0a91-afc3-4bbd-b344-799706206d3a" />
<img width="576" height="494" alt="offensive content rate by text category" src="https://github.com/user-attachments/assets/3958566b-c770-489c-b6b6-bd551beea7d5" />



**Nearly 50% of content is politically or meme-tically expressive**

These categories rely heavily on context, tone, and implication, not explicit abuse.

**Key insight:** Offensiveness is not confined to "expected" categories — even neutral-looking content carries risk.

---

## AI Detection Performance

### AI moderation avoids false positives but fails to catch a large share of offensive content

<img width="567" height="516" alt="ai flagging effectiveness vs ground truth" src="https://github.com/user-attachments/assets/e28e1ed6-a6dc-4bba-9cf3-dd4132798871" />


- **For non-offensive content:** AI correctly leaves ~90% unflagged
- **For offensive content:** AI misses ~40–45%

**Analysis:** Indicates high precision, low recall

The system is conservative by design — but this creates silent exposure risk.

---

## Crisis-Category Risk Intersections

### Detection failures intensify at specific category × crisis intersections

<img width="543" height="455" alt="false negative heatmap category X crisis" src="https://github.com/user-attachments/assets/81406691-c751-41df-9ccd-d569eb0beabd" />


**Highest false-negative risks:**
- Neutral × Protest (~0.56)
- Meme × Protest (~0.56)
- Neutral × Election (~0.53)

**Lowest risk:**
- Social × Election (~0.38)

**Key findings:**
- Seemingly benign or humorous content becomes dangerous in volatile contexts
- AI struggles most when context flips meaning

---

## Time-to-Action Analysis

### AI misses significantly increase time-to-action, extending user harm

<img width="571" height="455" alt="time to action impack of Ai misses" src="https://github.com/user-attachments/assets/4d3d68cc-8cab-4a30-9ece-57463d664e1a" />


**No false negatives:**
- Median TTA ≈ 20 hours
- Tight distribution, low variance

**False negatives:**
- Median TTA ≈ 40 hours
- Long tail up to 120 hours

**Impact:** Missed content stays live 2× longer, compounding harm during sensitive periods.

---

## Silent Harm Distribution

### High-volume comment streams are the largest source of undetected harm

<img width="571" height="509" alt="silent harm by content type" src="https://github.com/user-attachments/assets/4882efa3-8916-43eb-ad45-369328ad4a1e" />


**Silent harm cases:**
- **Comments:** ~350
- **Posts:** ~200
- **Ads:** ~100

**Analysis:** Scale + conversational dynamics make comments hardest to police. Reliance on user reporting is insufficient.

---

## Recommended Resolution

### Market-specific, context-aware operations can materially reduce risk without over-enforcement

### Contextual Risk Routing
Prioritize human review for:
- Comments
- Meme & Neutral content
- Protest & Election periods

### False-Negative Monitoring
- Track category × crisis risk patterns as operational KPIs
- Use these signals to guide escalations

### Crisis Playbooks
- Expect higher false negatives during crises
- Pre-emptively allocate review capacity

### Expected Outcomes
- Faster time-to-action
- Reduced silent harm
- Lower escalation risk

---

## Author

[Debajyoty Sen]
