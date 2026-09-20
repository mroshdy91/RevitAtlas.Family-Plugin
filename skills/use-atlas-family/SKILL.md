---
name: use-atlas-family
description: Create, edit and verify native loadable Revit families through Atlas Family, paired with Atlas Core for work identity, inspection, review and delivery.
---

If Atlas tools cannot connect, follow the installed Atlas Core skill's agent-assisted installation reference. When setup is authorized, the agent runs Core's packaged helper; do not ask the user to configure tokens or install another Family engine. If Core is absent, install it through the selected marketplace first.

# Atlas Family

Use Atlas Core to discover the session, create the owned work item, retain engineering intent and recover operations. Request the exact Family action contract through `atlas_catalog`; reuse it when known.

Native family geometry, parameters, references, components, representation and specialized interfaces belong to this surface. Ordinary families do not require MEP checks. Work IDs and revisions must come from the paired Core connection.

The compatible Core runtime admits fixed typed family routes. Check Core status and the current action contract for the connection profile, engine compatibility and capability limits; restricted migration-subset connections can admit fewer actions. A mapped action returning `MIGRATION_PENDING` is unavailable; do not substitute imported geometry, arbitrary scripts or a weaker requirement. Report the missing capability honestly.

Preserve source files and separate engineering expectation from implementation and evidence. Use native reference and parameter keys in constrained forms; flex every requested type and probe requested controls before review. Inspect existing associations before replacing them. Imported/static content cannot satisfy native parametric requirements without demonstrated behavior. Optional connectors, adaptive and structural operations retain their own applicability.

Imported saved work keeps its original intent and baseline but needs fresh bindings and acceptance. Resume copied projects, reload the current family, and inspect preserved instance identities. Core owns image judgment (`atlas_review.record`) and delivery (`atlas_deliver.complete`); Family owns placed-family operations. A native mutation or image does not mean the whole brief passes. Complete family and imported-family delivery workflows have targeted qualification; this does not establish every family/template combination or broad release readiness.

Before parameter definitions, inspect native types and use `atlas_family_parameters.ensure_type` to create the first named type or explicitly reuse a source type. This preserves values and prevents accidental default-type rebuilds. Existing types are not silently deleted.

For requested resizing, movement or independent controls, load `atlas_catalog` workflow `behavior_first` and [behavior-first construction](references/behavior-first.md). Prove the hardest behavior on one feature before detailing the whole assembly. Parameter inspection's `control_summary` distinguishes direct roles; associations still require measured tests.

Before delivery, inspect parameter controls and state which values drive solid geometry, connectors, materials or visibility, and which are informational. Label unprobed behavior and project use as untested; fixed geometry plus a parameter named Diameter is not a resizable family. If resizing was requested, metadata cannot satisfy it. For a generic single-size brief, disclose the chosen size, fixed geometry and source assumptions in the final handoff.
