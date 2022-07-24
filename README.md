# metabase multiarch

Builds and publishes an [metabase](https://www.metabase.com) container image which works on amd64 and aarch64.

```bash
docker run \
    --name metabase \
    -p 3000:3000 \
    ghcr.io/tgrosinger/metabase-multiarch:latest
```

Then open http://localhost:3000.
