# flutter_lints_ymadd

An extended lint rule set for better coding.

Added a rule for flutter_lints that I think is even better.
rules in addition to [flutter_lints](https://pub.dev/packages/flutter_lints).
## Usage

### 1. Install

With Flutter:
```bash
flutter pub add --dev flutter_lints_ymadd
```

pubspec.yaml:
```yaml
dev_dependencies:
    flutter_lints_ymadd:
```

### 2. Create `analysis_options.yaml`
Create an `analysis_options.yaml` file at the root of the package (alongside the `pubspec.yaml` file) 
and `include: package:flutter_lints_ymadd/analysis_options.yaml` from it.
