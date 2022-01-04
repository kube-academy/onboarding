# KubeAcademy from VMware Contributor's Guide

The KubeAcademy from VMware Contributor's Guide is written exclusively for instructors and practitioners who are creating course content for KubeAcademy. KubeAcademy provides free Kubernetes training for beginner, intermediate, and advanced skillset levels. 

With Kubernetes constantly evolving in ability, power and speed, so does the need to create timely, relevant course content with appropriate depth. It's one reason why KubeAcademy is always looking for Kubernetes experts in the Cloud Native and Kubernetes communities who are interested in creating and reviewing course content. 

## Can Anyone Contribute to KubeAcademy?

At the present, KubeAcademy is only able to accept course contributions from VMware employees because of the way our submission process works. We are currently updating the submission process so that any member of the Cloud Native or Kubernetes communities may contribute to KubeAcademy. 

## How to Submit a Content Proposal to KubeAcademy

KubeAcademy uses a GitHub repository to manage its course backlog. This backlog is open to the public.  If you would like to submit a content proposal to KubeAcademy, you must complete and submit the KubeAcademy Content Proposal available in the KubeAcademy Backlog.

To submit a content proposal, 

1. Go to the [GitHub Kube-Academy Issues Backlog](https://github.com/kube-academy/backlog/issues) and select **New Issue** at the top of the page. 

   The KubeAcademy Content Proposal option appears. 

2. Select **Get started** at the top of the page to open the KubeAcademy Content Proposal. 
3. Complete the proposal as follows:

   - In the Proposed Content Title, enter a title for the content.
   - For Target, indicate whether the content is a course or a lab by selecting the corresponding option.
   - For Course Description, provide two or three sentences that describe the content.
   - For Prerequsites, provide any prerequisites from a KubeAcademy course or lab.
   - For Learning Outcome, provide a summary of what you expect the learner to know after completing the course.
   - For Example, identify and summarize the important primitives of Kubernetes architecture.
   - For Reference, provide a link that references student learning outcomes.
   - For Outline, present your outline in the sequential order that you plan to teach each lesson and lab in the video. 

4. Attach any files that you would like to include with the content proposal.
5. Select **Submit new issue**.
   Your content proposal is added to the Kube-Academy Backlog.

### Course Outine Approval

Your course outline is going to require approval from the KubeAcademy team. Use the [KubeAcademy New Course Proposal](https://github.com/kube-academy/onboarding/blob/main/templates/new-course.md) form to submit the course outline. 

When adding your course outline, make sure to display it in the sequential order that you plan to teach each lesson and workshop in the video. Other information required on this form includes the course title, description, prerequisites, and learning outcomes.

When the form is complete, copy, and paste its content into your new GitHub issue so that the KubeAcademy team can review it. 

Once your course is approved, a member of the KubeAcademy team will contact you. Do not begin work on the new course until you receive approval.

## Instructor Onboarding 

Instructor onboarding includes ensuring that you have the proper equipment to record a high quality video for KubeAcademy, and verifying that the equipment works accurately by submitting a **Hello World** video sample to KubeAcademy for review.

Note: For instructions on how to create the **Hello World** video sample, go to the section, **Create a "Hello World" Video Sample**.

To record a video, you need:

- Video equipment
   - Camera. Use a 1080p webcam or camera, at a minimum. For example, Logitech c920s.
   - Microphone. Use the one with your webcam or add an external Mic such as xxxxx.
   - Video Lighting (*optional*). Consider a one light setup, two light setup, or three point light setup.
- Video recording software. For example, [Open Broadcaster Software (OBS)](https://obsproject.com/).
- The [KubeAcademy Course Creation Template](https://drive.google.com/file/d/1hD6-2eKwSTa1WJKSJq_mj3NRS3K_5HOD/view?usp=sharing).

### Video Lighting (Optional)

There are a couple of different ways to set up lighting for your video. This includes one-point lighting, two-point lighting, and three-point lighting.

- **One-point lighting** is made up of a single, key light. You can position the key light as top-down, side, or ring lighting.
- **Two-point lighting** is made up of a key light, and a fill light. The key light is the primary, and brightest light between the two. The purpose of the fill light is to improve the illumination of the key light by lightening the shadows in a video. 
- **Three point lighting** is made up of a key light, a fill light, and a backlight. The key light is the primary, and brightest light between the two. The purpose of the fill light is to improve the illumination of the key light by lightening the shadows in a video. The backlight provides depth to the video by creating a rim light that pushes you away from the background. 

### Video Recording Software

The course developers at KubeAcademy use [Open Broadcaster Software (OBS)](https://obsproject.com/) to create videos. It is a free and open source software that is available for Linux, Mac, and Windows operating systems. OBS lets you set up scenes for input devices such as a microphone, camera or screen.  

For instructions on how to configure OBS for Kube Academy videos, see [OBS](obs.md).

## KubeAcademy PowerPoint New Course Template

The [KubeAcademy PowerPoint New Course Template](https://drive.google.com/file/d/1hD6-2eKwSTa1WJKSJq_mj3NRS3K_5HOD/view?usp=sharing) is where you add the content for your video course, including a video of yourself teaching the course, the course title, agenda, slide titles and instructional content.

### Create a "Hello World" Video Sample

A **Hello World** video is a 1 - 3 minute sample video that you create and submit to the KubeAcademy before you start recording the new course. This is so the KubeAcademy team can ensure that OBS, your video and mic are working properly, and to assist you with any issues if they are not.

To create a Hello World video sample with sound:

1. Open the [KubeAcademy PowerPoint New Course Template](https://drive.google.com/file/d/1hD6-2eKwSTa1WJKSJq_mj3NRS3K_5HOD/view?usp=sharing) in the KubeAcademy Onboarding Google Docs folder.
2. Go **File** > **Make a Copy** > **Entire Presentation**.
3. From the template copy, go **File** > **Rename** to rename your Hello World video sample. Save it to your GitHub folder containing the templates.
3. In Slide 1, do all the following:

   - Insert the sample MP4 video over the **PLACE YOUR VIDEO HERE** box.
   - Replace **Title** with the title of your course.
   - Replace **Subtitle** with **Video Course Sample**
   - Replace **Speaker's Name**, and **Role/Title** with your name, role or title.

3. In two or more of the other slides, continue to add sample content.
4. Delete any slides from your Hello World video sample that you did not use.
4. Go to the [KubeAcademy backlog](https://github.com/kube-academy/backlog/issues) in GitHub.
5. Attach the Hello World video to the issue that you created for your course in GitHub.

It is a good idea to test record the three scenes before you do an actual course recording. Make sure to run the test for a few minutes to ensure that there are no issues. If you encounter one, contact the KubeAcademy team through Slack at ?, or go to [OBS Help](https://obsproject.com/help).

### Test Record using OBS

1. From OBS, go **Settings** > **Output**. 
2. In the **Controls** panel, select **Start Recording**.

   ![controls](recording/images/controls.png)

3. Do all of the following:

   a. Perform a test for three different scenes: mic, screen, and webcam.
   b. Speak a few words to test the mic pick up.  
   c. In the **Controls** pane, select **Stop Recording**.

## Create the Video Course

How do you use OBS and Powerpoint to create the video? 

### Video Course Guidelines

When recording your video, do all the following:

 - Keep the recording time to under seven minutes for each lesson in your course. If your video is longer than seven minutes, it is going to require editing stay within the time limit. If you need help editing content, contact KubeAcademy for assistance.
 - Keep the size of your powerpoint slides under 10MB. If the file is too large, it may not attach to your GitHub issue.
 - Save your video course as an MP4 file. 

### Frequently Asked Questions Video Guideines

When creating a video of frequently asked questions (FAQs), do all the following:

- Keep the recording time between three to five minutes for a video of frequently asked questions. 

## KubeAcademy from VMware Brand Requirements for Instructors

VMware brand names such as **KubeAcademy from VMware** are essential elements of the company’s identity. KubeAcademy encourages all instructors to become familiar with the [The VMware Brand Voice Guidelines](https://www.vmware.com/content/dam/brand/photography-only/guidelines/writing-and-naming/brand-voice-guide/VMware-Brand-Voice-Guidelines.pdf) when referring to VMware brand names in a course.

### KubeAcademy from VMware Instructor Brand Apparel

VMware and KubeAcademy from VMware brand apparel are the only types of branded apparel that an instructor may wear in a KubeAcademy video course. This applies specifically to hats, jackets, shirts, sweaters, and sweatshirts. 

### Kubernetes Academy Brand Video Backgrounds

There are two official KubeAcademy backgrounds. These include: [KubeAcademy White](https://drive.google.com/file/d/1QcN_oPjshLARn0-C6TKqUIbSHKkuzHsB/view?usp=sharing), and [KubeAcademy Black](https://drive.google.com/file/d/1hD6-2eKwSTa1WJKSJq_mj3NRS3K_5HOD/view?usp=sharing). You also have the option of using a Green screen.

## Scriptwriting Guidelines

Voice and tone are important elements of the VMware brand. How you sound is as important as what you say. When writing your script, refer to the [VMware Marketing Editorial Style Guide](https://www.vmware.com/content/dam/brand/photography-only/guidelines/writing-and-naming/editorial-style-guide/marketing-editorial-style-guide.pdf) for specific instructions on branding, voice and tone, and inclusive terminology. 

Here are a few guiding principles:

- Write your script in a pleasant, conversational tone that encourages your audience to want to keep learning Kubernetes. 
- Use plain language that your audience can understand.
- Use active-voice verbs and passive-voice verbs as little as possible. 
- When introducing a term for the first time, make sure to provide a brief definition or explanation. For specialized terminology and brand names, always introduce the full term on the first reference along with its corresponding acronym, if you plan to reference it elsewhere in the course.
- Know your audience. Demonstrate that you undertand their challenges and they will trust your solutions.
- Elevate KubeAcademy relevance. Unexpected examples that highlight KubeAcademy's unique approach and value can go a long way.

### Terminology Do's and Do Not's

The following terminology guidelines identify specific types of terms that you cannot use in your scripts. For a list of terminology that you cannot use in scripts or workshops submitted to KubeAcademy, go to https://source.vmware.com/portal/pages/global-marketing/terminology-changes.

When writing a script, consider the following terminology do's and do not's.

- **Do** 
   - use words that are neutral and positive. 
   - use gender-neutral terminology, unless it is relevant to the content. For example, use **they** instead of **he** or **she** and **person hours** instead of **man hours**. 
   - use non-violent terms that imply pain or degradation. For example, use **turn off the switches** instead of **kill the switch**.
   - use terms that are free of ableism. For example, use **challenge** instead of **handicap**; use **sanity check** instead of **confidence check**.
- **Do not** 
   - use terminology that is jargon and slang.
   - use charged terminology. This includes words with shock value that demean, hurt, imply negative judgment.
   - objectify persons. For example, do not use **male** to signify a plug. Do not use female to signify a socket.

## Deploy Content

Deploying content to a public, production environment requires a number of steps. The following diagram covers many of the major steps. The blue boxes reflect activities most content contributors are actively engaged in doing.

![Image](https://docs.google.com/drawings/d/e/2PACX-1vQAcCAMyF1Gce3rpXToIyX02qoEFRf55gU9SbOprQaL1KE4nPjMvKWE5XqGI8zLYTG6stQ3Vq-HPYSH/pub?w=960&h=720)

We manage KubeAcademy content development much like any standard software development process - by building a backlog of tasks that need to be completed, prioritizing each task, and having members of the team (and community) complete the tasks based on match in skillset, time and interest.

### Report Content Issues

One of most beneficial things the Cloud Native and Kubernetes communities can do to ensure the integrity of content at KubeAcademy is to let us know when there is inaccurate or out of date content, or you find a defect in a course, course description, or lab. 

To report a content issue:

1. [Add the issue to the KubeAcademy backlog](https://github.com/kube-academy/backlog/issues). The KubeAcademy backlog keeps track of defects, course update requests, and new course proposal ideas.

2. Do one of the following:
   - [Submit a Defect Report](https://github.com/kube-academy/onboarding/blob/main/templates/defect.md) if there is an issue with the content you would like to report. If possible, include steps that reproduce the issue.
   - [Submit an Update Course Request](https://github.com/kube-academy/onboarding/blob/main/templates/update-course.md) to report a course that is in need of a major update, has content that is out of date, or is no longer valid, and should be archived.

KA: We create a folder in kube-academy/backlog/courses/<course-name> and populate with template files...
Course Creation
KA Team To Dos
Invite to KA bi-weekly
Access to KA Drive (VMware Employees)
Outline
Outline.md
Script & Slides
Script.md
Slides PPT (up to 10MB)?
If too large, share via Google Drive or other appropriate sharing
Note: We can move to KA Google Drive at VMware…
Video Recording
MP4 File
Course Metadata (for publishing to site)
Contributor Bio
Course Name
Course Description
Lesson Description

To Do:
Check base level permissions for repository for contribution requests/etc.
https://github.com/kube-academy/backlog
Use backlog for all issues related to roadmap	
Create Github Templates
Bug Report 
Recording Setup Template
New Course Proposal
Update Course Proposal

