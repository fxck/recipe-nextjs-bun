# Zerops x Next.js on Bun

Import project:

```yaml
project:
  name: nextjs-bun

services:
  - hostname: app
    type: bun@1.1
    buildFromGit: https://github.com/fxck/recipe-nextjs-bun
    enableSubdomainAccess: true
```
