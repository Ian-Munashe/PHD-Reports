# PHD-Reports-Privacy-Policy

Your privacy is important to us. It is PHD Reports' policy to respect your privacy and comply with any applicable law and regulation regarding any personal information we may collect about you, including across and other apps we own and operate.

This policy is effective as of 16 December 2021 and was last updated on 16 December 2021.

## Simple Usage
To use this plugin, add `fxdialogs` as a
[dependency in your pubspec.yaml file](https://pub.dev/packages/fxdialogs/install).

### Implementation:

* Import `import 'package:fxdialogs/fxdialogs.dart';`

### Message Dialog

* use `FXDialog` widget to call the **Message Dialog** .

```
ElevatedButton(
    onPressed: () => FXDialog(
        context,
        dialogType: DialogType.success,
        message: "Custom Dialog message",
    ),
    child: Text("Open Success Dialog"),
),
```
### FX Progress indicator

* use `FXDialog.progress()` widget to choose your preferred **Progress Indicator** .

```
ElevatedButton(
    onPressed: () => FXDialog.progress(
        context,
        progressType: ProgressType.linear,
        subtitle: "Loading...",
    ),
    child: Text("Open Linear Progress Dialog"),
),
```

See the `example` directory for the complete sample app.

