# How to reproduce

Run `pnpm docs:build` and see console output for error. You will get an error like this:

```
ReferenceError: localStorage is not defined
    at file:///Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/pinia-plugin-persistedstate@2.4.0_pinia@2.2.6_vue@3.5.13_/node_modules/pinia-plugin-persistedstate/dist/chunk-256H5QT7.mjs:158:19
    at Array.map (<anonymous>)
    at file:///Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/pinia-plugin-persistedstate@2.4.0_pinia@2.2.6_vue@3.5.13_/node_modules/pinia-plugin-persistedstate/dist/chunk-256H5QT7.mjs:156:155
    at file:///Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/pinia@2.2.6_vue@3.5.13/node_modules/pinia/dist/pinia.mjs:1684:43
    at EffectScope.run (/Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/@vue+reactivity@3.5.13/node_modules/@vue/reactivity/dist/reactivity.cjs.prod.js:77:16)
    at file:///Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/pinia@2.2.6_vue@3.5.13/node_modules/pinia/dist/pinia.mjs:1684:33
    at Array.forEach (<anonymous>)
    at createSetupStore (file:///Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/pinia@2.2.6_vue@3.5.13/node_modules/pinia/dist/pinia.mjs:1671:14)
    at createOptionsStore (file:///Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/pinia@2.2.6_vue@3.5.13/node_modules/pinia/dist/pinia.mjs:1263:13)
    at useStore (file:///Users/mark_chen/Downloads/repro-pinia-persistedstate-vitepress/node_modules/.pnpm/pinia@2.2.6_vue@3.5.13/node_modules/pinia/dist/pinia.mjs:1752:17)
```
