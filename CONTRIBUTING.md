# Contributing to KubeAcademy
Thanks for your interest in contributing! The purpose of this document to help explain various ways in which you can contribute. We not only need content contributions but help with process improvements and reviewing content and testing labs!

## Kube Academy Mission 
Our mission at Kube Academy is to lower the barrier for anyone wanting to learn and adopt Kubernetes by providing free Kubernetes knowledge, directly from experienced practitioners.

## Community
KubeAcademy is built with a love and passion for the Cloud Native and Kubernetes communities. The Cloud Native ecosystem moves fast and that covering each area with appropriate depth is challenging. We need community contributions to keep up in this fast moving space. It is why we are seeking experienced practioners to contribute content, review content, and even provide input on how best to streamline the content contribution process.

### Eligibility
At this time we are only able to accept course contributions from VMware employees. We do plan to expand elegibility in the future as we streamline our process. 

If you are not a VMware employee, however, there are ways you can contribute. First, please report any [defects](#Defects) you find.

### Slack Channel
On VMware slack, we are on the #KubeAcademy slack channel. Let us know if you are interested in contributing and we can help you get started.

## Content Creation Process
This document describes the content creation process for Kube Academy courses. This includes setup instructions on how to record a video, and steps on how to write a script.

Each course is comprised of multiple lessons which cover specific topics related to the course.  Our courses are presented in video format delivered by instructures as a lecture or a demo (or both).  We also have recently introduced labs that provide learners with a hands-on environment and is powered by [Educates](https://github.com/eduk8s).

### KubeAcademy and KubeAcademy Pro
We have both short-form courses on KubeAcademy as well as longer-form courses available on KubeAcademy Pro. Both types of courses are completely free, although KubeAcademy Pro does require registration.

The primary distinction between KubeAcademy and KubeAcademy Pro is the time commitment required of the learner and the depth of coverage of each topic in the course. KubeAcademy Pro courses cover topics in more depth and have an overall longer duration for the course as well as longer lesson runtimes. 

When someone submits a course for development, we will identify whether the course is better suited for one format or the other.

#### Courses

When creating a course, 
Course:
- An introduction that summarizes the lecture.
- A course is comprised of one or more lessons
- A couse may optionally include a Lab
- A course must have an Intro Lecture 
- A course must have an Summary Lecture
- Lessons can be:
    - Standard Video Lecture
    - Video Demo
    - Combination Video Lecture and Demo
    - **Note:** Lessons for KubeAcademy must be under 10 minutes; Lessons for KubeAcademy Pro have no maximum time limit.
- Labs
    - Developed using [Educates](https://github.com/eduk8s)

#### Exception: FAQ Course

One exception to the above definition of a course is the FAQ "course". The intent of the FAQ "course" is to represent short bite-sized lessons that do not depend upon other material. It supports both an easy entry point for learners and a way for contributors to get started with the video production format of creating courses

### Other Content

(Coming Soon) In addition to video content, we are planning future releases to include written content in the form of Articles.

### Recording Video Content

See our document on [recording lessons with OBS](recording/obs.md) to get started recording video content.

## Process
Deploying anything to a public/produciton environment requires a number of steps that often go undocumented. In the interest of completeness, the following diagram covers many of the major steps. The boxes shaded in blue are intended to reflect activities most content contributors will be actively engaged in.

![Image](https://docs.google.com/drawings/d/e/2PACX-1vQAcCAMyF1Gce3rpXToIyX02qoEFRf55gU9SbOprQaL1KE4nPjMvKWE5XqGI8zLYTG6stQ3Vq-HPYSH/pub?w=960&h=720)

We manage KubeAcademy content development much like any standard software development process - by building a backlog of tasks that need to be completed, prioritizing each task, and having members of the team (and community) complete the tasks based on match in skillset, time and interest.

We have identified three different types of requests that will come into the backlog:
- Defects
- Course Update Proposal
- New Course Proposal

> **_Note:_** We are using Github Issues for managing the document process. While the site content is not in the repository, we are exposing a repository, backlog, for communicating requests and reporting issues.

### Defects
Content, like software will have defects. If you identify anything incorrect in the website, in a course or lecture content, please submit a Github Issue providing the following information:

https://github.com/kube-academy/onboarding/blob/main/templates/defect.md

Github Repo:
[Issue Repo](https://github.com/kube-academy/backlog/issues)

### Course Update Proposal
Beyond defects, when a course becomes out of date or needs more signifiant change than can be captured in a defect report, please make a request using the following course update template:

https://github.com/kube-academy/onboarding/blob/main/templates/update-course.md

Github Repo:
[Issue Repo](https://github.com/kube-academy/backlog/issues)

### New Course Proposal
In order to request a new course, please make a request using the following template:

https://github.com/kube-academy/onboarding/blob/main/templates/new-course.md

Github Repo:
[Issue Repo](https://github.com/kube-academy/backlog/issues)

### Backlog
(In Progress)
[KubeAcademy Course Backlog](https://github.com/orgs/kube-academy/projects/3)

