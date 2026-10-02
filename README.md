# Y.O.L.I. OpenClaw runtime builder

This public repository contains only a workflow that fetches the public OpenClaw repository at the pinned commit `c5fb142dd49abe1447d21b644aed6ea80b85df0f`, builds its documented runtime image with declarations disabled, and publishes a commit-tagged image to GHCR.

It contains no private Y.O.L.I. source, credentials, or personal data. The workflow is manual, never uses `latest`, and uploads the resulting image manifest digest as an artifact.
