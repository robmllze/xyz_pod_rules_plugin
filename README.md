## Example

analysis_options.yaml

```yaml
include: package:flutter_lints/flutter.yaml

analyzer:
  plugins:
    - custom_lint

custom_lint:
  rules:
    - must_dispose_pods
```
