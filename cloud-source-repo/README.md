# cloud-source-repo

## Description
Package for provisioning a Google Cloud Source Repository

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] cloud-source-repo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree cloud-source-repo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init cloud-source-repo
kpt live apply cloud-source-repo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
