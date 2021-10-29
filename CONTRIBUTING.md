# KubeAcademy from VMware Contributor's Guide

The KubeAcademy from VMware Contributor's Guide is specifically for those developing content for KubeAcademy. It includes instructions on how to:
- Create a course, lesson, or lab.
- Write a script to read as you record the course, lesson or lab.
- Download and install Open Broadcaster Software (OBS) to record your video.
- Submit a Defect Report if you find a defect in a course, course description on lab.
- Submit an Update Course Request if you encounter an inaccurate or out of date course.

KubeAcademy is built with a love and passion for the Cloud Native and Kubernetes communities. The Cloud Native ecosystem moves fast. Covering each area with appropriate depth is challenging. This is why we need community contributions to keep up in this fast moving space. It is why we are seeking experienced practioners to contribute content, review content, and even share your ideas on ways we can better streamline our content contribution process.

## How to Contribute Content to KubeAcademy
Thank you for your interest in wanting to contribute content to KubeAcademy from VMware. KubeAcademy provides free Kubernetes training for beginner, intermediate, and advanced skillset levels. We invite you to check out our [GitHub Repository Backlog](https://github.com/orgs/kube-academy/projects/3) for contribution ideas. 

We also welcome ideas for developing new courses. To submit your idea for a new course, go [here](https://github.com/kube-academy/onboarding/blob/main/templates/new-course.md).

### KubeAcademy Slack Channel

There is a #KubeAcademy Slack channel on VMware Slack. This is a good place to let us know of your interest in contributing to KubeAcademy. 

## Can Anyone Contribute to KubeAcademy?

At the present, KubeAcademy is only able to accept course contributions from VMware employees because of the way our submission process works. We are currently updating the submission process so that any member of the Cloud Native or Kubernetes communities may contribute to KubeAcademy. 

## Content Types

KubeAcademy provides content in the following formats. 
- **Courses**. Each course is comprised of multiple lessons which cover specific topics related to the course.  Our courses are presented in video format delivered by instructures as a lecture or a demo (or both).  We also have recently introduced labs that provide learners with a hands-on environment and is powered by [Educates](https://github.com/eduk8s). This includes setup instructions on how to record a video, and steps on how to write a script.

When creating a course, ensure it includes all the following:
- An introduction that summarizes the lecture.
- The course is comprised of one or more lessons
- A couse may optionally include a Lab
- A course must have an Intro Lecture 


    Note: The FAQ "course" represents mini-lessons that do not depend upon other material. It supports both an easy entry point for learners and a way for contributors to get started with the video production format of creating courses
- **Lessons**. Lessons for KubeAcademy must be under 10 minutes; Lessons for KubeAcademy Pro have no maximum time limit. Lessons can be:
   - Standard Video Lecture
   - Video Demo
   - Combination Video Lecture and Demo 
- **Labs**. Each lab is developed using [Educates](https://github.com/eduk8s). 
- **Articles** (Coming Soon) Future content releases are going to include written Articles.


### Recording Video Content

See our document on [recording lessons with OBS](recording/obs.md) to get started recording video content.

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

