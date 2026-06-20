# Horizon Cubox Site

This repository is the publish target for Horizon daily essay pages that are later saved into Cubox.

Generated pages are written to:

- `horizon/horizon-daily-YYYY-MM-DD.html`

The recommended publish flow is:

1. Generate and publish with `bash scripts/sync_horizon_cubox.sh YYYY-MM-DD`
2. Commit the updated HTML in this repository
3. Push to the remote Pages repository
4. Let Cubox save the resulting public URL
