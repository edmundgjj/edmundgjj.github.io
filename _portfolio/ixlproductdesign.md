---
layout: single
title: "IXL Product Design Challenge"
permalink: /ixl
excerpt: "Enhance student's online learning and practice experience and design a new homework assignment feature"
last_modified_at: 2016-11-03T10:01:43-04:00
author_profile: true
sidebar:
  nav: "portfolio"
---


{% include toc %}

## Introduction

### About IXL Learning

IXL is an immersive online learning platform that provides standards-aligned practices for Math, Language arts, Science and Social Studies, covering more than 6000 skills for K-12 students.Through highly interactive content and an adaptive learning system, students are not only engaged in practicing but also develop concepts and skills mastery that prepares them for school, standards assessment and eventually lifelong learning.

### What did I do for the project?

*   Wrote a short paragraph to describe IXL to teachers
*   Conducted user research through in-depth interviews with K-12 teachers for product design
*   Made four product enhancement recommendations that included:
    1.  Include behavioral design elements like social proof and healthy competition to enhance the user engagement
    2.  Enhancing UI for learning progression while students practice their questions to improve motivation
    3.  Proposed alternative scoring methods for Challenge Zone to current points-based UI to create a more satisfying experience
    4.  Offline access to practices for students on mobile and tablet applications.
*   Design the homework assignment feature for students and teachers

This project took me a total of 4 days from research, designing the features, making the prototypes to finally, documenting and writing the proposal.

### Tools that I used for this project

*   Sketch for UI wireframes and grayscale prototypes
*   Lucidcharts for user flow
*   Invision for interactive prototype
*   Deployed Jekyll for online documentation of design process

## My Research and Design Process

To formulate product recommendations that really meet user needs, I conducted in-depth one-on-one interviews with 4 teachers with K-12 and High School teaching experiences. Additional research also included studying user feedback to identify pain points and domain expertise research for potential product opportunities and innovation.

<table class="table">

<thead>

<tr>

<th></th>

<th>Teacher F</th>

<th>Teacher Y</th>

<th>Teacher W</th>

<th>Teacher J</th>

</tr>

</thead>

<tbody>

<tr>

<td>Years of experience</td>

<td>11</td>

<td>13</td>

<td>13</td>

<td>6</td>

</tr>

<tr>

<td>Grades Taught</td>

<td>4 to 6</td>

<td>6, 7</td>

<td>2 to 5</td>

<td>High School</td>

</tr>

</tbody>

</table>

**Teacher F**

*   Coaches teachers on classroom management and English Language Speakers program
*   Expertise in 1-1 literacy guidance
*   Used IXL LA for 1 year after parent donated license to class.

**Teacher Y**

*   In charge of 6th grade LA curriculum design
*   Emphasis of 21st Century Learning Framework and Multi Engagement
*   Sit on the Common Core alignment committee
*   Hosted California Secretary of Education to demonstrate effective classroom use of technology like Apple TV, Google Docs, Expedition

**Teacher W**

*   Have experience implementing Renaissance reading program softwareto help students improve reading habits and scores.
*   Taught in low-income communities
*   In charge of Language Arts and Social Studies lesson plan and pacing guide
*   School did not have resources to provide technology

#### Aims of interviews

Through face-to-face interviews, I was able to hear first-hand recounting of narratives and was able to observe emotions of the interviewees. It helped me to develop a better understanding of what teachers really feel deeply about and how their day-to-day experiences have shaped their perspectives on how students are engaged in learning and the challenges they face in classrooms.

#### Some Key Learning Points

One of key learning points was recognizing the deeply social environment that IXL or any educational technology product (google expeditions, renaissance program etc.) is embedded in. There are social behavioral traits such as social proof, social recognition and competitiveness exhibited amongst the students where they enjoy challenges and competing with one another.

In addition, teachers also have a deep desire for autonomy in deciding the best means to help their students. This desire is rooted in the belief that their professional training and close relationships with the students cannot be replaced by any technology solution. This means that any technology solution needs to have a teacher-first focus.

Moreover, different teachers have different teaching styles and aptitude to implement technology solutions. Teaching tools like IXL should have features that are modularized and be flexible enough to fit into different teaching scenarios.

Even without quantitative data, it is even more so crucial that the design process relies on reliable qualitative data. At the initial phase of prioritizing product ideas to work on, we can use the data points to help prioritize product ideas to work on and crearte user stories and personas with the data collected during the research phase.

For conciseness, I have condensed six main insights that I have derived from my preliminary research phase in Appendix A.

#### Design Method

I used grayscale design for wire-framing and prototyping as I'm less concerned about the visual aesthetics but instead, am focused on the overall layout and product functionalities. Without needing to worry about pixel perfection, I am able to make strategic product decisions concerning UI and user flow.

Grayscale design also has the benefit of visual hierarchy by virtues of contrast over a basic wireframe that only uses lines. As I'm proficient in Sketch, I am able to mock-up the wireframe as quick if not quicker than drawing on pen and paper, with a consistency and tidy-ness that I'd personally prefer. It helps me to communicate my product ideas to engineers and other product managers without being too abstract or missing details in my design elements.

However, I strongly believe that the prototyping process and the kind of design style used should be up to the designers as long as it helps them to communicate product ideas effectively.

## Prompt One: How would I describe IXL to a teacher?

IXL is an immersive online learning platform that provides standards-aligned practices for Math, Language arts, Science and Social Studies, covering more than 6000 skills for K-12 students.

Through highly interactive content and an adaptive learning system, students are not only engaged in practicing but also develop concepts and skills mastery that prepares them for school, standards assessment and eventually lifelong learning.

IXL can be adapted to your teaching style be it flipped classroom to 1:1 and with the analytics tools, you can personalize instruction and feedback to help every student to excel by pinpointing their weaknesses and monitoring their progress.

#### Identifying value propositions of the product:

<table class="table table-condensed">

<thead>

<tr>

<th>Helping Students to Learn</th>

<th>Helping Teachers to Teach</th>

</tr>

</thead>

<tbody>

<tr>

<td>

<ul>
<li>Standards-aligned practices</li>
<li>Subjects include Math, Language Arts, Science & Social Studies</li>
<li>Practice more than 6000 skills</li>
<li>
  <ul>Interactive Content
      <li>Visual Graphics</li>
      <li>Virtual Rewards System</li>
      <li>Adaptive Difficulty</li>
      <li>Immediate Feedback</li>
  </ul>
</li>
<li>Geared towards skilled mastered and real understanding of concepts at hand</li>
<li>Preparation for school, standards assessments and lifelong learning</li>
</ul>

</td>

<td>

<ul>
<li>Suits any teaching style and classroom environments</li>
<li>Identify student needs through analytics</li>
<li>Adapt your teaching with actionable insights and information about every student's learning needs</li>
<li>Use it to teach skills aligned to school and district standards</li>
<li>View your students' practice in real-time</li>
</ul>

</td>

</tr>

</tbody>

</table>

## Prompt Two: New Product Recommendations

### Summary

I will be focusing on the product experience of the students, particularly, on enhancing the immersive learning experience while practicing. My recommendations are:

1.  Include social proof and healthy competition features to make practicing more fun and social.
2.  A new GUI to heighten sense of progression and motivation to continue practicing
3.  Consider using streak or token scoring for challenge zones.
4.  Allow students to download assignments for offline access on mobile and tablet.

### Why did I choose to focus on this?

As an online learning tool, our primary user are students and creating an immersive learning experience that consistently keeps students engaged is foremost for both business and product goals.

### 1. Include social proof and healthy competition features
