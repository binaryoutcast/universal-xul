# UXP "Redwood"

The Redwood branch of the Unified XUL Platform was orginally used while testing and development continued on trunk toward webcomponents. At some point, the work ceased and it was THOUGHT stable and merged in. However, there have been side effects. Presenting most brokenly in Interlink. So what was once for an extended range of Pale Moon 28.x versions is now the home of Interlink Mail until it can be determined what caused the breaking regressions and how to work around or fix them.

Otherwise this codebase may become used for "pure" toolkit applications that do not require the latest WebApp specifications if it persists.

The `unified-comm` repository will operate as `binoc-central` did in relation to `uxp-redwood` and `uxp-current` (mcp repo) with `redwood` and `current` branch identifiers and be made and as functionally identical as possible so that the applications can be built for both iterations of the codebase. However, only Interlink will be initally produced with this codebase and if the issues with `uxp-current` can be resolved then Interlink will return to using that for as long as UXP its self remains viable.
