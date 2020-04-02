1. Upadated Firebase requirements to 17.x, added missing implementations to solve runtime ClassNotFound Exceptions
2. Added GooglePlayServices version test when invoking startWatch
  - Error 400 = Current GPS version below required 10.2
  - Error 404 = GPS not installed or disabled
