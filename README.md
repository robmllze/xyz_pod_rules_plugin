## Example

**analysis_options.yaml**

```yaml
include: package:flutter_lints/flutter.yaml

analyzer:
  plugins:
    - custom_lint

custom_lint:
  rules:
    - must_dispose_pods
```

**pubspec.yaml**

```yaml
dev_dependencies:
  custom_lint: ^0.6.4
  xyz_pod_rules_plugin:
    git:
      url: https://github.com/robmllze/xyz_pod_rules_plugin
      ref: main
```
