# Sample Express

## Sample command

To create a new chart

```bash
helm create <chart-name>
```

To pack new helm chart

```bash
helm package sample-express-chart
```

To install new helm chart

```bash
helm install sample-express-chart sample-express-chart-0.1.0.tgz
```

To list all current install chart

```bash
helm list
```

To uninstall chart

```bash
helm uninstall sample-express-chart
```
