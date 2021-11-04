# KubeAcademy from VMware Contributor's Guide

The KubeAcademy from VMware Contributor's Guide is specifically for those developing content for KubeAcademy. It includes instructions on how to:
- Create a course, lesson, or lab.
- Write a script to read as you record the course, lesson or lab.
- Download and install Open Broadcaster Software (OBS) to record your video.
- Submit a Defect Report if you find a defect in a course, course description on lab.
- Submit an Update Course Request if you encounter an inaccurate or out of date course.

## Can Anyone Contribute to KubeAcademy?
At the present, KubeAcademy is only able to accept course contributions from VMware employees because of the way our submission process works. We are currently updating the submission process so that any member of the Cloud Native or Kubernetes communities may contribute to KubeAcademy. 

KubeAcademy is built with a love and passion for the Cloud Native and Kubernetes communities. The changes in development in this technology area is rapid. Covering each area with appropriate depth is challenging. This is why we need community contributions to keep up in this fast moving space. It is why we are seeking experienced practioners to contribute content, review content, and even share your ideas on ways we can better streamline our content contribution process.

## How to Contribute Content to KubeAcademy
Thank you for your interest in wanting to contribute content to KubeAcademy from VMware. KubeAcademy provides free Kubernetes training for beginner, intermediate, and advanced skillset levels. We welcome ideas for developing new courses. To submit your idea for a new course, go [here](https://github.com/kube-academy/onboarding/blob/main/templates/new-course.md). We also invite you to check out our [GitHub Repository Backlog](https://github.com/orgs/kube-academy/projects/3) for contribution ideas. 

### Contact KubeAcademy through VMware Slack 

There is a #KubeAcademy Slack channel on VMware Slack. This is a good place to let us know of your interest in contributing to KubeAcademy. 

## KubeAcademy Content Types

Most of the content created for KubeAcademy is in a video format. This includes content for courses, demos and lectures. 

- **Course**. A series of lessons that cover a specific topic of study. At KubeAcademy, all courses are created in a video format. Course content must include:
  - An introduction about the course, demo, or lecture.
  - One or more lessons.
  - A lab (optional).
- **Lesson**. A lecture, demo, or combination of both that are part of a course. A lesson created for KubeAcademy must be 10 minutes, or less. A lesson created for KubeAcademy Pro does not have a time limit. There are a couple of types of lessons: These include:
   - A video lecture. 
   - A video demo.
   - A combination of a video lecture and a video demo. 
- **Lab**. A hands-on environment where learners can practice how to use Kubernetes. The labs are powered by [Educates](https://github.com/eduk8s). Educates is a Kubernetes Operator that controls the KubeAcademy training environment. 
- **Articles**. (Future content releases include) A piece of written work that guides readers to a course. Future content releases are going to include written Articles.

    Note: The FAQ "course" represents mini-lessons that do not depend upon other material. It supports both an easy entry point for learners and a way for contributors to get started with the video production format of creating courses

## How to Create Video Content

To start creating video content for KubeAcademy, go to [Open Broadcaster Software (OBS)](https://obsproject.com/) and download the latest release of this free and open source software for video recording to your operating environment. OBS Studio provides downloads for Linux, Mac, and Windows.

A template is available, A bio is needed...

### Download and Install OBS

The course developers at KubeAcademy use Open Broadcaster Software Studio (OBS) to record videos. OBS provides convenient methods for defining scenes that include various input devices such as a microphone, camera or screen. OBS is a free and open source software that is available for Linux, Mac, and Windows operating systems. 

Read the [OBS Studio Quickstart](https://obsproject.com/wiki/OBS-Studio-Quickstart) for information on how to change default settings for audio devices and video sources. 

To download OBS Studio:

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
6. [Add scenes and sources](https://obsproject.com/wiki/OBS-Studio-Overview#scenes-and-sources) for your video. This includes webcams and any other devices or media that you want in the output. 
7. Test the record settings as follows:
   - Go **Settings** > **Output**. 
   - Select **Start Recording** 
   - Run the test for a few minutes to make sure that there are no issues. If you encounter an issue, go to [OBS Help](https://obsproject.com/help).



 in the following formats. 
-


## Deploy Content
Deploying content to a public, production environment requires a number of steps. The following diagram covers many of the major steps. The blue boxes reflect activities most content contributors are actively engaged in doing.

![Image](https://docs.google.com/drawings/d/e/2PACX-1vQAcCAMyF1Gce3rpXToIyX02qoEFRf55gU9SbOprQaL1KE4nPjMvKWE5XqGI8zLYTG6stQ3Vq-HPYSH/pub?w=960&h=720)

We manage KubeAcademy content development much like any standard software development process - by building a backlog of tasks that need to be completed, prioritizing each task, and having members of the team (and community) complete the tasks based on match in skillset, time and interest.

## Report Content Issues

One of most beneficial things the Cloud Native and Kubernetes communities can do to ensure the integrity of content at KubeAcademy is to let us know when there is content that is inaccurate or out of date, or when there is a defect in a course, course description, or lab. 

To report a content issue:

1. [Add the issue to the KubeAcademy backlog](https://github.com/kube-academy/backlog/issues). 

2. Do one of the following:
   - [Submit a Defect Report](https://github.com/kube-academy/onboarding/blob/main/templates/defect.md). Use this template to provide details about the issue. If possible, include steps to reproduce the issue.
   - [Submit an Update Course Request](https://github.com/kube-academy/onboarding/blob/main/templates/update-course.md). Use this template to provide details about a course that requires a major change such as a module addition, or is out of date and either needs to be updated or archived.

We have identified three different types of requests that will come into the backlog:
- Defects
- Course Update Proposal
- New Course Proposal

> **_Note:_** We are using Github Issues for managing the document process. While the site content is not in the repository, we are exposing a repository, backlog, for communicating requests and reporting issues.

Github Repo:
[Issue Repo](https://github.com/kube-academy/backlog/issues)

