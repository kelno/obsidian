---
publish: "true"
---

Getting started: https://quartz.jzhao.xyz/

Test publish:  `npx quartz build --serve` 

Sync to publish to GitHub pages: `npx quartz sync`

Changing the root of the publish folder is just pointing the symlink called "content" to something else (`D:\work\quartz\content` -> ?)

# Plugins

#### HardLineBreaks
https://quartz.jzhao.xyz/plugins/HardLineBreaks

Adding `Plugin.HardLineBreaks(),` to `quartz.config.ts` in plugins/transformers
