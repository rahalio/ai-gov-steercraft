# Steercraft — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Mission operator / science planner

- As a mission operator, I want sentinel alerts ranked by predicted mission impact, so that I spend the pass on what matters.
- As a science planner, I want a steering proposal tied to the correlation or anomaly that justified it, so that I can approve or reject with context.
- As an operator, I want predictions marked when measurement is stale, so that I do not uplink on a false sense of currency.

### Autonomy / data scientist

- As a data scientist, I want to publish a sentinel with an explicit false-positive budget, so that alarm fatigue is a managed contract.
- As an autonomy engineer, I want association-rule and graph discoveries registered as insight objects, so that they can drive predictions without living only in notebooks.
- As an engineer, I want drift and generalisation metrics on every production sentinel, so that we know when to retrain before the rover acts wrongly.

### Anomaly duty officer / safety reviewer

- As a duty officer, I want suppressed alerts itemised with rationale, so that silence is auditable.
- As an anomaly board chair, I want the full MIPS chain for any unexplained vehicle act, so that we can distinguish sensor fault from model drift from unlawful autonomy.
- As a safety reviewer, I want bounded-autonomy steering to hard-stop outside its envelope, so that AI cannot expand its own authority.

### Principal investigator / archive curator

- As a PI, I want citable provenance from measurement through steering, so that science claims survive review.
- As an archive curator, I want graph entities linked to repository DOIs, so that association discoveries remain reproducible after the campaign ends.

### Platform administrator

- As a platform administrator, I want authorisation tiers enforced per mission, so that one team’s supervised mode cannot silently become another’s unsupervised mode.
- As an administrator, I want uplink conflict detection against the activity plan, so that steered commands do not collide with human-planned sequences.
- As a compliance officer, I want export-control tags on telemetry-derived features, so that models do not leak controlled content into uncleared environments.
