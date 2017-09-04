# Emoticon Pack - Google Android 7.0 (Nougat)
[ ![Download](https://api.bintray.com/packages/kevalpatel2106/EmoticonGIFKeyboard/emoticonpack-android7/images/download.svg) ](https://bintray.com/kevalpatel2106/EmoticonGIFKeyboard/emoticonpack-android7/_latestVersion) [![API](https://img.shields.io/badge/API-16%2B-orange.svg?style=flat)](https://android-arsenal.com/api?level=16) ![Javadoc](https://img.shields.io/badge/Javadoc-EmoticonGIFKeyboard-blue.svg)](http://kevalpatel2106.github.io/EmoticonGIFKeyboard) <a href="https://www.paypal.me/kevalpatel2106"> <img src="https://img.shields.io/badge/paypal-donate-yellow.svg" /></a> [![Google Android 8.0](https://img.shields.io/badge/Android%208-1869%20Icons-brightgreen.svg)

This emoticon icon pack contains emoticons graphics from **Android 7.0 Nougat**. You can find complete list of emoticons icons from [here](https://emojipedia.org/google/android-7.0/).

## How to use?
- Add below lines to `app/build.gradle` file of your project.
    ```
    dependencies {
       compile 'com.kevalpatel2106:emoticonpack-android7:<latest>
    }
    ```
- This gif pack is plugin for [EmoticonGIFKeyboard](https://github.com/kevalpatel2106/EmoticonGIFKeyboard).
- Set `Android7EmoticonProvider` as emoticon provider in `EmoticonConfig`.
  ```
    EmoticonGIFKeyboardFragment.EmoticonConfig emoticonConfig = new EmoticonGIFKeyboardFragment.EmoticonConfig()
                .setEmoticonProvider(Android7EmoticonProvider.create())
  ```


## Acknowledgements
- Emoticon graphics and emoticon details are from [Emojipedia](https://emojipedia.org/). (See [emoticon-scrapper](https://github.com/kevalpatel2106/EmoticonGIFKeyboard/tree/master/emoticon-scrapper) module.)


## Questions?🤔
Hit me on twitter [![Twitter](https://img.shields.io/badge/Twitter-@kevalpatel2106-blue.svg?style=flat)](https://twitter.com/kevalpatel2106)


## License
Copyright 2017 Keval Patel

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.