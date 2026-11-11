# Gladoss Enterprise Clients (Data Buyers)

Goal: license Gladoss-curated de-identified clinical datasets to AI labs, pharma, and biotech.

## Buyer Categories

### AI Labs & Foundation Model Companies
- Need: domain-specific clinical text for LLM training and evaluation
- Pain: hospitals won't share raw data; they need compliant, structured, labeled sets
- Angle: Gladoss supplies ready-to-train physician-note datasets with ground-truth outcomes

### Pharma & Biotech
- Need: real-world evidence, disease progression patterns, trial feasibility
- Pain: synthetic or claims-only data lacks clinical reasoning depth
- Angle: longitudinal free-text notes show how doctors actually work through symptoms and treatment

### Digital Health / AI Scribe Companies
- Need: benchmark data and training corpora for ambient documentation tools
- Pain: hard to get consented, de-identified visit data at scale
- Angle: Gladoss pipeline already handles Safe Harbor + Expert Determination

## Known Market Anchors (Nov 2026)
- Tempus AI: disclosed $100 per de-identified neurology record to Pathos (500K records, Oct 2026 8-K)
- Mercor: $80K-$820K per medical practice; $100K-$900K per digital health company; $50M+ paid out
- OneMedNet: $11.5M+ contract for millions of de-identified records for foundation model training
- BioStack: $9.5M seed (Peak XV), 100M+ de-identified records across US/India/Brazil/Argentina
- Segmed: 2,800+ partner sites, 150M+ imaging studies
- TriNetX: 800M+ clinical notes, targeting ~1B by end of 2026
- Truveta: 120M+ patients, launching Truveta Genome Project (10M patients)
- Nightingale Open Science: 40TB labeled medical imagery, free to use
- HealthVerity: claims/records/lab exchange, revenue share to suppliers
- Gradient Health: imaging revenue share (~20% to partners; $240K example from $3M deal)
- Defined.ai: 20-30% of deal value to content owners; $1-2 per image

## Pricing Benchmarks
- Per-record: ~$100 (Tempus neurology example)
- Per-practice license: $80K-$820K
- Per-image: $1-2; per hour of film: $100-300
- Revenue share to data suppliers: typically 20%

## Gladoss Differentiation
- Starts with small independent practices the big buyers ignore
- Privacy-first positioning matches physician distrust (86% cite data privacy concerns)
- Open-source pipeline builds trust vs. closed black-box aggregators
- Focus on free-text notes (the highest-value, hardest-to-source asset) rather than imaging

## Risks to Manage
- Re-identification risk on rare conditions / small cohorts
- 42 CFR Part 2 (behavioral health) — exclude entirely
- Payer contract terms may restrict downstream licensing
- State privacy laws beyond HIPAA (California CMIA)
- Models can memorize training text — pre-ingestion de-identification is non-negotiable