# Open Broadcaster Software

This document will help you get up and running with [Open Broadcaster Software (OBS)](https://obsproject.com/).

OBS is free and open source software that can be used to record KubeAcademy lessons.  It provides convenient methods to defind "Scenes" that include various input devices such as your microphone, a camera or your screen.

## Install

The [download page](https://obsproject.com/download) provides download options for the installer.  It is available for Windows, Mac and Linux.

## Configuration

With OBS installed, download `obs-kubeacademy-scenes.json` scene collection config file.

Then, in OBS import that scene collection config.

![import scene collection](images/import-scene-collection.png)

Now, you should see 3 items in the Scenes pane.

![scenes](images/scenes.png)

The "ScreenCap" scene allows you to capture your screen and mic at the same time.

The "Camera" scene allows you to capture your webcam and mic.

The "PinP" captures all three.  It captures your screen as the primary with your camera picture-in-picture.

You should see three devices under "Sources."

![sources](images/sources.png)

These three devices will need to be configured to use the devices connected to your computer.  The scene collection file you imported was exported from another computer with different devices attached.  For each device, simply select it, then click the cogwheel icon at the bottom of the pane and set them to use the appropriate device for your setup.

Lastly, open the preferences for OBS.

![preferences](images/preferences.png)

Select "Video" from the panel on the left and set the Base and Output resolution to 1920x1080.

![video settings](images/video-settings.png)

## Recording

You should now be ready to do a test recording.  In the "Controls" pane, click "Start Recording."

![controls](images/controls.png)

Test each of the three scenes.  Say a few words to test the mic pick up.  Then click "Stop Recording."

When recording an actual lesson, if you make a mistake, go back to the last transition point - such as when you switched slides in a deck - and resume from there.  The flub can be edited out later.

## Remux the Recording

OBS records to an `.mkv` file.  The lessons you submit need to be in `.mp4` format.  Select "Remux Recordings" from the File menu.

![remux menu](images/remux-menu.png)

In the dialogue that opens, click the browse button to navigate to the file that was just saved.

![remux recordings](images/remux-recordings.png)

Select the file and then click "Remux" at the bottom-right.

Short recordings will process quickly.  Longer recordings will take more time.

Once OBS tells you the remux is complete, you can view the files by selecting "Show Recordings" from the File menu.

![recordings menu](images/recordings-menu.png)

That will open a file browser.  You should see the original `.mkv` file alongside the `.mp4` file.  Open the `.mp4` file and watch the video to ensure the output is as expected.

![file browser](images/file-browser.png)

Rename to the `.mp4` file to include the course and lesson names and upload it to the appropriate location in  Google Drive.

