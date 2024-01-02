错误信息：

```
yN [Error]: Request moonbit-lsp/readFile failed with message: Error: ENOENT: no such file or directory, open '/home/foo/tmp/foo/target/check/main/main.mi'
    at kk (/home/foo/.vscode-server/extensions/moonbit.moonbit-lang-0.1.269/node/lsp-server.js:6:244)
    at h9 (/home/foo/.vscode-server/extensions/moonbit.moonbit-lang-0.1.269/node/lsp-server.js:5:6426)
    at yk (/home/foo/.vscode-server/extensions/moonbit.moonbit-lang-0.1.269/node/lsp-server.js:5:6559)
    at Immediate.<anonymous> (/home/foo/.vscode-server/extensions/moonbit.moonbit-lang-0.1.269/node/lsp-server.js:5:6307)
    at process.processImmediate (node:internal/timers:476:21) {
  code: -32603,
  data: undefined
}
```

环境信息：

```
$ moon version
moon 0.1.0 (4e5df49 2023-12-28)
moonc 084e1ac 2023-12-28 /home/foo/.moon/bin/moonc

$ uname -a
Linux LAPTOP-CKB07V03 4.4.0-19041-Microsoft #488-Microsoft Mon Sep 01 13:43:00 PST 2020 x86_64 GNU/Linux
我使用的是WSL
