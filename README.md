Dartmon
=========

A Dart package to use the Postmon API

Use
------

```dart
import "package:dartmon/dartmon.dart";
    
void() {
  Postmon postmon = new Postmon("cep_here");
  print(postmon.infos);
}
```
    
ToDo
------

 * Function to use tracking API's method
 * Improve unittests
 * Remove the "dart:html" dependency

License
--------
    Copyright 2014 The Postmon API Team

	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at
	
	    http://www.apache.org/licenses/LICENSE-2.0
	
	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.