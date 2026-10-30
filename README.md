# lofitown-autofishing-dist

Public distribution mirror for the [lofi.town AutoFish](https://github.com/lowqualityloey/lofitown-autofishing)
userscript. The source repository is private; this one exists so Tampermonkey can check for and
install updates without a GitHub session.

## Install

<https://github.com/lowqualityloey/lofitown-autofishing-dist/releases/latest/download/autofish.user.js>

Every release attaches the built userscript as **`autofish.user.js`**. That fixed path is what the
script's `@downloadURL` and `@updateURL` point at, so the newest release is always the update.

## What is in here

Only the generated file, attached to releases. The file is produced by `node build-userscript.js`
in the source repository. Do not edit it here - changes would be overwritten by the next release.
