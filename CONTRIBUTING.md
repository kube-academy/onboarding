# KubeAcademy from VMware Contributor's Guide

The KubeAcademy from VMware Contributor's Guide is written exclusively for instructors and practitioners who are creating course content for KubeAcademy. KubeAcademy provides free Kubernetes training for beginner, intermediate, and advanced skillset levels. 

With Kubernetes constantly evolving in ability, power and speed, so does the need to create timely, relevant course content with appropriate depth. It's one reason why KubeAcademy is always looking for Kubernetes experts in the Cloud Native and Kubernetes communities who are interested in creating and reviewing course content. 

This guide includes instructions on how to:

- [Submit an idea for a course, lesson, or workshop.](https://github.com/kube-academy/onboarding/blob/main/templates/new-course.md)
- Write a script using the [VMware Brand Guidelines](https://www.vmware.com/brand/portal/guidelines.html) and the [VMware Marketing Editorial Guide](https://www.vmware.com/content/dam/brand/photography-only/guidelines/writing-and-naming/editorial-style-guide/marketing-editorial-style-guide.pdf).
- Submit a script to KubeAcademy for approval.
- [Download and install Open Broadcaster Software (OBS).](https://obsproject.com/) to record your video.
- Use the [KubeAcademy Course Template](https://docs.google.com/presentation/d/1Xq2wg6Q8TAucZ7qGy7dAjMpEBVuvqDPt/edit#slide=id.p3) to create a video of your approved script. 

## Can Anyone Contribute to KubeAcademy?

At the present, KubeAcademy is only able to accept course contributions from VMware employees because of the way our submission process works. We are currently updating the submission process so that any member of the Cloud Native or Kubernetes communities may contribute to KubeAcademy. 

To submit an idea for a new course, go [here](https://github.com/kube-academy/onboarding/blob/main/templates/new-course.md). We also invite you to check out our [GitHub Repository Backlog](https://github.com/orgs/kube-academy/projects/3) for contribution ideas. 

### Report Content Issues

One of most beneficial things the Cloud Native and Kubernetes communities can do to ensure the integrity of content at KubeAcademy is to let us know when there is inaccurate or out of date content, or you find a defect in a course, course description, or lab. 

To report a content issue:

1. [Add the issue to the KubeAcademy backlog](https://github.com/kube-academy/backlog/issues). The KubeAcademy backlog keeps track of defects, course update requests, and new course proposal ideas.

2. Do one of the following:
   - [Submit a Defect Report](https://github.com/kube-academy/onboarding/blob/main/templates/defect.md) if there is an issue with the content you would like to report. If possible, include steps that reproduce the issue.
   - [Submit an Update Course Request](https://github.com/kube-academy/onboarding/blob/main/templates/update-course.md) to report a course that is in need of a major update, has content that is out of date, or is no longer valid, and should be archived.

## Course Content Types

KubeAcademy's current offerings include video courses made up of one or more lessons, an optional workshop, and (coming soon in a future release) blog posts. A description of the content is as follows:

- **Course**. A series of lessons that cover a specific topic of study. At KubeAcademy, all course content is currently created in a video format. When creating course content, you must include:
  - An introduction about the course, demo, or lecture.
  - One or more lessons.
  - A workshop (optional).
- **Lesson**. A lecture, demo, or combination of both for a course. A video lesson must be no longer than 7 minutes. 
- **Workshop**. A hands-on environment where learners can practice how to use Kubernetes. The labs are powered by [Educates](https://github.com/eduk8s). Educates is a Kubernetes Operator that controls the KubeAcademy training environment. 
- **Blog**. A piece of written work that corresponds to a specific course or workshop.

    Note: The FAQ "course" represents mini-lessons that do not depend upon other material. It supports both an easy entry point for learners and a way for contributors to get started with the video production format of creating courses

## KubeAcademy Brand Requirements

Brand names, such as KubeAcademy from VMware, are essential elements of our company's identity. KubeAcademy encourages all instructors to use [The VMware Brand Voice Guidelines](https://www.vmware.com/content/dam/brand/photography-only/guidelines/writing-and-naming/brand-voice-guide/VMware-Brand-Voice-Guidelines.pdf) when referring to VMware brand names in a course.

### Instructor Brand Apparel

An instructor who is going to appear in a video course must display one or more of the following brand elements

An instructor bio is needed.

### Kubernetes Academy Brand Background

There are two different KubeAcademy backgrounds available. One is a dark background, the other is a light background. To get a background to use in your video, go [here] 

### KubeAcademy Content Formats

Most of the content created for KubeAcademy is in a video format. This includes content for courses, demos, and lectures. The following is a description of content type.

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

## Scriptwriting Guidelines

Write your script using a plain language that your audience can understand. When introducing terminology for the first time, make sure to provide a brief definition or explanation. For specialized terminology and brand names, always introduce the full term on the first reference along with its corresponding acronym, if you plan to continue referencing it.

When writing your script, refer to the [VMware Marketing Editorial Style Guide](https://www.vmware.com/content/dam/brand/photography-only/guidelines/writing-and-naming/editorial-style-guide/marketing-editorial-style-guide.pdf) for specific instructions on branding, voice and tone, and inclusive terminology.        

### Start with a Video Brief

One way to start writing a video script is to first write a video brief. A video brief helps you organize your course objectives. It also causes you to think more about the needs of your audience as you plan content for your course. Understanding the needs of your audience is key to writing a video script that is compelling, relevant and succinct.

### Use a Conversational Voice and Tone in Your Script Writing

How we sound is as important as what we say. Write your script in a pleasant, conversational tone that encourages your audience to want to keep learning Kubernetes. Use active-voice verbs whenever possible, and avoid passive-voice verbs unless readers can easily recognize that the subject of the verb is irrelevant.

Voice and tone are important elements of the VMware brand. Consider the following guiding principles when creating course content:

- Know your audience. Demonstrate that you undertand your learner's challenges and they will trust your solutions.
- Match the level of detail to the audience's level of understanding. Deeper connections allow for deeper conversations.
- Make it familiar. Talk to your learners as if they were in the room with you.
- Elevate KubeAcademy relevance. Unexpected examples that highlight KubeAcademy's unique approach and value can go a long way.
- Move people forward. Add energy to your course with short, crisp statements that include active verbs.

### Terminology Use

The following terminology guidelines identify specific types of terms that you cannot use in your scripts. For a list of terminology that you cannot use in scripts or workshops submitted to KubeAcademy, go to https://source.vmware.com/portal/pages/global-marketing/terminology-changes.

When writing a script, consider the following terminology do's and do not's.

- Do use words that are neutral and positive. 
- Do use gender-neutral terminology, unless it is relevant to the content. For example, use **they** instead of **he** or **she** and **person hours** instead of **man hours**. 
- Do use non-violent terms that imply pain or degradation. For example, use **turn off the switches** instead of **kill the switch**.
- Do use terms that are free of ableism. For example, use **challenge** instead of **handicap**; use **sanity check** instead of **confidence check**.
- Do not use terminology that is jargon and slang.
- Do not use charged terminology. This includes words with shock value that demean, hurt, imply negative judgment.
- Do not objectify persons. For example, do not use **male** to signify a plug. Do not use female to signify a socket.

### Submit Your Script

To submit your script for review, upload it [here]. 

### KubeAcademy Course Template

Once your script is approved by KubeAcademy, you can start to build the course in the [KubeAcademy Course Template](https://docs.google.com/presentation/d/1Xq2wg6Q8TAucZ7qGy7dAjMpEBVuvqDPt/edit#slide=id.p3) by organizing the script content onto the slides. If there is artwork that you would like to add to your course, contact the KubeAcademy for assistance.

## Create a Video

The course developers at KubeAcademy use [Open Broadcaster Software (OBS)](https://obsproject.com/) to create videos. OBS provides convenient methods for defining scenes that include various input devices such as a microphone, camera or screen. OBS is a free and open source software that is available for Linux, Mac, and Windows operating systems. 

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

     ![scenes](recording/images/scenes.png)
   
3. Configure each source so that it connects to your computer. This configuration is necessary because the original scene collection file that was exported came from another computer with different sources.

   ![sources](recording/images/sources.png)

4. Select the three devices. Click the cogwheel icon at the bottom of the pane. 

5. Open the preferences for OBS.

   ![preferences](recording/images/preferences.png)

6. Select **Video** from the panel on the left. Set the Base and Output resolution to 1920x1080.

   ![video settings](recording/images/video-settings.png)

If you make a mistake when recording an actual lesson, here's what to do:
  - Go back to the last transition point. For example, if you made a mistake at the point where you switched slides in a deck, go back and resume recording from there.  
  - Cut the mistake out of the recording later.

#### Test Record

It is a good idea to test record the three scenes before you do an actual course recording. Make sure to run the test for a few minutes to ensure that there are no issues. If you encounter one, go to [OBS Help](https://obsproject.com/help).

To test record:

1. Go **Settings** > **Output**. 
2. In the **Controls** pane, select **Start Recording**.

   ![controls](recording/images/controls.png)

3. Do all of the following:

   a. Perform a test that includes all three scenes: mic, screen, and webcam.
   b. Speak a few words to test the mic pick up.  
   c. In the **Controls** pane, select **Stop Recording**.

### Video Course Time Limit

When recording your video course, remember to keep it under seven minutes. If your video is longer than seven minutes, you are going to need to edit the content to comply with the time limit. If you need help editing content, contact KubeAcademy for assistance.

## Video Equipment

I need help here.

Tips for looking at the camera. Sit, or stand?
Tips for remembering content.
Tips for using a script.
Tips for not using a script.
Video Editing
Script editing

### Lights, Mics and Other 

I need input.

## Deploy Content
Deploying content to a public, production environment requires a number of steps. The following diagram covers many of the major steps. The blue boxes reflect activities most content contributors are actively engaged in doing.

![Image](https://docs.google.com/drawings/d/e/2PACX-1vQAcCAMyF1Gce3rpXToIyX02qoEFRf55gU9SbOprQaL1KE4nPjMvKWE5XqGI8zLYTG6stQ3Vq-HPYSH/pub?w=960&h=720)

We manage KubeAcademy content development much like any standard software development process - by building a backlog of tasks that need to be completed, prioritizing each task, and having members of the team (and community) complete the tasks based on match in skillset, time and interest.



