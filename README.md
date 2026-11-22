# GSS Downloads

Release bundles for the GSS Plugin Manager. Each release holds one `site.tar.gz`:
a signed `manifest.json`, the plugin zips and their screenshots.

Published with `gss-publish` and `tools/publish.sh` from the GSS-PluginManager
repo. The download server pulls the latest release, checks the Ed25519 signature
and every file's SHA-256, and only then makes it live.

Do not upload or edit releases by hand.
