# busybox-static-webserver

Minimal static-file container: busybox `httpd` (busybox 1.36.x), built from source in a
multi-stage `Dockerfile` (build config in `.config`, server config in `httpd.conf`), served
from a `scratch` image on port 3000.

## Build & deploy

- **No build automation.** The `ghcr.io/pepperlink/busybox-httpd` image (tags `1.36.1`,
  `1.36.2`) was built by hand in 2024 (2024-07); there is no CI and no build workflow.
- **No deploy path:** no current consumers found in `pepperlink/home`.
- Status: archive-or-CI decision pending (owner).
