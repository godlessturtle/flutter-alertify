# ✨ Flutter Alertify

[![pub package]](https://pub.dartlang.org/packages/alertify)

A collection of beautiful animated dialogs.

## 🎖 Installing

```yaml
dependencies:
  alertify: "^0.0.2"
```

### ⚡️ Import

```dart
import 'package:alertify/alertify.dart';
```

## 🎮 How To Use

```dart
 Alertify(
  content: 'Some content here',
  context: context,
  isDismissible: true,
  title: 'Alertify',
  alertType: AlertifyType.success,
  buttonText: 'OK',
  animationType: AnimationType.outToIn,
  barrierColor: Colors.black.withOpacity(0.5),
  onDismiss: () {
    // Your code here
  },
).show();
```


<img src="https://github.com/godlessturtle/flutter-alertify/blob/master/Ekran%20Resmi%202019-10-03%2011.16.10.png">
<img src="https://github.com/godlessturtle/flutter-alertify/blob/master/Ekran%20Resmi%202019-10-03%2011.16.21.png">
<img src="https://github.com/godlessturtle/flutter-alertify/blob/master/Ekran%20Resmi%202019-10-03%2011.16.31.png">
<img src="https://github.com/godlessturtle/flutter-alertify/blob/master/Ekran%20Resmi%202019-10-03%2011.16.40.png">

### ❗️ Note

- Pull requests are welcomed

## ⭐️ License

MIT License
