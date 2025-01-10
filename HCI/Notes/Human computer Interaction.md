
2024-08-22

tags: #HCI, #UI #UX, 
topics:


HCI is the interaction between the human and the computer. But in reality it is just the interaction between a human and a task with computer as a mediator. Ideally we're trying to make the interface as invisible as possible so users can focus on the task effectively.

HCI is a huge field and is a subfield of Human factors engineering. 
Human factors engineering includes designing products which doesn't have the computer in them. For example, the steering and seat height adjustment in a car is a human factor engineering.
HCI just focuses on the interaction between humans and computers like the radio in a car.

![[Pasted image 20240820110432.png]]

UI design is about interaction with a single screen, but HCI covers more general methods that apply to any interface. UX design is about creating designs whereas HCI is about understanding them and so they have a symbiotic relationship. The understood designs are implemented as UX designs and if it doesn't work well we change the understanding and so it is a feedback cycle.
HCI is also related to human psychology and that too is a symbiotic relationship. Researchers at Apple designed file system management using the psychology that people tend to unorderly pile up file that relate to a similar subject.
HCI is about researching designs which includes need-finding, prototyping and evaluation to find what people require and then use that information to design interfaces with principles such as distributed cognition, mental models and universal designs. 
**The results of user research informs the designs and the results from designs informs the research.**

Learning goals of HCI:
1. To design interfaces
2. Effectiveness of interfaces depends upon the goals we have while designing them. It can be either for usability, or for research or to make a change in something. Generally we assume it is usability.
3. To design interfaces that emphasis on human's role in interaction (tasks).

Applications of HCI

Applications can be thought to be in 3 different categories:
According to technology:
1. Virtual reality
2. Augmented reality
3. Ubiquitous computing and wearables: Computers are everywhere including on our hands nowadays
4. Robotics
5. Mobile: eg, why doesn't people use mobile devices to write essays and read books?
According to idea:
1. Context-sensitive computing: Devices detect environment and context. Mobile understands if user is walking or driving etc.
2. Gesture based interaction: gesture to control devices. Fitbit using hand movements to detect exercises, Kinect have applications in healthcare to gaming
3. Pen and Touch based interaction: Pens in education courses
4. Information visualization: data can be visualized in complex and interactive ways. Goal is to match reader's mental model to the reality.
5. CSCW (computer supported cooperative work): Using computers to support people working together. Distributed team working on a project, a pre-recorded course, chat apps etc. 
6. Social computing: chat online with emoticons
According to domains:
1. Special needs: prosthetic hands, communicating data using sound, autonomous wheelchair
2. Education: Online courses
3. Healthcare: VR in medical field, patient analysis, fitbit etc
4. Security: CAPTCHA that doesn't interfere with user experience, make users create good passwords by ranking the security of passwords with others to make it fun.
5. Games: How users control players, penalties for failure are too high/low etc.


#### Principles of HCI

Interfaces mediate between users and their tasks. 
While designing an interface we have to focus on the task not just the interface.

How to identify a task:
1. Watch real users
2. Talk to them
3. Start small: Observe small operations that users perform
4. Abstract up: Combine small operations to understand what she is trying to achieve
5. You are not the user

Views of the user:
There are three possible roles a user can play in an interface:
1. Processor: The interface must fit within known human limits like colors that can be seen, memory that can be stored etc. We evaluate this by using quantitative experiments like numeric measurements.
   It comes from the behaviorism field of psychology which tries to understand behavior just by using the human behavior and not any cognition that takes place.
3. Predictor: Here we care about user's knowledge, experience, expectations and their thought process. The interface must fit within their knowledge, and we evaluate this by qualitative studies called ex situ studies such as task analyses to see where users are spending their time. 
   It comes from cognitive psychology field of psychology which uses what goes inside user's head like what he thinking. While designing interfaces, we try to understand how user will predict how the interface will behave.
1. Participant: This view takes into consideration what the users are doing around it like other tasks they're involved in. So the interface must fit with the context they're in and this is evaluated by In situ studies. This is trying the interface in the relevant context.
   It comes from functionalism view of psychology. This model views users and interface as participants within a larger complex cognitive system.

![[Pasted image 20240827094139.png]]

While working on a task, we'll be using all three methods to make the right decisions. For some cases we might implement something using predictor method and then evaluate the results using processor method. To understand how it all works out in real scenarios we look into participant methods.

![[Recording 20240827095302.m4a]]


There are different detailed design principles laid out by different authors. A compiled version with the important 15 design principles are given by Dr. Joyner and is summarized in [[HCI - design principles (2.5)]] (Ed lesson 2.5).
### Feedback cycles

Almost all of the development in any field happens with feedback cycles

![[Pasted image 20240827151729.png]]
#### Gulf of execution

This is the gap in knowledge of the users in knowing what they can do with an interface.
The user will have a goal to achieve and they need to know how to execute that goals to make it a reality with the interface.
1. Identify intentions: Users need to understand what their goal is the context of the interface
2. Identify actions: Find the actions they need to do to achieve their goal
3. Execute in interface: Do the identified actions in interface

Tips:
1. Make functions discoverable
2. Let the users mess around: No irreversible button
3. Be consistent with other tools: Use common shortcuts and icons
4. Know your user: Experts or novice users
5. Feedforward: Show users what the result of any action will be.

Gulf of evaluation
This is the task of letting the users know of the results of the actions that users took.
1. Interface output
2. : visual, audio, video or vibration modes of results
3. Interpretations: Users understanding the resulting output. Does users understand a vibration of the mobile in his pocket?
4. Evaluation: Has users understood that the goal they wanted to achieve was achieved or not using the interpretation.
An example of bad evaluation is when a user changes the temperature of the heater in a room and the thermostat gives no indication to the users that the temperature was changed. 
Tips:
1. Give feedback constantly, eg. got input, what input etc.
2. Give feedback immediately
3. Match the feedback to the action: subtle action - subtle feedback, Significant action - significant feedback
4. Vary your feedback: Maybe try audio
5. Leverage direct manipulation

### Norman's feedback cycle stages

On the left we have the Bridge of execution and on the right we have Bridge of Evaluation

![[Pasted image 20240827155330.png]]

In simpler terms:
![[Pasted image 20240827155555.png]]


## Research methods (Ed 3.1)

Designing a new interface is mostly improving what already exists. 
We'll need to design based on user's tasks in mind.

#### User centered design
It considers the needs of the user throughout the design process
Steps: 
1. Understand the needs and depth through **needfinding** 
2. Get feedback from users
3. Prototype a design
4. Evaluate the new design with new users

#### Principles of user-centered designs
1. The design is based upon an explicit understanding of users, tasks and environments.
2. Users are involved throughout design and development
3. The design is driven and refined by user centered evaluation.
4. The process is iterative
5. The design addresses the whole user experience. 
6. The design team includes multidisciplinary skills and perspectives.

#### Stakeholders
"User" is always loosely defined. The users actually include more people than just the direct user.
1. Primary: The main person who directly uses it.
2. Secondary: The people who are affected by the primary user.
3. Tertiary:  People who are affected by the system but doesn't interact with it at all.

### Design life cycle

1. [[HCI - Need finding]]: Understanding the task that user needs to perform
2. [[HCI - Design alternatives]]: To not get stuck on a single idea too soon.
3. [[HCI - Prototyping]]
4. [[HCI - Evaluation (3.6)]]: Get feedback and cycle begins again.

There are methods to get the required information in each of these stages and is shown:

![[Pasted image 20240827235303.png]]

We don't just go over the circle once. Once we do some initial needfinding, we create alternate designs and do some low fidelity prototyping like paper prototyping or verbal prototyping, then we evaluate it and based on the results, do the needfinding again to create alternate designs and then based on these designs, increase the fidelity of the prototyping which is then evaluated again. This cycle continues to create very high fidelity prototypes with good evaluation.

Types of data: 
Quantitative data: Numeric data: difficulty ratings, performance numbers etc.
Qualitative data: Descriptions, feedbacks etc. in natural language like surveys or bug reports.

Qualitative provides broader picture and is mostly used in design cycle, but hard to get conclusions. 
Quantitative can be converted to qualitative. 
Both serve different purposes. Quantitative:  What? Qualitative: How, why?

Types of quantitative data:

![[Pasted image 20240828082145.png]]

Single nominal is a list of options in which users can choose one and multi-nominal is where users can choose multiple from the options.
Ordinal will have a relevance to the order to the values in the list, like satisfaction levels. The options can be either binary (yes/no) or non binary.
Discrete values mean whole number values given by users, while continuous can be any number. Eg: When asked a user how much time they take to commute maybe 30 mins. This is a discrete value. If commute time is recorded it might be 37.25 mins which is continuous.

Types of qualitative data

There are several types of qualitative data like transcripts from interviews, field notes, artifacts and lot more. They can be converted to quantitative data using a method called coding.

#### Ethics and human research (Ed 3.2)

To be able to collect data from humans and design interfaces, we must follow some rules that'll protect the people who participate in the surveys.
The researchers must first complete a CITI training on IRB website to be able to do the research. This will allow us use IRBWISE website to create research program using protocols. We can be added to any existing protocols. There we'll have to provide all the details of the study we're conducting. We also have to get the consent form signed according to the Belmont report. Once this is submitted, it'll take 3 weeks to approve it.


### Direct manipulation (Ed 2.3)

Users must be able to directly manipulate everything on screen so it can be the most intuitive. 
Command line used to be the way to control files in a computer and then it was changed to a mouse to control files directly using the mouse. This was then changed to touch screens which is the most intuitive for novice users.

According to Norman and Hutchins:
Distance is the distance between the goals and the system itself.

![[Pasted image 20240903142332.png]]

There are two types of distances: semantic distance is the distance between the users goals and their expression in the system. Articulatory distance is the distance between the expression of the goals and its execution, meaning how hard it is to do things that he has in his mind.

![[Pasted image 20240903211140.png]]

Whenever we're interacting with a computer interfaces, we create a goal then an intention and then execute them. Then something happens in the computer and then user perceives and interprets it and evaluate it to see if the task was completed or not. If it is not, the task repeats.

**Direct engagement** is a part of direct manipulation which promotes interfaces that represent human interaction with physical objects, not just with programs.
An example of this is the action of drag and dropping files into a folder in a computer which mimics the same action in real life

Direct manipulation is not always about creating interfaces that feel like real activity but also about creating interfaces that gives us a feel of a real activity.
An example of this is the gestures on a laptop with different animations that gives us a feeling that things are moving according to our actions on our trackpad like swiping from the right to open up the notification bar.

#### Invisible interfaces

The interface sits between the user and the task. Direct manipulation helps to reduce the gulf of execution and helps get the user closer to the task which makes the interface invisible.

Tips for creating invisible interfaces:
1. Use affordances: places were visual design of the interface is just how its supposed to be used. buttons for pressing, dials for turning.
2. Know your user: Novice or expert
3. Differentiate your user: More detailed for novices, more efficiency for experts.
4. Let your interface teach: eg: Shortcut tutorials in the GUI
5. Talk to your user: get feedback

#### Human abilities (Ed 2.4)

Understanding humans is an important part of HCI. It also includes human psychology as well.
Humans can perceived the world through visual, auditory and haptic senses.

Humans have 3 different memory store:
1. Perceptual store
2. Short term memory
3. Long term memory

Perceptual store or working memory is the shortest memory where the images and audio that you see and hear stay in your memory less than a few seconds. It has three parts: visuospatial sketchpad for storing images, phonological loop for audio and episodic buffer for any kind of ordering. All of them are controlled by a central executive.

Short term memory can chunk four to five chunks at a time. Chunks are bits of information combined to one chunk to remember. So we cannot make users store too much in the short term memory at a time. It is also better to do recognition than recall while trying to make user recall something.

Its difficult to load things into long term memory as it requires us to load it to short term memory multiple times.

#### Cognition

Cognition is an important function of humans. There are two types of learning that we usually do. The procedural learning we automatically learn to do like using hotkeys and declarative knowledge where we intentionally learn something like conversing. 
Human brain has a limited amount of cognitive load. If we overload it with something less important, we might not have much left for more important tasks. We have to keep this in mind while designing interfaces. The interface should not take too much cognitive load so the task itself won't have enough load left. User will also have the overall context in his mind as well.

![[Pasted image 20240904093833.png]]

Tips to reduce cognitive load:
1. Use multiple modalities: Visual, audio, haptic etc.
2. Let the modalities complement each other: Different modalities should support and illustrate each other instead of competing
3. Give the user control of the pace: No timers to induce pressure. Let user control pace.
4. Emphasize essential content and minimize clutter: Let user have the most important actions while still giving the full range of actions.
5. Offload tasks: If there is anything users have to remember from previous page, show them that in the interface. If there is anything users have to do manually, see if it can be done automatically.

Human motor skills are also important and have to be considered for different contexts. People might not be able to click on small buttons in contexts like walking or running.

2024-08-22

tags: #HCI, #UI #UX, 
topics:


HCI is the interaction between the human and the computer. But in reality it is just the interaction between a human and a task with computer as a mediator. Ideally we're trying to make the interface as invisible as possible so users can focus on the task effectively.

HCI is a huge field and is a subfield of Human factors engineering. 
Human factors engineering includes designing products which doesn't have the computer in them. For example, the steering and seat height adjustment in a car is a human factor engineering.
HCI just focuses on the interaction between humans and computers like the radio in a car.

![[Pasted image 20240820110432.png]]

UI design is about interaction with a single screen, but HCI covers more general methods that apply to any interface. UX design is about creating designs whereas HCI is about understanding them and so they have a symbiotic relationship. The understood designs are implemented as UX designs and if it doesn't work well we change the understanding and so it is a feedback cycle.
HCI is also related to human psychology and that too is a symbiotic relationship. Researchers at Apple designed file system management using the psychology that people tend to unorderly pile up file that relate to a similar subject.
HCI is about researching designs which includes need-finding, prototyping and evaluation to find what people require and then use that information to design interfaces with principles such as distributed cognition, mental models and universal designs. 
**The results of user research informs the designs and the results from designs informs the research.**

Learning goals of HCI:
1. To design interfaces
2. Effectiveness of interfaces depends upon the goals we have while designing them. It can be either for usability, or for research or to make a change in something. Generally we assume it is usability.
3. To design interfaces that emphasis on human's role in interaction (tasks).

Applications of HCI

Applications can be thought to be in 3 different categories:
According to technology:
1. Virtual reality
2. Augmented reality
3. Ubiquitous computing and wearables: Computers are everywhere including on our hands nowadays
4. Robotics
5. Mobile: eg, why doesn't people use mobile devices to write essays and read books?
According to idea:
1. Context-sensitive computing: Devices detect environment and context. Mobile understands if user is walking or driving etc.
2. Gesture based interaction: gesture to control devices. Fitbit using hand movements to detect exercises, Kinect have applications in healthcare to gaming
3. Pen and Touch based interaction: Pens in education courses
4. Information visualization: data can be visualized in complex and interactive ways. Goal is to match reader's mental model to the reality.
5. CSCW (computer supported cooperative work): Using computers to support people working together. Distributed team working on a project, a pre-recorded course, chat apps etc. 
6. Social computing: chat online with emoticons
According to domains:
1. Special needs: prosthetic hands, communicating data using sound, autonomous wheelchair
2. Education: Online courses
3. Healthcare: VR in medical field, patient analysis, fitbit etc
4. Security: CAPTCHA that doesn't interfere with user experience, make users create good passwords by ranking the security of passwords with others to make it fun.
5. Games: How users control players, penalties for failure are too high/low etc.


#### Principles of HCI

Interfaces mediate between users and their tasks. 
While designing an interface we have to focus on the task not just the interface.

How to identify a task:
1. Watch real users
2. Talk to them
3. Start small: Observe small operations that users perform
4. Abstract up: Combine small operations to understand what she is trying to achieve
5. You are not the user

Views of the user:
There are three possible roles a user can play in an interface:
1. Processor: The interface must **fit within known human limits** like colors that can be seen, memory that can be stored etc. We evaluate this by using **quantitative** experiments like numeric measurements.
   It comes from the behaviorism field of psychology which tries to understand behavior just by using the human behavior and not any cognition that takes place.
3. Predictor: Here we care about user's knowledge, experience, expectations and their thought process. The interface must **fit within their knowledge**, and we evaluate this by **qualitative** studies called **ex situ** studies such as task analyses to see where users are spending their time. 
   It comes from cognitive psychology field of psychology which uses what goes inside user's head like what he thinking. While designing interfaces, we try to understand how user will predict how the interface will behave.
1. Participant: This view takes into consideration what the users are doing around it like other tasks they're involved in. So the interface must fit with the context they're in and this is evaluated by In situ studies. This is trying the interface in the relevant context.
   It comes from functionalism view of psychology. This model views users and interface as participants within a larger complex cognitive system.

![[Pasted image 20240827094139.png]]

While working on a task, we'll be using all three methods to make the right decisions. For some cases we might implement something using predictor method and then evaluate the results using processor method. To understand how it all works out in real scenarios we look into participant methods.

![[Recording 20240827095302.m4a]]


There are different detailed design principles laid out by different authors. A compiled version with the important 15 design principles are given by Dr. Joyner and is summarized in [[HCI - design principles]] (Ed lesson 2.5).
### Feedback cycles

Almost all of the development in any field happens with feedback cycles

![[Pasted image 20240827151729.png]]
#### Gulf of execution

This is the gap in knowledge of the users in knowing what they can do with an interface.
The user will have a goal to achieve and they need to know how to execute that goals to make it a reality with the interface.
1. Identify intentions: Users need to understand what their goal is the context of the interface
2. Identify actions: Find the actions they need to do to achieve their goal
3. Execute in interface: Do the identified actions in interface

Tips:
1. Make functions discoverable
2. Let the users mess around: No irreversible button
3. Be consistent with other tools: Use common shortcuts and icons
4. Know your user: Experts or novice users
5. Feedforward: Show users what the result of any action will be.

Gulf of evaluation
This is the task of letting the users know of the results of the actions that users took.
1. Interface output: visual, audio, video or vibration modes of results
3. Interpretations: Users understanding the resulting output. Does users understand a vibration of the mobile in his pocket?
4. Evaluation: Has users understood that the goal they wanted to achieve was achieved or not using the interpretation.
An example of bad evaluation is when a user changes the temperature of the heater in a room and the thermostat gives no indication to the users that the temperature was changed. 
Tips:
1. Give feedback constantly, eg. got input, what input etc.
2. Give feedback immediately
3. Match the feedback to the action: subtle action - subtle feedback, Significant action - significant feedback
4. Vary your feedback: Maybe try audio
5. Leverage direct manipulation

### Norman's feedback cycle stages

On the left we have the Bridge of execution and on the right we have Bridge of Evaluation

![[Pasted image 20240827155330.png]]

In simpler terms:
![[Pasted image 20240827155555.png]]


## Research methods (Ed 3.1)

Designing a new interface is mostly improving what already exists. 
We'll need to design based on user's tasks in mind.

#### User centered design
It considers the needs of the user throughout the design process
Steps: 
1. Understand the needs and depth through **needfinding** 
2. Get feedback from users
3. Prototype a design
4. Evaluate the new design with new users

#### Principles of user-centered designs
1. The design is based upon an explicit understanding of users, tasks and environments.
2. Users are involved throughout design and development
3. The design is driven and refined by user centered evaluation.
4. The process is iterative
5. The design addresses the whole user experience. 
6. The design team includes multidisciplinary skills and perspectives.

#### Stakeholders
"User" is always loosely defined. The users actually include more people than just the direct user.
1. Primary: The main person who directly uses it.
2. Secondary: The people who are affected by the primary user.
3. Tertiary:  People who are affected by the system but doesn't interact with it at all.

### Design life cycle

1. [[HCI - Need finding]] (Ed 3.3): Understanding the task that user needs to perform
2. [[HCI - Design alternatives]] (Ed 3.4): To not get stuck on a single idea too soon.
3. [[HCI - Prototyping]] (3.5)
4. [[HCI - Evaluation]] (3.6): Get feedback and cycle begins again.

There are methods to get the required information in each of these stages and is shown:

![[Pasted image 20240827235303.png]]

We don't just go over the circle once. Once we do some initial needfinding, we create alternate designs and do some low fidelity prototyping like paper prototyping or verbal prototyping, then we evaluate it and based on the results, do the needfinding again to create alternate designs and then based on these designs, increase the fidelity of the prototyping which is then evaluated again. This cycle continues to create very high fidelity prototypes with good evaluation.

Types of data: 
Quantitative data: Numeric data: difficulty ratings, performance numbers etc.
Qualitative data: Descriptions, feedbacks etc. in natural language like surveys or bug reports.

Qualitative provides broader picture and is mostly used in design cycle, but hard to get conclusions. 
Qualitative can be converted to quantitative. 
Both serve different purposes. Quantitative:  What? Qualitative: How, why?

Types of quantitative data:

![[Pasted image 20240828082145.png]]

Single nominal is a list of options in which users can choose one and multi-nominal is where users can choose multiple from the options.
Ordinal will have a relevance to the order to the values in the list, like satisfaction levels. The options can be either binary (yes/no) or non binary.
Discrete values mean whole number values given by users, while continuous can be any number. Eg: When asked a user how much time they take to commute maybe 30 mins. This is a discrete value. If commute time is recorded it might be 37.25 mins which is continuous.

Types of qualitative data

There are several types of qualitative data like transcripts from interviews, field notes, artifacts and lot more. They can be converted to quantitative data using a method called coding.

#### Ethics and human research (Ed 3.2)

To be able to collect data from humans and design interfaces, we must follow some rules that'll protect the people who participate in the surveys.
The researchers must first complete a CITI training on IRB website to be able to do the research. This will allow us use IRBWISE website to create research program using protocols. We can be added to any existing protocols. There we'll have to provide all the details of the study we're conducting. We also have to get the consent form signed according to the Belmont report. Once this is submitted, it'll take 3 weeks to approve it.


### Direct manipulation (Ed 2.3)

Users must be able to directly manipulate everything on screen so it can be the most intuitive. 
Command line used to be the way to control files in a computer and then it was changed to a mouse to control files directly using the mouse. This was then changed to touch screens which is the most intuitive for novice users.

According to Norman and Hutchins:
Distance is the distance between the goals and the system itself.

![[Pasted image 20240903142332.png]]

There are two types of distances: semantic distance is the distance between the users goals and their expression in the system. Articulatory distance is the distance between the expression of the goals and its execution, meaning how hard it is to do things that he has in his mind.

![[Pasted image 20240903211140.png]]

Whenever we're interacting with a computer interface,s we create a goal then an intention and then execute them. Then something happens in the computer and then user perceives and interprets it and evaluate it to see if the task was completed or not. If it is not the task repeats.

**Direct engagement** is a part of direct manipulation which promotes interfaces that represent human interaction with physical objects, not just with programs.
An example of this is the action of drag and dropping files into a folder in a computer which mimics the same action in real life

Direct manipulation is not always about creating interfaces that feel like real activity but also about creating interfaces that gives us a feel of a real activity.
An example of this is the gestures on a laptop with different animations that gives us a feeling that things are moving according to our actions on our trackpad like swiping from the right to open up the notification bar.

#### Invisible interfaces

The interface sits between the user and the task. Direct manipulation helps to reduce the gulf of execution and helps get the user closer to the task which makes the interface invisible.

Tips for creating invisible interfaces:
1. Use affordances: places were visual design of the interface is just how its supposed to be used. buttons for pressing, dials for turning.
2. Know your user: Novice or expert
3. Differentiate your user: More detailed for novices, more efficiency for experts.
4. Let your interface teach: eg: Shortcut tutorials in the GUI
5. Talk to your user: get feedback

#### Human abilities (Ed 2.4)

Understanding humans is an important part of HCI. It also includes human psychology as well.
Humans can perceived the world through visual, auditory and haptic senses.

Humans have 3 different memory store:
1. Perceptual store
2. Short term memory
3. Long term memory

Perceptual store or working memory is the shortest memory where the images and audio that you see and hear stay in your memory less than a seconds. It has three parts: visuospatial sketchpad for storing images, phonological loop for audio and episodic buffer for any kind of ordering. All of them are controlled by a central executive.

Short term memory can chunk four to five chunks at a time. Chunks are bits of information combined to one chunk to remember. So we cannot make users store too much in the short term memory at a time. It is also better to do recognition than recall while trying to make user recall something.

Its difficult to load things into long term memory as it requires us to load it to short term memory multiple times.

#### Cognition

Cognition is an important function of humans. There are two types of learning that we usually do. The procedural learning we automatically learn to do like using hotkeys and declarative knowledge where we intentionally learn something like conversing. 
Human brain has a limited amount of cognitive load. If we overload it with something we might not have much left for more important tasks. We have to keep this in mind while designing interfaces. The interface should not take too much cognitive load so the task itself won't have enough load left. User will also have the overall context in his mind as well.

![[Pasted image 20240904093833.png]]

Tips to reduce cognitive load:
1. Use multiple modalities: Visual, audio, haptic etc.
2. Let the modalities complement each other: Different modalities should support and illustrate each other instead of competing
3. Give the user control of the pace: No timers to induce pressure. Let user control pace.
4. Emphasize essential content and minimize clutter: Let user have the most important actions while still giving the full range of actions.
5. Offload tasks: If there is anything users have to remember from previous page, show them that in the interface. If there is anything users have to do manually, see if it can be done automatically.

Human motor skills are also important and have to be considered for different contexts. People might not be able to click on small buttons in contexts like walking or running.
