# mengqiyns

## Description
mengqiyns

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] mengqiyns`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree mengqiyns`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init mengqiyns
kpt live apply mengqiyns --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
