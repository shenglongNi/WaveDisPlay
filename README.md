# WaveDisPlayView

WaveDisPlayView is an Android list view that allows you to preview the next view or the previous view by dragging left and right.

## Installation

Add it to your root build.gradle with:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
and app build.gradle:

```gradle
dependencies {
   implementation 'com.github.MlxChange:WaveDisPlay:0.1.1'
}
```

## Usage

====
```xml
<com.mlx.widget.WaveDisplayView
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        android:layout_width="match_parent"
        android:layout_height="match_parent">
</com.mlx.widget.WaveDisplayView>
```
```kotlin
waveDisplayView = findViewById(R.id.wave)
waveAdapter = MyAdapter(this, mData)
waveDisplayView.setAdapter(waveAdapter)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

<pre>
Copyright 2020 MlxChange

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>