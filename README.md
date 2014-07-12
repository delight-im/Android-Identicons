# Android-Identicons

[Identicons](http://en.wikipedia.org/wiki/Identicon) for Android — turn any data into a visual hash

## Installation

 * Copy the Java package to your project's source folder
 * or
 * Create a new library project from this repository and reference it in your project

## Usage

### Layout (XML)

```
<im.delight.android.identicons.SymmetricIdenticon
	android:id="@+id/identicon"
	android:layout_width="48dp"
	android:layout_height="48dp" />
```

or

```
<im.delight.android.identicons.AsymmetricIdenticon
	android:id="@+id/identicon"
	android:layout_width="48dp"
	android:layout_height="48dp" />
```

### Activity (Java)

```
Identicon identicon = (Identicon) findViewById(R.id.identicon);
identicon.show("john.doe@example.org");
// identicon.show(myObject);
// identicon.show(42);
// identicon.show(System.currentTimeMillis());
// identicon.show(true);
```

## Other languages

These are implementations in other languages, which may be similar but generally not related:

 * [JavaScript](https://github.com/stewartlord/identicon.js)
 * [Ruby](https://github.com/chrisbranson/ruby_identicon)
 * [Java](https://github.com/donpark/identicon)
 * [PHP](https://github.com/yzalis/Identicon)
 * [Go](https://github.com/cupcake/sigil)

## License

```
Copyright 2014 www.delight.im <info@delight.im>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```