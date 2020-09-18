# charts
Repo for storing/hosting Helm charts

## Updating

Run the following commands when creating/updating charts:

```bash
helm package <path to your chart>
helm repo index https://cicadatesting/cicada-charts/ .
```

This will compress the chart as a TAR file and regenerate the index.yaml
with the updated binaries
