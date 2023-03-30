# DSI Course for Causal Inference

## Contents:
1. [Description](https://github.com/UofT-DSI/08-causal_inference#description)
2. [Learning Outcomes](https://github.com/UofT-DSI/08-causal_inference#learning-outcomes)
3. [Logistics](https://github.com/UofT-DSI/08-causal_inference#logistics)
4. [Assignments and Marking Scheme](https://github.com/UofT-DSI/08-causal_inference#marking-scheme)
5. [Policies](https://github.com/UofT-DSI/08-causal_inference#policies)
6. [Folder Structure](https://github.com/UofT-DSI/08-causal_inference#folder-structure)
7. [Acknowledgements and Contributions](https://github.com/UofT-DSI/08-causal_inference#acknowledgements-and-contributions)

## Description:
Causal inference allows us to connect the dots in our data and speak to the cause-and-effect relationship that one thing may have with another. In ideal conditions, a thorough experiment design will be repeatable to a high degree of consistency. In practice, however, many fields that apply data science require some form of cause-and-effect recognition solely from observational data. To do this, it is imperative to understand causality, how to define a causal research question, and what causal models can and cannot tell us from observational data.

The first two sections of this course focus on the why and what of research design, covering key motivations and concepts. The third and fourth sections provide an introduction to the technical side. You will learn how common causal models work, what they are meant to achieve, how to apply them, and perhaps most importantly, their limitations.

## Learning Outcomes
By the end of the course, learners will be able to:
1. Apply concepts of research design and causality
2. Analyze and formulate suitable research questions
3. Structure a robust experimental study
4. Evaluate the benefits and drawbacks of causal inference models
5. Implement common models and techniques
6. Think critically about causal inference with observational data

## Logistics

### Course Contacts
* Instructor: **Lorena Almaraz De La Garza** (she/they)
  * Email: l.almaraz@utoronto.ca
  * LinkedIn: https://www.linkedin.com/in/lalmaraz/

### Delivery instructions
The course runs synchronously over Zoom. It consists of three classes a week for three weeks, or nine classes in total. Classes are 6 PM - 8 PM EDT on Mondays and Thursdays, and 9 AM - 12 PM EDT on Saturdays. Being mindful of online fatigue, there will be one or two breaks during each class where students are encouraged to stretch, grab a drink and snacks, or ask any additional questions.

Tutorials take place an hour before class on Mondays and Thursdays (5 PM - 6 PM EDT), and a half hour before and after class on Saturday (8:30 AM - 9 AM and 12 PM - 12:30 PM EDT). Tutorials provide additional time to discuss the course content, assignments, and any questions. Attendance is not mandatory but may contribute to participation.

### Technology Requirements
1. We use RStudio for R examples and Jupyter Notebooks for Python examples, please take the time to ensure you are able to use either of these on your device.
2. A basic familiarity with either programming language is expected for this course.

### Lesson Schedule
Subject to change as required.

| Date        | Lesson | Topic                                                                         | Slides     |
|-------------|--------|-------------------------------------------------------------------------------|------------|
| Mon, Apr 3  | 1      | Research Basics I: Designing Research and Research Questions                  | [Slides]() |
| Thu, Apr 6  | 2      | Research Basics II: Describing Variables, Relationships, and Identification   | [Slides]() |
| Sat, Apr 8  | 3      | Thinking About Causality: Causal Diagrams, Paths, and Treatment Effects       | [Slides]() |
| Mon, Apr 10 | 4      | Methods I: Regression, Matching, and Fixed Effects                            | [Slides]() |
| Thu, Apr 13 | 5      | Methods II: Diff-in-diff, Instrumental Variables, and Regression Discontinuity| [Slides]() |
| Sat, Apr 15 | 6      | Methods III: Practice                                                         | [Slides]() |
| Mon, Apr 17 | 7      | Professional Skills I: Causal Inference in Industry                           | [Slides]() |
| Thu, Apr 20 | 8      | Professional Skills II: Industry Case Study with Kamilah Ebrahim, BCG         | [Slides]() |
| Sat, Apr 22 | 9      | Review and Practice                                                           | [Slides]() |

## Assignments and Marking Scheme
| Assessment      | Weight | Due Date  |
|-----------------|--------|-----------|
| [Quiz 1]()      |10      |Sat, Apr 8 |
| [Assignment 1]()|15      |Mon, Apr 10|
| [Assignment 2]()|20      |Sat, Apr 15|
| [Assignment 3]()|30      |Thu, Apr 20|
| [Quiz 2]()      |10      |Sat, Apr 22|
| Participation   |15      |           |

Assignments are due before class on the date stated above. Please submit assignments as a PDF by emailing the instructor and using the following format for the subject line: ``DSI: [Assignment #], [Name]``.

## Policies
The course covers research theory, techniques for causal design, and coding examples in R and Python. Learners are encouraged to try to use the language most relevant to their field, even if it's not the language they're most comfortable with. Learners are expected to critically engage with the content, think about practical examples from their specific fields, and ask questions throughout. Should learners need accommodations or flexible arrangements, they are kindly asked to contact the instructor.

### Zoom
 1. Camera is optional although highly encouraged. We understand that not everyone may have the space at home to have the camera on.
 2. Please keep your microphone muted unless you are speaking and be mindful of noise in your environment.

### Assignments
1. Assignments are due before class on the date stated above. Please submit assignments as a PDF by emailing the instructor and using the following format for the subject line: ``DSI: [Assignment #], [Name]``.
2. There is no penalty for late assignments but justification via email is required. Note that late assignments might negatively impact the learner's progress towards subsequent assignments, however.

### Academic Integrity
1. Citations are necessary for all works that are not the learner's authorship — this includes code found online; learn more about citations here: https://guides.library.utoronto.ca/c.php?g=251103&p=1741147
2. Learn more about the University of Toronto's stance on academic integrity here: http://academicintegrity.utoronto.ca/

## Folder Structure
There are two folders contained in this repo:

### 1. *assignments*:
This folder contains the assignments for the workshop. Learners are expected to complete them by the established due date.

### 2. *slides*:
This folder contains the PDF and PPT versions of the slides. Slides will be uploaded after class.

## Acknowledgements and Contributions
## Acknowledgements
* Primary textbook for this course: Nick Huntington-Klein, 2021, The Effect: An Introduction to Research Design and Causality, https://theeffectbook.net/
* We wish to acknowledge this land on which the University of Toronto operates. For thousands of years, it has been the traditional land of the Huron-Wendat, the Seneca, and most recently, the Mississaugas of the Credit River. Today, this meeting place is still the home to many Indigenous people from across Turtle Island and we are grateful to have the opportunity to work on this land. Visit https://www.whose.land/en/ to learn about the peoples and histories of the place you join us from.
* The instructor acknowledges her positionality as a light-skinned woman of colour, a Mexican-Canadian, and a person living with an invisible disability, and acknowledges the myriad ways in which these identities have shaped her worldview and relationship to power. Examples shared in this course might be biased toward this lived experience. The instructor trusts the learner to integrate their own positionality as they participate in the course, use examples as a point of reference, and — if they are comfortable doing so — enhance the collective experience by sharing their own reflections and perspectives.
### Contributions 
* This is the first iteration of the Causal Inference course. We welcome your critical feedback, requests, or other contributions to improve it. To submit an issue, comment on our Feedback session in Padlet (https://padlet.com/lalmaraz2/202304-dsi-causal-inference-b2suuln8se4e4m16) or create a new ticket here: https://github.com/UofT-DSI/08-causal_inference/issues.
