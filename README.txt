Software Engineering Lab Repository

This repository contains the coursework and project artifacts completed for the Software Engineering subject.

Project Overview
The work in this repository is based on Problem Statement #14: Corporate Mental Wellness & Counseling Platform.
The goal of the project is to design a digital platform that helps organizations support employee mental wellness, ensure confidential counseling access, and streamline support services for employees in need.

Repository Structure
- Lab 1/
  - Requirements specification and use-case modeling documents
  - UML use-case diagram and related artifacts
- Lab 2/
  - Jira-based project planning and task tracking materials
- Lab 3/
  - System design, component modeling, and justification files
- Lab 4/
  - Scenario 14 terminal 2048 game and Lab 4 materials

Lab 1 Deliverables
1. 01_Requirements_Table.docx
   - Includes 5 functional requirements and 2 non-functional requirements
   - Covers actors, use cases, relationships, and traceability
2. 02_Use_Case_Flow.docx
   - Contains the main flow for UC-02: Book Confidential Counseling Session
3. 02_Use_Case_Flow.pdf
   - PDF version of the use-case flow
4. 03_UML_Use_Case_Diagram.pdf
   - UML use-case diagram showing both actors, all 7 use cases, include/extend relationships, and legend
5. 04_UML_Use_Case_Diagram.drawio
   - Editable diagrams.net source for the UML diagram
6. Copy of 15_SE_Lab1_SE_Problem_Statements.pdf
   - Reference copy of the provided lab problem statement

Lab 2 Deliverables
- Lab2_Jira_Submission.pdf
  - Jira-based project tracking and task submission documentation
- Lab_2_Jira_Student_Handout_Problem_Statement.pdf
  - Problem statement handout for the Jira lab

Lab 3 Deliverables
- Lab3_Component_Diagram.pdf
  - Component diagram for the proposed system design
- Lab3_Justification.pdf
  - Design rationale and justification for the architecture
- Lab3_Component_Modeling.zip
  - Archive containing the component modeling work

Lab 4 Deliverables
- Lab4_Scenario14.zip
  - Scenario 14: terminal-based 2048 game with directional movement, tile merging, undo, score tracking, and game-over handling

Lab 4 — Scenario 14: 2048
The Lab 4 package implements a terminal version of 2048. The work addresses:
- Correct one-merge-per-tile behavior, including four-equal-tile and separated-pair cases
- Win detection at 2048, no-legal-moves detection, and tile creation only after a changed move
- One-level undo that restores both the board and score, plus best-score tracking for the current run
- Concise action-level feedback for successful moves, without reporting invalid or unchanged moves as successful
- Strict command handling for W/A/S/D movement, U undo, and Q quit

The implementation keeps game state in memory and adds no external dependencies or persistent storage.

Run the game from its project directory:
```
python main.py
```

Run the standard-library unit tests:
```
python -m unittest
```

The reported test suite contains 27 tests covering slides and merges, all movement directions, unchanged moves, win and no-move states, undo and score restoration, feedback, invalid commands, and quitting.

Lab 4 Submission Items
- A 10-second video showing the original behavior before the changes
- A 10-second video showing the fixed game and its new features
- A link to the LLM chat page with the complete chat history

Purpose
This repository serves as a structured record of software engineering lab work, including requirement analysis, use-case modeling, task planning, component-based design, and the Lab 4 2048 coding scenario.

Labs 1–3 focus on the Corporate Mental Wellness & Counseling Platform. Lab 4 contains the separate Scenario 14 terminal 2048 exercise.
