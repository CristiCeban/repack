---
"@callstack/repack": patch
---

Fix `.jpeg` images not showing in Android release builds. They were emitted to `raw` instead of `drawable-*`, where React Native looks for them. Android image placement now matches React Native's drawable file types.
