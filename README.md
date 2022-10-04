# IMGD 5100–Tangible and Embodied Interaction 

- **Instructor:** [Charlie Roberts](http://charlie-roberts.com)
- **Office:** Kaven 203 (in IMGD suite), but, not so much at the moment...
- **Email:** <cdroberts@wpi.edu>
- **Office Hours:** Thursday, 2–4 PM. Try to make it to my listed office hours _first_. If you have a conflict with that time, direct message me on Discord with a few alternative times that work for you, preferably in the afternoon. Appointments are generally for discussing course progress; for technical questions / assignment questions please use the public Discord server so that everyone can benefit from the discussion. Finally, I am always excited to take appointments with students interested in doing research / projects with me (independent study, thesis advising/reading, etc.); log on and say hi! 
- **[Course Discord server](https://discord.gg/2htm8uZ4)**

## Course Description
IMGD 5100 will discuss interaction through the lens of *Tangible, Embedded, and Embodied Interaction* (often shortened to TEI), considering issues of embodiment in virtual environments, alternative physical interfaces, and human-computer interaction in the digital arts, games, and crafts. Assignments in the class will reach across a variety of different mediums to explore user interaction: text-only, audio-only, and integrated multimodal approaches. Additonal goals include studying fundamental human-computer interaction principles, practicing critique, and exposure to a variety of technologies for interaction and user experience design.

The course will supplemented with guest lectures from both within and outside the WPI community, including experts in haptics, novel human-computer interaction in dance, tangible programming languages, immersive audio, and experience design for embodied installations. 

## Keep up with course announcements and participate on the Discord
Make sure you join the Discord server (see link at top of syllabus). Important announcements will be made via Discord, so make sure you're logging on regularly. This is also the best place to ask questions... and hopefully answer when you have some expertise to share. Please stay on top of course communications.

## Materials
This course will provide time for students to explore physical computing / microcontroller programming, using a [kit you must purchase](https://www.amazon.com/ELEGOO-Project-Tutorial-Controller-Projects/dp/B01D8KOZF4/ref=sr_1_4?keywords=arduino+starter+kit&qid=1661534683&sprefix=Arduino+star%2Caps%2C71&sr=8-4).

## Grades
50% [Weekly readings / design sprints](https://github.com/charlieroberts/IMGD-5100-2022.github.io/blob/main/README.md#course-outline-subject-to-change)  
50% Project(s)

Late work is accepted for design/development assignments, however, turning in such assignments late will often mean you miss out on chances for in-class critique. *Please do your best to complete the weekly readings*, as class discussion will be both confusing and potentially boring without doing so.

## Attendance
Don't miss class if at all possible! Class will provide critique sessions, a variety of guest lectures, and other opportunities that can't easily be replicated.

## Final Project
The final project is open-ended; you are encouraged to follow your personal interests to create a project that explores tangible and/or embodied interaction. This could include:

- A game that you make with an accompanying alternative control device
- An embodied interface for making visual art, crafts, or music
- An immersive experience that explores haptics
- A VR / AR experience
- A more focused HCI experiment where you design / test an interface for research purposes

You are required to do some type of user evaluation of your work. Time in class will be provided for this, but obviously not all interfaces work well with remote testing. Give this some thought and be preapred to justify your chosen evaluation.

Here is a timeline of deliverables for the project (dates TBD):

1. A short paper (less than a page) describing what your project will be, what challenges / difficulties you expect to encounter when building it, and how you will evaluate it. Note there is no class this day (Patriots Day)

2. Prototype I. You will casually show/discuss your prototype with 1–2 other members of the class + the instructor on this day. Be prepared to either show pre-recorded video or do live demonstrations of your work.

3. Check-in. Send a brief (< one page) summary of your progress to date to the instructor. You should now be at a point where you're ready to begin evaluating your work more seriously, and there will be class time allocated for this.

4. Final project presentations.

5. Final projects are due (no class today, as WPI will be on a Friday schedule). Please create a small website that contains documentation of your project, including a brief description of the concept, a video of it in action, and a description of your evaluation and its results.

## Course Outline (subject to change)
For all readings, please prepare a paragraph or two (>200 words) describing points of interest you found in the article, questions you might have, and topics for discussion in class. Please submit this by 10AM the morning they are due, this will hopefully give me time to scan them before class.

### Week 1: what is 'tangible' , what is 'embodied' and what is TEI? 
Readings (due Aug. 30th by class time):
- [Human–computer interaction, foundations and new paradigms](https://www.alandix.com/academic/papers/JVLC-2016-HCI-FNP/JVLC-special-2016-draft.pdf) by Alan Dix  
- [Direct Manipulation:
A Step Beyond Programming Languages](https://www.cs.umd.edu/users/ben/papers/Shneiderman1983Direct.pdf) by Ben Shneiderman  
- [Getting a Grip on Tangible Interaction: A Framework on Physical Space and Social Interaction](http://www.ehornecker.de/Papers/FrameworkCHI.pdf) by Eva Hornecker and Jacob Buur  
- [Tangible Bits: Beyond Pixels](https://dl.acm.org/doi/pdf/10.1145/1347390.1347392) by Hiroshi Ishii  

### Week 2: Embodied text(?) and the keyboard / mouse as input devices
#### Design Sprint (choose one, due Sept 6th.)
*Live Coding*

Experiment with one or more of the environments below:
- [Hydra (2D visuals)](https://hydra.ojack.xyz)
- [Livecodelab (3D visuals + a bit of music](https://livecodelab.net/)
- [Marching.js (ray-marched visuals)](https://charlieroberts.github.io/marching/playground/)
- [Gibber (music + 3D visuals)](https://gibber.cc/alpha/playground)
- [Barbara (2D visuals + programming language creation)](https://www.barbara.graphics/)

Create a short (2–3 minute) performance using one of these systems (consider syncing to music if you’re doing a graphics performance). You will be asked to conduct peer critiques of this assignment in groups next week. As you use these systems, consider how the “embodiedness” of the environment (or lack thereof) is contributing to your work. Do you find yourself wanting tangible controls? Do the keys become tangible? The mouse?

Write a short response (minimum 250 words) addressing these questions and other aspects of the environment you found interesting or problematic. 

Include a link to a video of your performance at the top of your design sprint, and please share the recording in the class Discord channel. 

*Interactive Fiction*

For this assignment, you will create a work of “interactive fiction”. This can be a game, a story, or you can take artistic license with the assignment to do something more creative with text and interaction. The only limitation is that text, and text alone, is the sole medium you may use to present your project.

There are a few different tools for creating interactive fiction. The most popular of these is  [Twine](http://twinery.org/) , which primarily relies on hypertext links for interaction. However, you can also have variables, conditionals, and other programmatic constructs to make interaction more complex than you might expect from a hyperlink based system.

There are also tools where natural language parsing (asking users to enter text at a prompt) is used instead of pointing and clicking. Two of the most popular of these are   [TADS](http://www.tads.org/) 
and   [Inform](http://inform7.com/) . 

[Here’s a comprehensive comparison of a number of different IF systems by Emily Short](https://emshort.blog/how-to-play/writing-if/)

The experience you create should be designed to be completed in about 15 minutes; we will be critiquing them in class next week. In addition to creating the assignment you will also need to provide a written summary of what you did (minimum 250 words). This summary should briefly describe what you created, what your inspiration was, and what tool you chose to author your work. Please also consider whether or not you think the work creates sense of immersion and whether or not you feel the work is embodied in any way.

Submit your writing via Discord and be sure to include a link to your project! The Emily Short article linked above has useful suggestions for how to distribute your work.

#### Readings (due Sept. 2nd)
Please submit a summary to me through Discord per the instructions at the top of the Course Summary.
- [Embodiment of Code - Marije Baalman](https://zenodo.org/record/18748#.YBepti9h124)
- [Radical Clashes: What Tangible Interaction Is Made Of - Dijk1 et al](https://dl.acm.org/doi/pdf/10.1145/2460625.2460680?casa_token=nkmEsDhG44IAAAAA:sYqyBsnk4_tssXNF-5-SyyIpUbZZiJlu_L_7AuIiUahK_0TCU6vJKLCWjmrO_rNlHZ_yNvUk9-mw)
- [What is Embodied Programming - Alex McLean](https://slab.org/what-is-embodied-programming/)
- [The Pleasure Principle: Immersion, Engagement, and Flow - Douglas / Hargadon](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1038.2644&rep=rep1&type=pdf)

### Week 3/4: Physical Computing / Sensing

#### Mini-homework 
Choose one sensor / output module declare it “yours” in the class Discord. This should not be a module discussed in class. Be prepared to give a short tutorial on using the sensor / output in class on Thursday, and have sample Arduino code / circuit photos to share with the class. You don’t need to integrate the sensor into a larger project (just getting it to interface with the Arduino is fine) but feel free to have fun with this if you want to get creative!

#### Readings (due September 20th)
Please submit a summary to me through Discord per the instructions at the top of the Course Summary.

- Norman (do a quick refresh/scan before reading Iskander): [Design Thinking](https://cs3041-18b.github.io/docs/reading/DesignThinking_DonNorman.pdf)
- Iskander: [Design thinking is fundamentally conservative and preserves the status quo](https://hbr.org/2018/09/design-thinking-is-fundamentally-conservative-and-preserves-the-status-quo)
- Barragán & Reas (ported by Abhik Pai): [Extension 5](https://p5.readthedocs.io/en/latest/tutorials/electronics.html)
- Bilkstein: [Gears of our Childhood: Constructionist toolkits, robotics, and physical computing, past and future](https://www.researchgate.net/publication/262201733_Gears_of_our_Childhood_Constructionist_toolkits_robotics_and_physical_computing_past_and_future)

#### Design Sprint (due Sept. 27th)
For this assignment we will experiment with connecting sensors to Arduino, and using them to trigger events in a game engine / creative coding platform of your choice. Ideally, you will create an interactive experience that *would not be possible to create* using your laptop alone.

Ideas for this design sprint include:
- A small interface (perhaps three buttons + a potentiometer)  that replicates the experience of using a more traditional GUI, but in the physical world. This GUI should be connected to a desktop/laptop app. What does having dedicated physical controls add to the experience?
- A simple game interface + game that combines using the joystick with an additional sensor (photocell, ultrasound, and tilt switch seem like promising  ideas).
- Go completely embedded and make a small interactive experience using the 16x2 LCD display connected to one or more additional sensors. Perhaps a simple text based game with physical inputs?  Can you figure out how to make a more arcade style game with the constraints of 16x2? Note that the circuitry for the LCD display, while not complex, does require nine separate connections to the Arduino.

Document whatever you create and upload it to a freely accessible site for critique. Write a 250-word (minimum) summary of your experience. How hard was it to incorporate the Arduino sensors / interface elements? What affordances did you explore?  Make sure to include a link to your documentation video at the top of your writing, and be prepared to conduct critique sessions on your design in class. 

Unity + Arduino:  
[Ardity](https://assetstore.unity.com/packages/tools/integration/ardity-arduino-unity-communication-made-easy-123819) - you can install this directly from the asset store.  

Unreal Engine + Arduino:   
• Arduino Kit (cross-platform) : https://forums.unrealengine.com/community/community-content-tools-and-tutorials/91168-free-arduinokit-cross-platform-arduino-plugin-for-ue4/page4  
• UEDuino (Windows only) : https://github.com/RVillani/UE4Duino

### Week 6: Mobile Devices

#### Readings (due October 4th)
- Mads Soegaard: [Glossary of Human-Computer Interaction: Affordances](https://www.interaction-design.org/literature/book/the-glossary-of-human-computer-interaction/affordances)
- Gurevich et al.: [Style and Constraint in Electronic Musical Instruments](https://www.researchgate.net/profile/Adnan_Marquez-Borbon/publication/228754343_Style_and_constraint_in_electronic_musical_instruments/links/02e7e522ffe1e37eae000000.pdf)
- Atau Tanaka: [Mapping Out Instruments, Affordances, and Mobiles](http://research.gold.ac.uk/id/eprint/6834/1/P88_Tanaka.pdf)
- Donald Norman: [Affordance, Convention, and Design](https://dl.acm.org/doi/pdf/10.1145/301153.301168)

#### Design Sprint 
For this assignment we will experiment with using our phones as controllers for games, music, or other creative experiences. Regardless of which you choose, you will need to:
1. Create an interface on your mobile device. One option for doing this is to use an application like TouchOSC (iOS or Android, $5) or mrmr (iOS, free) or oscHook (Android, free).  At minimum, your interface should use the accelerometer in some meaningful way. At best, experiment with a variety of sensors and/or touch controls. Alternatively, you can use a web interface via [Interface.js](https://github.com/charlieroberts/interface.js) or some other related library (nexus-osc etc.)
2. Create  your game, musical instrument, or artistic experiment (or some combination of all three!) Make whatever you create accept messages over OSC so that it can communicate with your mobile device.  This can be in the platform of your choice… Unity, Web, Unreal, etc. although we’ll be covering Unity and Unreal specifically in class. Document whatever you  create in a video and upload it to a freely accessible site.
3. Write a 250-word (minimum) summary of your experience. How hard was it to incorporate the mobile sensors? Were you able to use the sensors in a way that helped create a different experience from what you might have made with mouse / keyboard? Would you use mobile devices as game controllers for external games / interactive experiencecs again? Do you think the user experience is more embodied than a mouse + keyboard combo? Make sure to include a link to your documentation video at the top of your writing, and be prepared to conduct critique sessions on your design next class. 

### Week 7: A Plurality of Realities: VR / AR / MR

#### Readings
Please submit a summary to me through Discord per the instructions at the top of the Course Summary.

- Smith: [Generative Design for Textiles: Opportunities and Challenges for Entertainment AI]( https://aaai.org/ocs/index.php/AIIDE/AIIDE17/paper/download/15820/15174)
- Carlons et al.: [Designing eBee: A Reflection on Quilt-Based Game Design](http://sokath.com/home/wp-content/uploads/2018/01/carlsson-fdg17.pdf)
- Eric Gunther1and Sile O’Modhrain: [Cutaneous Grooves: Composing for the Sense of Touch](https://www.researchgate.net/publication/221164911_Cutaneous_Grooves_Composing_for_the_Sense_of_Touch)

#### Readings
- Linett: [Review-House of Eternal Return, Meow Wolf Art Center, Santa Fe](https://sloverlinett.com/wp-content/uploads/2019/03/Meow-Wolf-review-PLinett-in-Curator-Journal.pdf) *no review required for this reading*

### Week 8: Game interfaces and alternative controllers

#### Design Sprint
For this spring, you can choose to make *either* an AR or a VR project (don't do both unless your super motivated). AR will require the use of your phone (or potentially a hololens if you have access to one), VR will require the use of a platform like Google Cardboard, or access to more specialized hardware if you have it.

Projects can be realized in any platform you choose, but I encourage using [AFrame](https://github.com/IMGD-5100-2021/IMGD-5100-2021.github.io/blob/main/arvr_desgn_sprint.md) or Unity. We will use class time to critique this sprint, so be prepared to work with other students / the instructor to make your project accessible to people. Note that specialized hardware won't be avaiable for these critiques, so be sure to think about documentation if you're using a device like the Vive / Hololens etc.

*VR*: In this design sprint, we will be **exploring virtual reality to consider what it will be like when computation can transport us to another place.** Transport someone to a real location, inside a game, among abstract art... whatever you think would be interesting, immersive, and compelling. You may work in teams for this assignment.

A couple of quick pointers before you start:
- **Be sure to articulate your design goal / objective ASAP.** Without an objective for your design, much of your process will be unguided. If your goal is to provide a sense of awe or provoke reflection or make someone feel like they are truly in another physical place... any of that is fine. The key is that you articulate your goal and make design decisions that align with that objective.
- **Consider what will make your design feel immersive.** This is your primary challenge, and it's worth thinking beyond visual channels. How could audio enhance your design? Should you add other forms of interaction besides keyboard / cardboard button / mouse?
- **Careful with interaction.** Because of time and hardware limitations, consider what input mechanisms you may even have available to you before getting too deep into the development.

*AR*: In this design sprint, you will make arbitrary user-occupied spaces *creepy*. This can be interpreted as you see fit. 
- What types of virtual objects can you place in a space that create unease? Discomfort? 
- Can you use sound in some way to emphasize this effect? 
- What types of interaction might be *disturbing*? 
- How can users explore the worlds you augment?

### Deliverables
- A short demo video, hosted online. Documentation of your assignment, including a brief description of what you made, how it was received during critique, and what you would change if you continued to work on it. Include the link to your video in your documentation, which should be a .pdf.
- Your AR/VR experience should be publicly accessible so that others can visit it or download it. **Include this link in your design doc.** If you're using AFrame, it's fine if this is a link from [glitch](https://glitch.com/) (which is probably the easiest place to develop your work).

### Week 9/10/11: Tangible Computing, Ubiquitous Computing

### Week 12: Audio, Interaction, and Immersion

### Week 13: Studio, user testing, miscellaneous topics as needed

### Week 14: Final presentations + critique

## Special Accommodations
If you need course adaptations or accommodations because of a disability, or if you have medical information to share with me that may impact your performance or participation in this course, please make an appointment with me as soon as possible. If you have approved accommodations, please request your accommodation letters online through the Office of Disability Services student portal. If you have not already done so, students with disabilities who need to utilize accommodations in this class are encouraged to contact the Office of Disability Services (ODS) as soon as possible to ensure that such accommodations are implemented in a timely fashion. This office can be contacted via email: <DisabilityServices@wpi.edu>, via phone: (508) 831-4908, or in person: Daniels Hall 124.
