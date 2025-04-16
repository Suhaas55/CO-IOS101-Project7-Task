//
//  README.md
//  ios101-project7-task
//
//  Created by Suhaas Achanta on 4/16/25.
//

# Project 7 - Task App

Submitted by: **Suhaas Achanta**

**Task App** is an app that allows users to create, manage, and complete tasks, with due dates and calendar-based tracking. Tasks persist even after closing the app.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a list of tasks
- [x] Users can add tasks to the list
- [x] Session persists when application is closed and relaunched (tasks don't get deleted when closing app)
- [x] Note: You have to quit the app, not minimize it, in order to see the persistence.
- [x] Tasks can be deleted
- [x] Users have a calendar view via tab bar navigation that displays tasks

The following **additional** features are implemented:

- [x] Tasks can be toggled completed
- [x] User can edit tasks by tapping on the task in the feed view
- [x] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

https://www.loom.com/share/add3116c512240bc9e460147ec1178ef?sid=c222029e-3fef-41eb-84e6-5839399a2f23

## Notes

Describe any challenges encountered while building the app.

- At first, the app wouldn't launch due to not setting the correct entry point after embedding in a tab bar controller.
- Navigation controller wasn't correctly attached to the tasks view, so the "+" button didn’t show up until fixed.
- Had to understand how to encode/decode custom `Task` structs for persistence.

## License

    Copyright 2025 Suhaas Achanta

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
