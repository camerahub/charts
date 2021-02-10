# CameraHub charts

Helm chart for [CameraHub](https://github.com/camerahub/camerahub)

```sh
helm repo add camerahub https://camerahub.github.io/charts
helm repo update
helm upgrade --install -n camerahub camerahub [-f values.yaml] --create-namespace camerahub/camerahub
```

You can optionally provide a values file to override the app defaults. Use the default [values.yaml](https://github.com/camerahub/charts/blob/main/charts/camerahub/values.yaml) as a basis.
