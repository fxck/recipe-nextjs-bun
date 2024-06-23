# Zerops x Next.js on Bun

Import project:

```yaml
project:
  name: nextjs-bun

services:
  - hostname: app
    type: bun@latest
    buildFromGit: https://github.com/fxck/recipe-nextjs-bun
    enableSubdomainAccess: true
```
