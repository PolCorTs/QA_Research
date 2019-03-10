# QA WORKFLOW

I am <https://www.linkedin.com/in/pol-cortés-escañuela-800075180/>(Pol Cortés), student of the <https://www.citm.upc.edu/ing/estudis/graus-videojocs/>(Bachelor’s Degree in Video Games by UPC at CITM). This content is generated for the second year’s subject Project 2, under supervision of lecturer <https://es.linkedin.com/in/ricardpillosu>(Ricard Pillosu).

# INDEX

* [Introduction to QA](#introduction-to-qa)
    * [QA Process](#qa-process)
* [QA Workflow](#qa-workflow)
    * [Waterfall](#waterfall)
    * [Agile](#agile)
* [Testing](#testing)
    * [Bugs](#bugs)

# Introduction to QA

Quality Assurance (QA) is a way to ensure everything is going the right way. Many people confuse the concepts of QA and testing. However, QA is used to describe the broad surface testing done inside a publisher, while testing covers the entire spectrum of techniques used to find, investigate, and solve problems.

<p align="center">
  <img src="https://github.com/PolCorTs/QA_Research/blob/master/Docs/qa-process.png?raw=true" alt="Github branches">
</p>

QA is more than finding bugs in a “the more the better” mode. The QA team’s mission is to help web developers deliver the product of their work within the estimated timeline, detecting any issues that might block the success of operations or even affect the user experience.
## QA Process
### Step one: review requirements and documentation

This step is started with the documentation generation process. QA testers review the documentation to make sure it is: complete, not redundant, clear, consistent and executable.
Errors cost less when detected at an early stage, improved documentation means a higher quality project for lower labor input and more accurate estimates.

### Step two: plan and prepare tests

When the requirements have been established, it is time to start planning testing. Describe the actions QA people must perform to make sure the piece of software functions as planned. In this stem, testing sessions are scheduled and every documentation that will be used in testing needs to be finished.

### Step three: testing

The main goal of this stage is to check whether the solution is developed properly from the technical perspective and meets the initial product requirements. There are different testing types to execute depending on the stage of the development process(see the [Testing](#testing) part for more information).

### Step four: report and measure

When a tester discovers a bug, he/she records it in a bug tracking system that every team member can access to.
This simplifies communication inside the team and helps keep a clear overview of the improvement process.

### Step five: verifying fixes

When a developer fixes an issue he/she informs the QA responsible, who verifies it. The ticket in the bug tracking system is closed when no issue is detected. A common rule to follow at this stage is: "no bug can be marked as fixed until it is verified".

# QA Workflow

There are many ways to approach your QA organization. The most used workflow options are **Waterfall** and **Agile**. They are completely different and adapt to different working/planification styles. 
<p align="center">
  <img src="https://github.com/PolCorTs/QA_Research/blob/master/Docs/agile_vs_traditional.png?raw=true" alt="Github branches" >
</p>

## Waterfall

Waterfall is a sequential method. It's not iterative, meaning work is not performed in cycles, constantly improving on the original product. You finish a stage and move on with the next step with the results practically immovable. You go through each of the project processes (from initiation to planning, execution, controlling, all the way to completion). And ideally at the end, you can assemble all the finished deliverables into a completed project or product. In this method, decisions (regarding both design and development) are made strictly within each phase of the process. As an example, changing the designs once the development phase has begun takes considerable time and money. Waterfall is supposed to control the process so that all but the most critical changes are managed or altogether prevented.
In this type of working organization, QA is performed only after all the development process is done. This limits a lot the testing possibilities to change things after being tested.

<p align="center">
  <img src="https://github.com/PolCorTs/QA_Research/blob/master/Docs/waterfall.jpg?raw=true" alt="Github branches" >
</p>

## Agile

Agile is an iterative, team-based approach to development. This approach emphasizes the rapid delivery of an application in complete functional components. Rather than creating tasks and schedules, all time is “time-boxed” into phases called “sprints.” Each sprint has a defined duration (usually in weeks) with a running list of deliverables, planned at the start of the sprint. Deliverables are prioritized by business value as determined by the customer. If all planned work for the sprint cannot be completed, work is reprioritized and the information is used for future sprint planning.

<p align="center">
  <img src="https://github.com/PolCorTs/QA_Research/blob/master/Docs/scrum-qa.png?raw=true" alt="Github branches" >
</p>

With this method the customer has frequent opportunities to see the work being delivered, and to make decisions to change throughout the development. He/she gains a strong sense of ownership by working extensively and directly with the project team throughout the project.
If time to market for a specific application is a greater concern than releasing a full feature set at initial launch, Agile can more quickly produce a basic version of working software which can be built upon in successive iterations. In addition development is often more user-focused, likely a result of more and frequent direction from the customer.

QA can work in parallel with development, testing as soon as new source code is produced. Heavily based on automated testing, a grat method for large projects that allow testers to test automatically some parts thanks to software. Integrated with the development team so here is only one team. This method allows black box and white box testing, deep knowledge of internal workings of internal workings of the application.

<p align="center">
  <img src="https://github.com/PolCorTs/QA_Research/blob/master/Docs/white-black_boxes.png?raw=true" alt="Github branches" >
</p>

# Testing

**Testing & the Game Life Cycle**
It is very important to differenciate the different phases of the game to detect what actions must do the QA team. Those important phases of the game development for QA are:

- Concept/Design
- Production/prototype: it is essential that the prototype contains the shining gameplay mechanic/story hook that can make a game financially successful.
- Alpha: the alpha phase comprises a game’s first major milestone.
- Beta: the beta phase is perhaps the most important milestone, it is roughly the time when all assets are in place and the game is virtually finished. 
- Gold: when a game hits the gold phase, it’s ready for market. 

There are many different types of testing to do depending on what you are looking for:

- Smoke testing: it comes first. In it testers lightly check that the software functions as planned. When this stage is passed, deeper investigation begins. 
- Integration testing: used when adding something into the main loop. It certifies the functionality of the new added feature inside the overall game.
- Performance testing: used to check the system load and stress while executing the task. This fase is where irregularities in performance are detected.
- Cross-platform testing: checks the perfect functioning in every platform the game is going to be run.
- Regression testing: used to search for bugs in previously tested code. It is needed when adding new features or making any updates to an existing system. 
- Balance testing: it makes sure that gameplay is fair to both the human and AI player alike. This is so important that developers sometimes spend months balancing the gameplay!
- Playtesting:  to simply “work as intended” is not enough; game designers must tap into what is known as “the fun factor”.

## Bugs

In games, every element that does not enhance the game but detracts from it is a bug. Sometimes a bug is almost impossible to see—and sometimes it’s right in your face, taking up the entire screeen. . When you’re a game tester, it’s your job to locate all the bugs you can, replicate them(make them occur again) and write a report for the developer team. You also have secondary goals as a tester such as verifying that the bugs have been fixed or make sure the game is fun together with the designers.

There are a lot of bug classifications, one of them is their severity affecting the game:

- Low priority bugs: they often make no difference to the development team whether they are fixed or not. Examples of low bugs are
minor graphical glitches, a short sound distortion here and there, some small error in the user interface.
- Medium priority bugs:  they occur more often than low bugs—and they can almost always be counted on to happen. A low priority bug that happen more frequently may be classified as medium priority. Another example is a bug that
would annoy a player, but not affect gameplay. 
- High priority bugs: they must be fixed.High bugs seriously affect gameplay, they make everything stop in its tracks. A necessary door that needs to be opened to continue with the story not opening is a major bug. A 40 frame rate fall would also be one.
- Critical bugs: It demands immediate attention from the developers. Nobody goes home until the bug is fixed. Critical bugs cause crashes, freezes, and data corruption.

Another type of classification is depending on which area they affect:

- Visual: they affect a game’s graphics. Inside theese there are different types:
    
     - Clipping: it is when a polygon overlays or penetrates another polygon. 
     - Z-Fighting: Z coordinate corresponds to depth. If there’s a problem, textures in different depths might overlap and "fight". 
     - Screen Tearing: screen tearing occurs when the graphics processing unit can’t draw a frame fast enough.
     - Missing Textures: when you encounter missing textures, all you see is flat white or placeholders.
     - Visible Artifact: this is usually one of many little bits and pieces scattered on the screen that are not connected to anyone or anything.

- Audio: they affect a game’s audio. Inside theese there are different types:
     
     - Audio Drop: you might miss important dialogue, a telling gunshot sound effect, or a line in a song. 
     - Skipping: it usually follows a frame rate “hiccup”. This is a good indication it might be performance-related, not asset-related.
     - Missing Sound Effect: if a sound effect is missing, you will hear silence and that’s it. A missing sound effect is ultimately the responsibility of the programming and/or the audio team.
     - Volume Level: if you can’t change volume in the Options Screen, a sound effect that’s too faint or music that’s overbearing can be classified as a volume level bug.
     
- Level Design: when a level is badly constructed, you might end up with a hole in the ground or even an invisible wall. 

- Artificial Intelligence: when characters do something completely illogical such as staring at a wall for five minutes, you can bet there’s something wrong with the AI code.

- Physics: physics bugs include breakables and dynamic behavior.

- Stability: it refers to the predictability of the code. Examples of stability bugs include freezes, crashes, and loading bugs.

- Performance: it refers to the speed with which the hardware processes the code. Those include frame rate, load time, minimum requirements machine, and installation time bugs.

- Networking: they are bugs specifically related to server-client connectivity and bandwidth issues. 

### Bug reports

Bug reports are text documents that describe to developers how a bug can be exactly reproduced. The more detailed a bug report is, the easier it is for the developer to fix it. The elements that a bug report must contain are:

- Title: bug titles need to be absolutely clear and to the point, when writting them try to follow the 6W rule (who, what, when,
where, and why).

- Description: The description provides more context and detail on the bug.

-Steps: they work as instructions explaining to the developer exactly what to do in order to replicate the bug.

- Version:  The version associated with your report is one such essential component.

- Repeatability: it refers to how often a bug occurs. 

- Verification: once your bug report is done, it goes back to the developer for a fix. When it is "fixed" you must review it again to verify it is correct.
