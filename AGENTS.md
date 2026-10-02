# Notes
- Jekyll (github-pages) reveal.js slideshow; runs via `docker-compose.base44.yml` (ruby:3.1, jekyll serve on 4000 -> 3000).
- First boot takes a few minutes for `bundle install`; gems cached in a volume. Lockfile is regenerated in-container if it fails to resolve.
- No external credentials needed.
