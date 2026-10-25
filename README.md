# Yael Durahly

Fourth-year Software & Information Systems Engineering student at Ben-Gurion University,
graduating in 2027. I work across full-stack development, machine learning, and systems
security.

Right now I'm building my final project: a security system for Linux build servers that
spots attacks hiding inside normal build activity. It uses eBPF to watch each build as it
runs, then decides whether to allow, alert, or stop it.

Before this I was an AI Research Intern at IBM's Beer-Sheva Research Lab, working on data
selection for fine-tuning language models. Earlier I came up through the Magshimim national
cyber program and served in the IDF C4I Technological Unit, writing software and managing
the network for 500+ users.

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
