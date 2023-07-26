# git-helm-hello

## Description
kpt package for provisioning flux gitrepo and helmrelease

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] git-helm-hello`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree git-helm-hello`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init git-helm-hello
kpt live apply git-helm-hello --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
