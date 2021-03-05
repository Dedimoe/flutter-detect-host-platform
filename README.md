# flutter-detect-host-platform
Flutter: detect host platform

Use Universal Platform package:

in pubspec.yml add :
```
dependencies:
  universal_platform: ^0.1.3
```

import: 
```
import 'package:universal_platform/universal_platform.dart';
```

code:
```
if (UniversalPlatform.isIOS) {
   print('iOS: $isIos');
}
if (UniversalPlatform.isAndroid) {
   print('Android: $isAndroid');
}
if (UniversalPlatform.isWeb) {
   print('Web: $isWeb');
}

```

reference : from [universal_platform](https://pub.dev/packages/universal_platform)
