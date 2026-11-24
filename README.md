# opscalehub.github.io

Compatibility site. Copies of the app built before 0.12 look for updates only at
`https://opscalehub.github.io/Dang/release.json`. After the repository was renamed to
`Banadad`, that path is served from here (no redirect: Android does not follow
https→http). `Dang/release.json` is updated by `scripts/release.sh` in OpScaleHub/Banadad
on every release. Do not create a repository named `Dang` (it would break GitHub's
redirects for the renamed repository).
