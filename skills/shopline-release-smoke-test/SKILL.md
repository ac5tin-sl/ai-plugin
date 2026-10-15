---
name: shopline-release-smoke-test
description: Use when the user explicitly invokes shopline-release-smoke-test to check that the installed example skill is available.
license: MIT
---

# SHOPLINE Release Smoke Test

This harmless example checks skill availability only, not API connectivity or release success.

Use this skill only when the user explicitly invokes `shopline-release-smoke-test`. Do not use it for general release, API, or troubleshooting requests.

When invoked, reply with exactly this one line, without extra text or formatting:

```text
SHOPLINE release smoke test: OK
```

Do not call tools or APIs, access credentials, run commands, or read or write files.
