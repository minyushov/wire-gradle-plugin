Wire Gradle Plugin
==================

DEPRECATED
-------
Please use Square's [wire-gradle-plugin](https://github.com/square/wire/tree/master/wire-gradle-plugin)

Integration
-------
```groovy
buildscript {
    repositories {
        maven { url "http://dl.bintray.com/minyushov/gradle" }
    }
    dependencies {
        classpath "com.minyushov.gradle:wire:1.0.1"
    }
}

apply plugin: 'com.squareup.wire'
```

License
-------

    Copyright 2015 Square, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
