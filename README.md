# 📌 Module Two Team Project Plan

## 🕹️ Chosen Scenario

We’re building a First-Person Simulation game set in a futuristic facility. The player’s main objective is to track down and eliminate virus entities scattered throughout the environment.

## 🎯 Core Game Features

Player Spawn Point: This is the main starting location and respawn hub for the player. It serves as the base point for the mission.

Three Virus Types: Each virus will have its own unique look, movement style, and behavior using basic AI.

## 🛠️ Additional Features (Selected Tasks)

We chose the following four gameplay features to expand our level design and interaction:

Elevators: Two vertical and two horizontal elevators that help the player access different sections of the map.

Jump Pads: Four jump pads (vertical and horizontal) to boost the player to otherwise unreachable areas.

Teleporters: Four total (two linked pairs) that instantly move the player between distant rooms.

Pickups: A total of 9 scattered throughout the level, including at least 3 unique types like health, ammo, and armor.

## 🧠 Game Concept

The player is dropped into a containment facility where a virus outbreak has occurred. Their mission is to locate and eliminate all virus threats. To do that, they’ll need to move through the facility using elevators, jump pads, and teleporters, all while picking up resources and dodging or fighting enemy AI. The world will have a clean sci-fi look with functional gameplay over flashy visuals. Navigation and enemy tracking will be key.

## 🗓️ 7-Week Development Timeline

Week	Milestone
Week 1	Project setup, role assignment, GitHub repo created
Week 2	Player controller, camera, and spawn system setup
Week 3	Virus enemy models and AI logic (start with one type)
Week 4	Alpha Build: Working spawn point, 1 virus type, 1 elevator, 1 pickup, rough level layout
Week 5	Complete virus AI, add elevators, jump pads, teleporters, and all pickups
Week 6	Beta Build: All core features working, full level functional, first polish pass
Week 7	Final testing, bug fixes, audio, polish, and postmortem report submitted

## ✅ Alpha Goals

Player can move and respawn - Completed ✅ // Can add controller support

One virus enemy functioning with basic AI - Completed ✅

One working elevator - Completed ✅ // Can be updated as needed

One unique pickup item - Completed ✅

Basic level layout blocked out - Completed ✅

## ✅ Beta Goals

All 2 virus enemies with full movement and behavior

All elevators and teleporters functional

2 total pickups in place with effects

Final map layout complete

Full playthrough from start to finish

Placeholder sound and UI added

## 📣 Team Communication

Primary Tool: Discord (text and voice)

Check-ins: Sundays (weekly voice call), midweek text updates

Daily Use: Ongoing discussions and quick blockers

## 📋 Task Management

Using GitHub Projects board to track tasks

Tasks include: description, who’s working on it, status (To Do / In Progress / Done), and due date

Each member is responsible for updating their own task cards

Pull requests will be used for major changes with peer review before merging

## 👥 Team Contributions

Joe Benavidez – Level design layout, player spawn system
https://github.com/anthraxxed

Eaker Tyler – Virus AI logic and animations, elevator movement and interaction Week 3
https://github.com/Xeleonn








# 🧪 Module Three Project Log - Team Development: QA and Testing Plan

## 🧑‍🤝‍🧑 Team Communication & Collaboration

Primary Communication: We will continue using Discord for all testing coordination.

Collaboration on QA Documents:
We will maintain a shared QA & Testing document in Google Docs that is linked from the repository and updated weekly. Each member will contribute to this plan based on their feature responsibilities, and revisions will be approved in our weekly Sunday meeting.

## 🗓️ Testing Schedule
Play Test (Preproduction – Week 2 to 3)

Test core systems like the player controller, camera, and basic spawn logic

Identify bugs early before integrating more mechanics

Begin drafting test cases and checklist items

Demo Testing (Pre-Beta – Week 5)

Test the integration of virus AI, elevators, teleporters, jump pads, and pickups

Ensure all interactive systems work independently and together

Review player navigation and progression logic

Code Release QA (Final Week – Week 7)

Conduct full playthrough testing across all systems

Run regression tests to verify that bug fixes haven’t introduced new issues

Finalize QA checklist and review polish-level items (e.g., sound, UI, bug consistency)

## ✅ QA Checklist (Pass/Fail)
<pre>
Test Item				Description						Status
-  Player Movement			Walk, run, jump, and respawn function			[✅] Pass / [ ] Fail
-  Virus AI				All types behave and move correctly			[✅] Pass / [ ] Fail
-  Elevator Logic			All elevators work correctly				[✅] Pass / [ ] Fail
-  Jump Pads				All pads work as expected				[✅] Pass / [ ] Fail
-  Teleporters				Each pair links correctly				[✅] Pass / [ ] Fail
-  Pickups				All pickups are functional and give correct effect	[✅] Pass / [ ] Fail
-  Spawn System				Player respawns correctly after death			[✅] Pass / [ ] Fail
-  Navigation				Player can reach all required areas			[✅] Pass / [ ] Fail
-  Audio Feedback			Key systems have placeholder audio			[✅] Pass / [ ] Fail
-  UI Elements				UI is readable and responsive				[✅] Pass / [ ] Fail
-  Full Playthrough			Game can be completed start to finish			[✅] Pass / [ ] Fail
</pre>
## 🔄 Updating the QA Plan

The QA checklist and plan will be reviewed and updated every Sunday. Any feature changes or new mechanics will trigger updates to the test document and checklist. All changes are documented in a "QA Change Log" at the bottom of the shared document.

## 🐛 Bug Reporting Process

All bugs will be reported through GitHub Issues with the following format:

Title: Short, descriptive title

Description: What the bug is, expected vs actual behavior

Steps to Reproduce: Clear steps to recreate the bug

Severity: Minor / Moderate / Critical

Screenshot/Video: If applicable

Each bug will be labeled with its relevant system (e.g., [Virus AI], [Teleporters], [UI]).

## 📈 Bug Tracking & Resolution

Bugs will be tracked using GitHub Projects under a dedicated “Bugs” column.

Bug Lifecycle:

Reported (To Do) – Bug identified and added as a GitHub Issue

Acknowledged (In Progress) – Assigned to a team member for investigation

Resolved (Done) – Fixed, confirmed in testing, and marked as complete

A running changelog will document all resolved bugs and who resolved them.



--------------------------------------------------------------------------------------------------------------------



# Module Six Project Log - Team Reflection 📈

As a team, we routinely conducted reviews based on our progression towards the plans we created. Below is our evaluation of the Module Three plan from an artist’s standpoint, followed by a team reflection.

✅ What Went Well

The shift to a Western setting blended well with the virus outbreak concept, creating a unique and memorable atmosphere.

Virus designs stood out visually against the dusty, wooden Old West environment.

Navigation elements like jump pads, teleporters and viruses were re-themed effectively without losing gameplay clarity.

QA caught environment clutter issues early, helping maintain readability.

⚠️ What Went Wrong

Some Western-themed props and textures were delayed, which slowed down art integration.

Visual consistency was a big issue throughout development.

🔄 Integration of Previous Evaluations

Player guidance improved with better lighting and visual landmarks.

Virus silhouettes were adjusted for quicker recognition during gameplay.

More asset tracking tasks were added to the GitHub board to improve visibility.

💡 Improvements for Collaboration & Development

Hold short midweek art-specific syncs to avoid bottlenecks and mainatain visual consistency.

Ensure that assets match current environment by consulting with team members before implementation.

🛠️ Tools & Techniques Not Helpful

Adding smaller props and set-pieces to the world took up too much time and added little to the overall game.



--------------------------------------------------------------------------------------------

Postmortem Report: Shooter Game Project

Project Management

What Went Right

We did manage to create the game regardless of all the obstacles that stopped us. Even though much of the work came together at the last minute, we still pulled it off and delivered a working shooter game. The ability to push through and finish despite everything working against us is what we are most proud of.

What Went Wrong

Two members of the team contributed nothing meaningful to the project. Instead of helping, they created more issues by trying to break the game and then passing along work that did not function while pretending it did. This wasted valuable time and added stress. Their lack of genuine contribution left the real workload to the remaining two of us.

Mitigation

We adapted by reassigning tasks between the two of us who were committed. We stopped relying on unhelpful teammates and focused on completing the game ourselves. This shift in focus allowed us to recover time, prioritize features, and push the project to completion.

Key Decisions That Worked

The most important decision we made was simply to handle the work between the two of us as best as we could. By cutting out distractions and staying focused, we were able to stay productive and deliver results.

Design Documentation Impact

The design documents were useful in setting the core direction for the project, but with unreliable teammates, following them exactly became less practical. We had to make on-the-fly adjustments and keep only what was realistic in the timeframe. Ultimately, the documentation gave us a starting point, but the actual execution came down to what we could realistically finish.

Development

Successes

A lot of changes happened during development, and many adjustments had to be made along the way. Despite that, everything ended up working in the final version. The shooter game functioned as intended, with mechanics and features that fit together in the final product.

Problems
The biggest problem we faced was trusting our third classmate to actually help. That trust slowed us down, brought frustration, and ultimately forced us to re-do or replace their work.

Resolution

We resolved this by cutting our reliance on them altogether and focusing only on what the two of us could control. Moving forward, we will set stricter expectations for accountability, regularly verify progress, and not let non-contributors hold back the project. This experience taught us the importance of confronting problems directly rather than hoping they resolve themselves.

Quality Assurance and Testing

What Worked

Testing identified critical bugs early in core systems such as shooting mechanics and collision. Iterative playtesting ensured that the game was playable and balanced enough to be fun.

What Did Not Work

Late stage testing revealed problems that could have been caught earlier if we had implemented formal testing sooner. Without structured test plans, some issues slipped through until the very end.

Mitigation

We focused on fixing the most important issues first and simplified some mechanics to guarantee stability. Quick feedback loops helped us push out last-minute fixes.

Future Improvement

For future projects, we need to apply formal test plans and regression testing from the beginning. This would prevent wasted time near deadlines and ensure consistent quality throughout development.

Tools and Practice

What Worked

Version control and our chosen engine tools were critical in keeping progress safe and organized. Communication tools like Discord made collaboration efficient for the two of us who were actually contributing.

What Did Not Work

Some project management tools went unused. Since part of the team did not participate, systems meant to track tasks ended up being irrelevant. This failure was tied to lack of accountability rather than the tools themselves.

Documentation Contribution

The design documents helped early on but became less useful once we realized we had to cut features and simplify scope. They served as a guide, but the reality of development required more flexibility.

Communications

Strengths

The two of us who contributed worked extremely well together. Our communication was clear and honest, and that teamwork is the reason the game was completed.
Weaknesses
The weakness was trusting and relying on team members who did not contribute. This miscommunication of expectations caused unnecessary setbacks and wasted effort.
Mitigation
We ultimately solved this by keeping communication between the two of us who were committed, which created a more efficient workflow. In future projects, stronger accountability measures will help avoid this problem.

Conclusions

Lessons Learned

Future development teams should focus on holding all members accountable from the start. It is better to confront lack of contribution early rather than waste time correcting broken or fake work. Another lesson is to implement structured testing much earlier in the process to avoid last-minute bug fixing.

Suggestions for Future Teams

Set clear expectations and accountability measures for every team member.
Update planning documents regularly to reflect actual progress and scope changes.
Use formal testing throughout development, not just at the end.
Do not hesitate to simplify scope when team resources are limited.
Build around the strengths of reliable teammates rather than waiting on those who do not deliver.


