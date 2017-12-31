# Pre-work - *Tipper*

**Tipper** is a tip calculator application for iOS.

Submitted by: **Harjas Monga**

Time spent: **10** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [x] Settings page to change the default tip percentage.
* [ ] UI animations
* [x] Remembering the bill amount across app restarts (if <10mins)
* [x] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Added support for a custom tip option
- [x] Added support to split the check

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='video.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

One of the struggles I had when creating this application was pre-filling the information onto the screen when the app loaded up. I realized that the issue was that I was reading the saved data after the view is rendered, I researched how the view lifecycle on iOS works.  Once I understood the view lifescycle, I was able to read the data before the view loaded, so when the app started the data would already be on the screen, I was able to properly prefill the fields with saved information before the user sees the view.

## License

    Copyright [2017] [Harjas Monga]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
