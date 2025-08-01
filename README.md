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

One virus enemy functioning with basic AI

One working elevator - Completed ✅ // Can be updated as needed

One unique pickup item

Basic level layout blocked out

## ✅ Beta Goals

All 3 virus enemies with full movement and behavior

All elevators, jump pads, and teleporters functional

9 total pickups in place with effects

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

Joe Benavidez – Level design layout, player spawn system, jump pad mechanics Week 2
https://github.com/anthraxxed

Eaker Tyler – Virus AI logic and animations, elevator movement and interaction Week 3
https://github.com/Xeleonn

 UI elements, pickups and item integration, teleporters Week 4
https://github.com/Seantroup

Dean Brandon – Sound design, bug testing, and final game polish Week 5
https://github.com/BDean353








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
-  Player Movement			Walk, run, jump, and respawn function			[ ] Pass / [ ] Fail
-  Virus AI				All types behave and move correctly			[ ] Pass / [ ] Fail
-  Elevator Logic			All elevators work correctly				[ ] Pass / [ ] Fail
-  Jump Pads				All pads work as expected				[ ] Pass / [ ] Fail
-  Teleporters				Each pair links correctly				[ ] Pass / [ ] Fail
-  Pickups				All pickups are functional and give correct effect	[ ] Pass / [ ] Fail
-  Spawn System				Player respawns correctly after death			[ ] Pass / [ ] Fail
-  Navigation				Player can reach all required areas			[ ] Pass / [ ] Fail
-  Audio Feedback			Key systems have placeholder audio			[ ] Pass / [ ] Fail
-  UI Elements				UI is readable and responsive				[ ] Pass / [ ] Fail
-  Full Playthrough			Game can be completed start to finish			[ ] Pass / [ ] Fail
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
