# KubeAcademy from VMware Contributor's Guide
Thank you for your interest in wanting to contribute content to KubeAcademy from VMware. KubeAcademy provides free Kubernetes training for beginner, intermediate, and advanced skillset levels. We welcome ideas for developing new courses. 

To submit your idea for a new course, go [here](https://github.com/kube-academy/onboarding/blob/main/templates/new-course.md). We also invite you to check out our [GitHub Repository Backlog](https://github.com/orgs/kube-academy/projects/3) for contribution ideas. 

The KubeAcademy from VMware Contributor's Guide is specifically written for instructors and practitioners who are creating content for KubeAcademy. This guide includes instructions on how to:

- Create a course, lesson, or lab.
- Write a script to read as you record the course, lesson or lab.
- Download and install Open Broadcaster Software (OBS) to record your video.
- Submit a Defect Report if you find a defect in a course, course description on lab.
- Submit an Update Course Request if you encounter an inaccurate or out of date course.

KubeAcademy is built with a love and passion for the Cloud Native and Kubernetes communities. The constant evolution of this technology makes creating courses with an appropraite depth challenging. This is why we are seeking experienced practioners to create content, review content, and even share your ideas on ways KubeAcademy can better streamline our content contribution process.

## Can Anyone Contribute to KubeAcademy?

At the present, KubeAcademy is only able to accept course contributions from VMware employees because of the way our submission process works. We are currently updating the submission process so that any member of the Cloud Native or Kubernetes communities may contribute to KubeAcademy. 

## Contact KubeAcademy 

There are a couple of ways to contact KubeAcademy with questions and concerns about a course. 

- [GitHub Issues Repo](Github Repo:
[Issue Repo](https://github.com/kube-academy/backlog/issues). All content created for KubeAcademy is managed in Github Issue Repository. Though no site content is in the GitHub repository, there is an open repository and backlog for anyone who is interested in developing a course, or reporting an issue to access. Github Repo:
- Slack. There is a #KubeAcademy Slack channel on VMware Slack. This is a good place to let us know of your interest in contributing to KubeAcademy. 

## KubeAcademy Content Formats

Most of the content created for KubeAcademy is in a video format. This includes content for courses, demos and lectures. The following is a description of content type.

- **Course**. A series of lessons that cover a specific topic of study. At KubeAcademy, all courses are created in a video format. Course content must include:
  - An introduction about the course, demo, or lecture.
  - One or more lessons.
  - A lab (optional).
- **Lesson**. A lecture, demo, or combination of both that are part of a course. A lesson created for KubeAcademy must be 10 minutes, or less. A lesson created for KubeAcademy Pro does not have a time limit. There are a couple of types of lessons: These include:
   - Video lectures. 
   - Video demos.
   - A combination of a video lecture and a video demo. 
- **Lab**. A hands-on environment where learners can practice how to use Kubernetes. The labs are powered by [Educates](https://github.com/eduk8s). Educates is a Kubernetes Operator that controls the KubeAcademy training environment. 
- **Article**. (Coming soon in a future content release.) A piece of written work that corresponds to a specific course.

    Note: The FAQ "course" represents mini-lessons that do not depend upon other material. It supports both an easy entry point for learners and a way for contributors to get started with the video production format of creating courses

## Create a Video

The course developers at KubeAcademy use Open Broadcaster Software Studio (OBS) to record videos. OBS provides convenient methods for defining scenes that include various input devices such as a microphone, camera or screen. OBS is a free and open source software that is available for Linux, Mac, and Windows operating systems. 

To start creating video content for KubeAcademy, go to [Open Broadcaster Software (OBS)](https://obsproject.com/) and download the latest release of this free and open source software for video recording to your operating environment. OBS Studio provides downloads for Linux, Mac, and Windows.

A template is available, A bio is needed...

### Download and Install OBS

Read the [OBS Studio Quickstart](https://obsproject.com/wiki/OBS-Studio-Quickstart) for information on how to change default settings for audio devices and video sources. 

To download and install OBS Studio:

1. Go to [Open Broadcaster Software (OBS))](https://obsproject.com/).
2. Select the operating environment to install OBS. There are three choices: Windows, macOS 10.13+, and Linux.

   The OBS installer appears in the bottom, left corner of the page.

3. Select the OBS installer.

   The Auto-Configuration Wizard opens.

4. Run the auto-configuration wizard.
   
   The wizard automatically tests your system to define default settings for options such as recording, resolution, and, bitrate. You can manually change these settings later. 
5. Set up your audio devices by doing one or both of the following:
   
   - **For macOS users only**. Download and install [iShowU Audio Capture](https://obsproject.com/forum/resources/os-x-capture-audio-with-ishowu-audio-capture.505/) audio driver extension to capture audio before continuing onto the next step.
   - Verify that the default audio device and microphone are working properly. To do this, open the OBS Studio window and look at the volume meters in the mixer section. If there is a problem with audio or if you want to change the devices in use, go **Settings** > **Audio**.

6. From the Scenes and Sources panel, [add scenes for your video](https://obsproject.com/wiki/OBS-Studio-Overview#scenes-and-sources). This includes webcams and any other devices or media that you want in the output. 

### Configure OBS to Create a Video

To configure OBS:

1. Go to ? and download the following scene collection config file.
   `obs-kubeacademy-scenes.json`.

2. Go to [OBS](https://obsproject.com/) and import the scene collection config.

   ![import scene collection](images/import-scene-collection.png)

   Three scenes display in the Scenes and Sources panel. These include: 
   
   - **ScreenCap**. Lets you capture your screen and mic at the same time.
   - **Camera**. Lets you capture your webcam and mic.
   - **PinP**. Lets you capture all three scenes. It captures your screen as the primary with your camera picture-in-picture.

     ![scenes](images/scenes.png)
   
3. Configure each source so that it connects to your computer. This configuration is necessary because the original scene collection file that was exported came from another computer with different sources.

   ![sources](images/sources.png)

4. Select the three devices. Click the cogwheel icon at the bottom of the pane. 

5. Open the preferences for OBS.

   ![preferences](images/preferences.png)

6. Select **Video** from the panel on the left. Set the Base and Output resolution to 1920x1080.

   ![video settings](images/video-settings.png)

If you make a mistake when recording an actual lesson, here's what to do:
  - Go back to the last transition point. For example, if you made a mistake at the point where you switched slides in a deck, go back and resume recording from there.  
  - Cut the mistake out of the recording later.

#### Test Record

It is a good idea to test record the three scenes before you do an actual course recording. Make sure to run the test for a few minutes to ensure that there are no issues. If you encounter one, go to [OBS Help](https://obsproject.com/help).

To test record:

1. Go **Settings** > **Output**. 
2. In the **Controls** pane, select **Start Recording**.

   ![controls](images/controls.png)

3. Do all of the following:

   a. Perform a test that includes all three scenes: mic, screen, and webcam.
   b. Speak a few words to test the mic pick up.  
   c. In the **Controls** pane, select **Stop Recording**.

## Video Course Creation Process

### KubeAcademy Video Branding Requirements

KubeAcademy has specific branding requirements for all course videos, including instructor apparel, and a video background.

### Video Course Time Limit

A video course can be no longer than seven minutes.

## Video Scripts

Once your course is approved by KubeAcademy, you can submit your video script for approval.

To submit your video script, go ?.


### Start with a Video Brief

One way to start writing a video script is to first write a video brief. A video brief helps you organize your course objectives. It also causes you to think more about the needs of your audience because you have to plan content for your course. Understanding the needs of your audience is key to writing a video script that is compelling, relevant and succinct.

### Use a Conversational Tone in Your Script Writing

Write your script in a pleasant, conversational tone encourages your audience to want to keep learning Kubernetes.


[KubeAcademy Course Template](https://docs.google.com/presentation/d/1Xq2wg6Q8TAucZ7qGy7dAjMpEBVuvqDPt/edit#slide=id.p3)

Developing an outline is a good way to get all your ideas down for the script you are writing for

Write the script in a conversational style
Use the template below to organize your script into slides. This will help you create a rhythm for changing topics
Build and organize the slides for your presentation to mirror your script 
Use your script to inform the content on your slides by using summarized parts of your script, bullet points, or quotes
Create visual representations of your script to your presentation or request artwork for your presentation by emailing tpalma@vmware.com.


### Write a Script

### Submit Your Script

### 


## Deploy Content
Deploying content to a public, production environment requires a number of steps. The following diagram covers many of the major steps. The blue boxes reflect activities most content contributors are actively engaged in doing.

![Image](https://docs.google.com/drawings/d/e/2PACX-1vQAcCAMyF1Gce3rpXToIyX02qoEFRf55gU9SbOprQaL1KE4nPjMvKWE5XqGI8zLYTG6stQ3Vq-HPYSH/pub?w=960&h=720)

We manage KubeAcademy content development much like any standard software development process - by building a backlog of tasks that need to be completed, prioritizing each task, and having members of the team (and community) complete the tasks based on match in skillset, time and interest.

## Report Content Issues
One of most beneficial things the Cloud Native and Kubernetes communities can do to ensure the integrity of content at KubeAcademy is to let us know when there is inaccurate or out of date content, or you find a defect in a course, course description, or lab. 

We have identified three different types of requests that will come into the backlog:
- Defects
- Course Update Proposal
- New Course Proposal

To report a content issue:

1. [Add the issue to the KubeAcademy backlog](https://github.com/kube-academy/backlog/issues). 

2. Do one of the following:
   - [Submit a Defect Report](https://github.com/kube-academy/onboarding/blob/main/templates/defect.md). Use this template to provide details about the issue. If possible, include steps to reproduce the issue.
   - [Submit an Update Course Request](https://github.com/kube-academy/onboarding/blob/main/templates/update-course.md). Use this template to provide details about a course that requires a major change such as a module addition, or is out of date and either needs to be updated or archived.


## Course Presentation

Tips for looking at the camera. Sit, or stand?
Tips for remembering content.
Tips for using a script.
Tips for not using a script.
Video Editing
Script editing




