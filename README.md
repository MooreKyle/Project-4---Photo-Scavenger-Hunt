# Project 4 - *Photo Scavenger Hunt*

Submitted by: **Kyle Moore**

**Photo Scavenger Hunt** is an app that contains a list which requires the user to attach photos based on a specific task. After attaching the photo to a task, the app shows the user where that photo was taken in a map. The map zooms in to show the specific location, including with a picture of the selected photo. The camera has functionality that may work on real devices. However, there are mixed results getting the camera to be able to take a picture on the simulator through the app's development, as this may not be supported for testing on my end.

Time spent: **7** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays list of hard-coded tasks
- [x] When a task is tapped it navigates the user to a task detail view
- [x] When user adds photo to complete the tasks, it marks the task as complete
- [x] When adding photo of task, the location is added
- [x] User returns to home page (list of tasks) and the status of your task is updated to complete
 
The following **optional** features are implemented:

- [x] User can launch camera to snap a picture	

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here is a reminder on how to embed Loom videos on GitHub. Feel free to remove this reminder once you upload your README. 

[Guide]](https://www.youtube.com/watch?v=GA92eKlYio4) .

## Notes

Describe any challenges encountered while building the app.

Attempting to get the camera functionality working has mixed results, and am unsure if it works properly in simulator or needs testing on a real life device.
 - Unsure if camera is detected and functioning via simulator in xcode. Compatible device (iPhone 15 and iPhone 15 Pro) via Xcode used for testing.
 - Camera app shows in background when app is newly installed and app requests permissions for access to photo library, and camera app shows after this.
      - However, exiting the camera menu afterwards, it does not show at any other point again, even after closing and reopening app.

 -  Camera code was added to TaskDetailViewController.swift.

 - I am unsure if the code itself will count as implementation of the optional feature of the camera's ability to take a picture. For the one time I was able to access the camera app, the camera snap button to take a picture was nonfunctional, and the camera showed a black screen, as if the app was frozen.

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
