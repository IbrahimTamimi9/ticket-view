# TicketView

[![](https://jitpack.io/v/santalu/ticket-view.svg)](https://jitpack.io/#santalu/ticket-view) [![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-TicketView-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/6223) [![Build Status](https://travis-ci.org/santalu/ticket-view.svg?branch=master)](https://travis-ci.org/santalu/ticket-view)

A simple layout for displaying tickets.

## Sample

<img src="https://github.com/santalu/ticket-view/blob/master/screens/sample.png"/>

## Usage

### Gradle
```
allprojects {
  repositories {
    maven { url 'https://jitpack.io' }
  }
}
```
```
dependencies {
  compile 'com.github.santalu:ticket-view:1.0.1'
}
```

### XML
```xml
<com.santalu.ticketview.TicketView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:background="@color/white"
    app:tv_anchor="@+id/pnr"
    app:tv_holeRadius="60"
    app:tv_orientation="vertical">

*** your content here ***

</com.santalu.ticketview.TicketView>
```

## Attributes

| Name        | Description           | Value  |
| ------------- |:-------------:| -----:|
| tv_anchor     | this determines where separator is drawn     | reference |
| tv_holeRadius | radius of holes      |   string |
| tv_orientation | orieantation of separator and holes      |   horizontal,vertical |

## License
```
Copyright 2017 Fatih Santalu

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
