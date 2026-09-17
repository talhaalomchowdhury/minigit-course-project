# Homework 2 — Part 2 Submission

Student name: Talha Alom Chowdhury

GitHub username: talhaalomchowdhury

## 1. Git Command Observations

| Command or workflow | What did you observe? | What was the user trying to accomplish? | What problem or risk did it address? |
|---|---|---|---|
| 1. git status | showed changes, file state, branch state | check repo state before commit| avoid to commit wrong or new changes |
| 2. git diff | showed line by line changes like add or delete | inspect changes before staging and commiting | inspect unwanted edit, mistakes |
| 3. git add | stage files on local |preparing files for the next step|
| 4. git commit -m"" | create record of changes including a message|save file into project| prevent from losing work |

## 2. User Needs

### UN-GIT-01 — Inspect working state

> As a developer need to see which file have been changed. Because of this developer can see the changes.

### UN-GIT-02 — Change Verification

> Developer can view line by line changes. and if there unwanted changes they can solve it.

### UN-GIT-03 — Creating Checkpoints

> a devoloper needs a way to save there work on the project for permanently. so they create checkpoint using messages.

## 3. User Requirements

| ID and short title | User requirement | Source user need | Rationale |
|---|---|---|---|
| UR-GIT-01 Status Inspection | The tool report the current status of all files | UN-GIT-01 | Ensures the user exactly what is the state of the project before making any saves.|
| UR-GIT-02 Change Diffing | The tool display exact line-by-line differences between chnaged files | UN-GIT-02 |Prevent errors by allowing users to inspect the changed code |
| UR-GIT-03 Preparationvfor staged | The tool allow users to selectively add individual changed or modified files | UN-GIT-03 | Lets users stage related changes together |
| UR-GIT-04 create snapshot | The tool record a permanent checkpoint of staged files | UN-GIT-3 | Creates stable, traceable checkpoints that can be reviewed later|

