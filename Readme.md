# Collection of various helm-charts

## Usage

```sh
helm repo add simontheleg https://simontheleg.github.io/helm-charts/
```

## Packaging and releasing

```sh
helm package charts/* -d ./releases &&
helm repo index --url https://github.com/SimonTheLeg/helm-charts .
```
