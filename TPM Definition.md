---
tags: [biology, documentation, TPM, template, reference-format]
aliases: [TPM, Taxon Partifunct Manifest, Documentation Template, Organism Documentation]
related: [Taxa and Metrics](Taxa%20and%20Metrics.md), [Taxa](Taxa.md), [TPM Example](TPM%20Example.md)
status: complete
---

# TPM Template - Taxon Partifunct Manifest

**Purpose:** Standardized documentation format for TPIV composite organisms  
**Function:** Records partifunct composition, morphology, ecology, and statistical metrics  
**Usage:** Enables consistent cross-team communication and pattern recognition  
**Format:** Structured reference document for commonly encountered taxa

---

## What is a TPM?

### Standardized Framework

As modular biology continues to reshape our understanding of TPIV lifeforms, field teams require a unified standard for cataloging recurring composite forms. This dispatch introduces the **Taxon Partifunct Manifest (TPM)**—a structured document designed to describe the anatomy, ecological role, and partifunct composition of commonly encountered composite taxa.

This format allows PRXEMA field operatives and research staff to consistently document the modular makeup of functional life-forms, enabling pattern recognition across biomes and facilitating cross-team genomic synthesis.

---

## What a TPM Contains

### Reference Dossier

A **Taxon Partifunct Manifest** is a reference dossier describing:

1. **Observed phenotype** (structure, behavior, ecology)
2. **Partifunct architecture** (dominant modules by domain and function)
3. **Statistical uniformity** ([PSV](Partifunct%20Set%20Variance.md): Partifunct Set Variance)
4. **Morphological diversity** ([MDI](Morphological%20Diversity%20Index.md): Morphological Divergence Index)
5. **Modularity signature** (not a "species," but a recurring successful configuration)

---

## TPM Structure

### Standardized Sections

Each TPM contains the following standardized sections:

**Header:**
- Common name
- Designation code
- Ecological classification
- Location/biome
- PSV and MDI values

**Core Partifunct Set:**
- Tracked partifuncts representing ~90% of body mass
- Domain and function classification
- Subtype designations
- Role in organism

**Morphology & Sensory Layout:**
- Visual anatomy description
- Structural variance patterns
- Sensory organ configuration
- Distinctive features

**Ecological Notes:**
- Feeding strategy
- Locomotion mode
- Reproduction method
- Herd/social behavior
- Habitat preferences

**Expression Metrics:**
- PSV analysis (population consistency)
- MDI analysis (morphological variation)
- Sample size
- Geographic/temporal variation

**Dispatch References:**
- Crosslinked documentation from prior fieldwork
- Supporting observations
- Related taxa

---

## Template Format

### Standard TPM Layout
```markdown
---
TPM-[CODE]
---

# [Common Name]

**Designation:** TPM-[CODE]
**Classification:** [Functional Category]
**Biome:** [Primary Habitat]
**PSV:** [Percentage] (±1σ)
**MDI:** [Index Value]

---

## Partifunct Snapshot

| Domain | Function | Subtype | Role |
|--------|----------|---------|------|
| ST | LMB | LIGN1 | Leg Segments |
| IN | DGV | HERB2 | Digestive Tract |
| RS | LUN | MULT1 | Lung Clusters |
| CN | MOTO | CORE4 | Motor Control |
| SN | VIS | STD2 | Visual Sensors |
| WP | WMB | STDX4 | Womb Partifunct |

---

## Morphology

**Body Plan:**
[Description of typical configuration]

**Size Range:**
[Dimensions]

**Distinctive Features:**
[Notable characteristics]

**Variation:**
[Common morphological variants]

---

## Ecology

**Feeding:**
[Diet and feeding strategy]

**Locomotion:**
[Movement patterns]

**Reproduction:**
[Reproductive behaviors]

**Social Structure:**
[Herd/pack/solitary patterns]

**Habitat:**
[Preferred environments]

---

## Expression Metrics

**PSV Analysis:**
[Percentage] of sampled individuals (n=[number]) share core partifunct set within ±1σ

**MDI Analysis:**
[Index] on standard scale, indicating [interpretation]

**Geographic Variation:**
[Regional differences if noted]

**Temporal Variation:**
[Seasonal changes if applicable]

---

## Dispatch References

- [[D###-Title]] - [Brief description]
- [[D###-Title]] - [Brief description]

---

## Notes

[Additional observations, anomalies, research priorities]

```
## Example TPM

### [Sample: Zebra Grazer](MagnaGrazerGuild.md)

**Designation:** `TPM-ZG-LGW-Hx`  
**Classification:** Grazer, Walker—Large Ground Weight, Hexapedal  
**Biome:** Magna Steppe  
**PSV:** 83% (±1σ)  
**MDI:** 2.8

### Partifunct Snapshot

| Domain | Function | Subtype | Role |
|--------|----------|---------|------|
| ST | LMB | LIGN1 | Leg Segments |
| ST | PAD | SPLT1 | Ground Adaptation |
| IN | DGV | HERB2 | Digestive Tract |
| RS | LUN | MULT1 | Lung Clusters |
| CN | MOTO | CORE4 | Motor Control |
| WP | WMB | STDX4 | Womb Partifunct |

*[See full example at [MagnaGrazerGuild](MagnaGrazerGuild.md)]*

---

## Usage Guidelines

### When to Create TPM

**Create TPM for:**
- Commonly encountered taxa (observed 10+ times)
- Ecologically significant organisms
- Taxa with stable PSV (>60%)
- Reference organisms for comparative studies

**Don't Create TPM for:**
- Single observations (document in field notes)
- Highly variable assemblages (PSV <30%)
- Transitional/intermediate forms
- Until sufficient data collected (n>20 individuals)

---

### Updating TPMs

**TPMs are Living Documents:**
- Update when new populations discovered
- Revise PSV/MDI with larger sample sizes
- Add regional variants
- Note seasonal/temporal changes
- Cross-reference new dispatches

**Version Control:**
- Include date of last update
- Note major revisions
- Maintain changelog (if significant changes)

---

## Research Applications

### Cross-Team Communication

**Standardization Benefits:**
- All teams describe organisms consistently
- Easy comparison across biomes
- Pattern recognition enhanced
- Data aggregation simplified

**Field Reference:**
- Quick identification guide
- Expected partifunct set known
- Variation ranges documented
- Ecological role understood

---

### Evolutionary Studies

**Track Changes:**
- PSV/MDI drift over time
- New partifunct incorporations
- Geographic divergence
- Response to environmental shifts

**Comparative Analysis:**
- Similar taxa across continents
- Convergent assemblages
- Partifunct reuse patterns
- Ecological equivalents

---

## Limitations

### What TPM Cannot Capture

**Static Snapshot:**
- Represents current observation
- May not capture full variation
- Seasonal changes require updates
- New populations may differ

**Individual Variation:**
- TPM shows average/typical
- Outliers exist
- Novel assemblages possible
- Intermediate forms not captured

**Non-Statistical:**
- Qualitative descriptions subjective
- Observer bias possible
- Requires sufficient sample size
- May oversimplify complexity

---

## Navigation

**Core Concepts:**
- [Taxa and Metrics](Taxa%20and%20Metrics.md) - Metrics used in TPM
- [Taxa](Taxa.md) - What TPMs document
- [Partifunct Core Definition](Partifunct%20Core%20Definition.md) - Building blocks

**Examples:**
- [TPM Example](TPM%20Example.md) - Complete example
- [TPIV Taxa](TPIV%20Taxa.md) - All documented TPMs
- [see worked example](TPM%20Example.md)

**Related Topics:**
- [Taxa and Metrics](Taxa%20and%20Metrics.md) - How organisms are named
- [Partifunct Domain & Function Table](Partifunct%20Domain%20&%20Function%20Table.md) - Partifunct catalog
- [Taxa and Metrics](Taxa%20and%20Metrics.md) - Classification codes

**Related Dispatches:**
- [B014 – Taxon Partifunct Manifest](Dispatches.md#b014) - Original format design
- [B014 – Taxon Partifunct Manifest](Dispatches.md#b014) - Field testing results

---

*"Before TPM, every team described organisms differently. Now we have a common language. When someone says 'TPM-ZG,' we all know exactly what they mean."*
*— Dr. James Kim, Field Coordination, Day 58*