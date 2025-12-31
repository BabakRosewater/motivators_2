Overview (Repo: motivators_2)

This workspace contains a single Git repository (motivators_2) with three CSV data sources that define the six core sales motivators and how they map to vehicle-level messaging.

Data files in this repo

1) core_motivators.csv — Core motivator definitions
Defines the six motivators (by motivator_number), including tagline, definition, buying-behavior signals, and a suggested sales cue question.
Purpose: the stable “meaning layer” that does not depend on a specific vehicle.

2) model_level_motivators.csv — Model/year motivator mappings
Maps motivators to specific models/years (and trims/paths) including recommended trim paths, customer-facing adjectives, feature anchors, proof points, and usage notes.
Purpose: the primary “what to say for this vehicle + motivator” layer.

3) vehicle_customer_facing_adjective_overlays.csv — Channel-specific overlays
Provides channel-specific language overlays (ex: email/text/any) for a given model/year (and optionally trim), allowing you to adjust customer-facing adjectives (and any optional positioning fields you include) without rewriting the base model mapping.
Purpose: a flexible “presentation layer” applied last to tailor language by channel/context.
