# auren-releases

Public release feed for [Auren](https://github.com/pablopramparo/auren) - a native Windows video
player powered by libmpv.

This repo holds only built release artifacts (installers, update packages, and Velopack's own
version manifest), kept separate from Auren's own source repo. Auren's built-in auto-updater
checks this repo's Releases anonymously, which requires the *feed* to be public even while the
source stays private - see `docs/SPECS.md` §22 in the main repo for the full design reasoning.

Nothing in this repo is meant to be run or built directly - download an installer from the
[Releases](https://github.com/pablopramparo/auren-releases/releases) page instead.
