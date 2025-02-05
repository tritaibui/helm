## KAS Chart

1. Package helm chart
```bash
helm package kas-quarkus/
```

2. Create index file to publish
``bash
helm repo index --url https://tritaibui.github.io/helm/ .
```