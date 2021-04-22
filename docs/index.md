Drone plugin to sign build artifacts with GnuPG. You are able to sign any file
which can be attached to your release or download mirror.

## Examples

```yaml
kind: pipeline
name: default

steps:
- name: step name
  image: dronehippie/gpgsign:1
  settings: []
```

## Parameters

dummy
: dummy
