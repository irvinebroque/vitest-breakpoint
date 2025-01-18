```
➜  vitest-breakpoint git:(main) npm run test

> vitest-breakpoint@0.0.0 test
> vitest


 DEV  v2.1.8 /Users/brendan/src/proj/vitest-breakpoint


⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ Unhandled Errors ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

Vitest caught 1 unhandled error during the test run.
This might cause false positive tests. Resolve unhandled errors to make sure your tests are not affected.

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ Unhandled Error ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯
Error: In project vitest.config.mts's configuration file wrangler.json, `compatibility_flags` must contain one of "nodejs_compat"/"nodejs_compat_v2".
Either one of these flags is required to use `@cloudflare/vitest-pool-workers`.
 ❯ buildProjectWorkerOptions node_modules/@cloudflare/vitest-pool-workers/dist/pool/index.mjs:1270:13
 ❯ buildProjectMiniflareOptions node_modules/@cloudflare/vitest-pool-workers/dist/pool/index.mjs:1382:47
 ❯ getProjectMiniflare node_modules/@cloudflare/vitest-pool-workers/dist/pool/index.mjs:1409:21
 ❯ Object.runTests node_modules/@cloudflare/vitest-pool-workers/dist/pool/index.mjs:1683:26
 ❯ executeTests node_modules/vitest/dist/chunks/resolveConfig.RxKrDli4.js:7680:5
 ❯ node_modules/vitest/dist/chunks/cli-api.C2yC_ESk.js:10798:9
 ❯ Vitest.runFiles node_modules/vitest/dist/chunks/cli-api.C2yC_ESk.js:10820:12
 ❯ Vitest.start node_modules/vitest/dist/chunks/cli-api.C2yC_ESk.js:10662:7
 ❯ startVitest node_modules/vitest/dist/chunks/cli-api.C2yC_ESk.js:11828:7

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

 Test Files  no tests
      Tests  no tests
     Errors  1 error
   Start at  09:33:12
   Duration  407ms (transform 0ms, setup 0ms, collect 0ms, tests 0ms, environment 0ms, prepare 0ms)
```