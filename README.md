# Zerops + Qwik

```yaml
project:
  name: zerops-qwik

services:
  - hostname: qwiknodejs
    type: nodejs@20
    ports:
      - port: 3000
        httpSupport: true
    minContainers: 1
    enableZeropsSubdomain: true
    buildFromGit: https://github.com/fxck/zerops-qwik-nodejs
```
