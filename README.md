# Yael Durahly

Fourth-year B.Sc. student in Software & Information Systems Engineering at Ben-Gurion
University, graduating in 2027. My work reaches across AI research, full-stack development,
and systems security.

My final-year project is a runtime security system for Linux build servers. During a build,
the server spawns hundreds of short-lived processes amid heavy file and network activity,
giving an attacker room to hide malicious behavior inside legitimate build steps. Using
eBPF, the system instruments each build as it runs, enriches every event with build-phase
and process-lineage context, then weighs that evidence through deterministic rules alongside
a behavior-based detector to decide its response: allow, alert, or stop the build.

Previously I was an AI Research Intern at IBM's Beer-Sheva Research Lab, where I evaluated
data-selection methods for fine-tuning language models with LoRA and compared online and
offline training strategies across three models. Earlier, I completed the Magshimim
national cyber program before serving in the IDF C4I Technological Unit, where I developed
internal software while managing network infrastructure for over 500 users.

## Technical Toolkit

**Languages:** Python, Java, JavaScript, C, C++, C#, SQL, Assembly, Bash

**Frameworks & libraries:** React, Node.js, Express, Socket.IO, Sequelize, FastAPI, LangChain

**Tools & platforms:** Git, Docker, MySQL, Postman, Linux

## Selected Projects

### [Nutrition Tracker](https://github.com/Yael-work/nutrition_tracker_app)

A full-stack meal and nutrition tracker built with React, Node.js, Express, MySQL and
Sequelize, with Socket.IO pushing live updates to the dashboard. Users log meals manually
or upload a photo, which an AI model turns into estimated food items and nutrition values
for the user to review before saving. I built the unified meals tab and calendar-based date
selection, hardened the AI response parsing so malformed JSON could not break the upload
flow, added the persistence and relationship test suite, and implemented the account and
password flows.

### [Clinical Decision Support — Lab Results](https://github.com/Yael-work/CDSS_Lab_results)

A deterministic, rule-based system (Python, FastAPI, React) that interprets laboratory
results, classifies them into risk categories, and explains the reasoning in plain language
— no AI at runtime, only transparent rules and documented thresholds. I built the
least-squares trend engine that tracks each marker over time, the critical-value escalation
for extreme results, the value-against-reference-range charts, and an on-device history
dashboard.

### [Java Maze Pathfinding](https://github.com/Yael-work/java-maze-pathfinding)

A Java system built in three stages: a maze generation and graph-search library (BFS, DFS
and Best-First Search behind clean abstract interfaces), then a thread-pooled client-server
application with run-length and DEFLATE compression for sending mazes over the network, and
finally a JavaFX desktop game on an MVVM architecture packaged with Maven. Covered by JUnit
tests on both the algorithms and the compression layer.

### [Networked Blackjack](https://github.com/Yael-work/CS_BlackyJacky)

A client-server blackjack game over a network (Python), with a threaded server and UDP
service discovery. My work focused on correctness under concurrency: I fixed a
synchronization bug that disconnected clients before a game finished, rewrote the client to
wait on events instead of busy-waiting, and added graceful shutdown on both sides. Built
with a partner.

## What I'm Looking For

I am looking for student and junior positions in frontend and backend software engineering,
applied machine learning, and systems security. I am also open to a broad range of roles,
such as product management.

Alongside my studies I have spent several years teaching and mentoring programming — from
high-school students in the Magshimim national cyber program to new immigrants pursuing STEM
degrees. I work in Hebrew, English and Russian.

## Contact

- [Email](mailto:yaeldur@post.bgu.ac.il)
- [LinkedIn](https://www.linkedin.com/in/yael-durahly-176050431/)
