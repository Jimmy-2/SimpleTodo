# Project 1 - *SimpleTodo App*

**SimpleTodo App** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Jimmy Wu**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **view a list of todo items**
* [x] User can **successfully add and remove items** from the todo list
* [x] User's **list of items persisted** upon modification and and retrieved properly on app restart

The following **optional** features are implemented:

* [ ] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://raw.githubusercontent.com/Jimmy-2/SimpleTodo/master/SimpleTodo.gif' title='SimpleTodo App Walkthrough' width='' alt='SimpleTodo App Walkthrough' />

MP4 created with [OBS](https://obsproject.com/).
MP4 converted to Gif with [Imgur](https://imgur.com/).

## Notes

Describe any challenges encountered while building the app.  
Default FileUtil import package did not work. So I had to use: import org.apache.commons.io.FileUtils; in the MainActivity.java file instead.   
This also resulted in a change to the implementation in build.gradle(:app).  
I had to use: implementation group: 'commons-io', name: 'commons-io', version: '2.6'  

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

