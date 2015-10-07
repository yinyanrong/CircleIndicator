CircleIndicator
===============
a lightweight viewpager indicator! 

![inside mode]( https://github.com/THEONE10211024/CircleIndicator/blob/master/demo/inside.gif)    

![outside mode]( https://github.com/THEONE10211024/CircleIndicator/blob/master/demo/outside.gif)    

![solo mode]( https://github.com/THEONE10211024/CircleIndicator/blob/master/demo/solo.gif)    

Gradle
------------

**version 1.1.5 (```minSdkVersion="11"```)**
```groovy
dependencies {
    compile 'me.relex:circleindicator:1.1.5@aar'
}
```


Usage
--------
xml:
```xml
	<pers.medusa.circleindicator.widget.CircleIndicator
        android:layout_width="match_parent"
        android:layout_height="40dp"
        android:layout_centerVertical="true"
        android:id="@+id/indicator"
        CircleIndicator:ci_background="@android:color/white"
        CircleIndicator:ci_selected_background="0xffe6454a"
        CircleIndicator:ci_mode="outside"
        CircleIndicator:ci_gravity="center"
        CircleIndicator:ci_radius="10dp"
        CircleIndicator:ci_margin="5dp"
        />
```
java:
```java
        circleIndicator.setViewPager(viewPager);
```
--------
Notice:the method should be called after ViewPager.setAdapter().    

#####Properties:

* `app: ci_radius`
* `app: ci_margin`
* `app: ci_background`
* `app: ci_selected_background`
* `app:ci_drawable_unselected`
* `app: ci_gravity`
* `app: ci_mode`


License
--------
```
Copyright (C) 2014 relex

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
