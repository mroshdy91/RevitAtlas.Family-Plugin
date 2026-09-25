# Geometry and interfaces

Use native constraints and dependency propagation before reconstructing geometry. Discover the exact action schema and existing native identities before guarded association replacement.

For circular form creation, `atlas_family_forms.create` can bind circles, extents, material and visibility in the same action. Circle selectors use the known initial native center/radius and must resolve to one complete logical circle. Create-and-bind rolls back as a group if a binding fails; successful construction still needs a physical behavior check.

For an existing curved/general profile, inspect `profile_constraints`, actual sketch identities and the owned-anchor hash. Release only the listed Atlas-owned anchors. A logical circle can contain multiple arcs: control the radius and center of all constituents. Endpoint, edge and bounded-arc radius constraints remain native relationships. A center-only correction should not add an empty, unrelated size-constraint stage.

Test centered round and rectangular features at multiple requested dimensions. Compare actual center coordinates and min/max bounds with the pipe, flange or other controlling datum. Correct width/radius alone does not prove centering. Use `atlas_family_test.sequence_probe` for cumulative changes with independently calculated bounds/volume expectations; isolated restoring samples can miss solver drift. Probe restoration and final saved reopening are separate checks.

Selection bounds can include reference geometry far outside the physical solids. Before moving a connector that appears remote, inspect its actual origin/direction and compare physical bounds with native reference-plane extents and priorities. On an admitted `reference_roles_v1` engine, inspect current priorities before guarded `atlas_family_constraints.edit`. Use Not a Reference for private construction references when appropriate; retain intentional public center/face references. Do not shrink physical geometry merely to make zoom-to-selection look correct. Recheck dimensions, physical volumes, connectors, selection behavior and save/reopen after a role correction.

`atlas_family_test.sequence_probe` can test geometry and formula-driven visibility together. Expectations can use volume with an explicit tolerance, bounds, and/or `visible`. A visibility-only expectation needs no artificial volume check. `visible` proves native visibility-parameter propagation, not the rendered appearance in every view. `atlas_family_test.components_visibility_probe` verifies the direct association to its specified control. Choose summary readback for compact evidence.

Use `atlas_family_components.nest_on_plane` only for a supported work-plane family with the intended reference-plane host, coplanar location, tangent direction and normal. Inspect actual host/orientation after substitution. `atlas_family_components.extract` preserves provenance for an editable inherited nested family; use guarded reload after editing the owned copy. Reload cannot silently change placement type.

For connectors, inspect native origin, outward direction and size independently of geometry. Test both connection ends after changing length, size and side-specific controls. A connector diameter association does not resize the physical bore. Project connection claims require an actual compatible placed-family connection test.

Native `cuts_geometry` controls whether a void cuts; visibility does not. Independently positioned parametric voids are available for drilling patterns where native arrays are unsupported. Do not infer general radial-array or helical-thread support from circular forms. Preserve an explicit decision to defer thread detail.
