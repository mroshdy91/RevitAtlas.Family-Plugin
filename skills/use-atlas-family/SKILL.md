---
name: use-atlas-family
description: Create, edit and verify native loadable Revit families through Atlas Family, paired with Atlas Core for work identity, inspection, review and delivery.
---

Pair this plugin with the matching Atlas Core release. If connection is unavailable, follow Core's setup reference. Do not install a second engine, change credentials or substitute an older runtime.

# Atlas Family

Use Atlas Core to discover the session, create the owned work item, retain engineering intent and recover operations. Request the exact Family action contract through `atlas_catalog`; reuse it when known.

Native family geometry, parameters, references, components, representation and specialized interfaces belong to this surface. Ordinary families do not require MEP checks. Work IDs and revisions must come from the paired Core connection.

Check Core status and the current action contract for the connection profile, engine compatibility and capability limits. A mapped action returning `MIGRATION_PENDING` is unavailable for that connection. Preserve the requested native behavior and report missing capability; imported geometry cannot substitute for an explicit parametric requirement. Core checked scripting has separate declared scope and admission and does not bypass these limits.

Preserve source files and separate engineering expectation from implementation and evidence. Use native reference and parameter keys in constrained forms; flex every requested type and probe requested controls before review. Inspect existing associations before replacing them. Imported/static content cannot satisfy native parametric requirements without demonstrated behavior. Optional connectors, adaptive and structural operations retain their own applicability.

Imported saved work keeps its original intent and baseline but needs fresh bindings and acceptance. Resume copied projects, reload the current family, and inspect preserved instance identities. Core owns image judgment (`atlas_review.record`) and delivery (`atlas_deliver.complete`); Family owns placed-family operations. A native mutation or image does not mean the whole brief passes. Complete family and imported-family delivery workflows have targeted qualification; this does not establish every family/template combination or broad release readiness.

Before parameter definitions, inspect native types and use `atlas_family_parameters.ensure_type` to create the first named type or explicitly reuse a source type. This preserves values and prevents accidental default-type rebuilds. Existing types are not silently deleted.

For requested resizing, movement or independent controls, load `atlas_catalog` workflow `behavior_first` and [behavior-first construction](references/behavior-first.md). Prove the hardest behavior on one feature before detailing the whole assembly. Parameter inspection's `control_summary` distinguishes direct roles; associations still require measured tests.

Semantic formulas use `@{width} / 2`; explicitly selected native syntax uses the actual Revit name, such as `Width / 2`. Discover existing reference keys before defining new ones. For a centered or anchored object, check position as well as dimensions at each requested type; correct width alone cannot prove centering. Use targeted `atlas_inspect.measure` with `targets` to avoid measuring unrelated template content.

Preserve authored formula expressions: Revit's inspected formula text can round unit literals and is not a lossless backup for reassignment. Use the typed lookup-table import/replace operation, then compare dependent numeric values and relevant physical behavior across affected types. Unchanged displayed formula strings alone do not prove preserved precision.

Before delivery, inspect parameter controls and state which values drive solid geometry, connectors, materials or visibility, and which are informational. Label unprobed behavior and project use as untested; fixed geometry plus a parameter named Diameter is not a resizable family. If resizing was requested, metadata cannot satisfy it. For a generic single-size brief, disclose the chosen size, fixed geometry and source assumptions in the final handoff.

For known related edits, use admitted Core execution plans under the installed Core skill's execution-plan guidance. Discover eligibility before selecting grouped reads or an atomic transaction. A checkpointed plan retains completed stages on later failure. Historical Family batches remain recoverable through `atlas_operation`; their separately committed stages do not imply whole-batch rollback. Recover the parent after interruption and inspect partial completion before planning more edits.

For compound construction, profile constraints, reference roles, nested hosts or connector placement, read [geometry and interfaces](references/geometry-and-interfaces.md). It covers the distinction between physical bounds and selection bounds, including remote construction references.

Request compact results when only a revision is needed. For measurement, use `atlas_family_forms.inspect` with explicit targets and fields; omitted measurements are unreported, not zero. Request full profiles only when needed for a constraint or diagnosis. A supported create-and-bind action can avoid a separate identity-discovery call.

For scheduled area, mass or welded volume, read [assembly quantities](references/assembly-quantities.md). Define the requested assembly/exposure scope before choosing formulas and verify the resulting native schedule values across configurations.
