Gitflow Workflow
Main Branches:

main: Contains production-ready code.
develop: Contains the latest development changes.
Supporting Branches:

feature/*: Used to develop new features. Branch off from develop and merge back into develop.
release/*: Used to prepare for a new production release. Branch off from develop and merge into both develop and main.
hotfix/*: Used to quickly fix production issues. Branch off from main and merge into both main and develop.
