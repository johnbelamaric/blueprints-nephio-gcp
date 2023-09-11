# nephio-mgmt

## Description
Nephio Management cluster components

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nephio-mgmt`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nephio-mgmt`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nephio-mgmt
kpt live apply nephio-mgmt --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
