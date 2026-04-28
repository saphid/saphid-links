# Saphid Signals

A tiny redirect page for Alex's link-blog.

The canonical links page now lives at:

https://saphid.github.io/homelab-blog/links

## How it works

`index.html` performs an immediate meta refresh to the Homelab Blog links page and includes a normal fallback link for browsers that do not follow redirects automatically.

## Development

This repo is intentionally static: no build step, package manager, or runtime dependencies.
