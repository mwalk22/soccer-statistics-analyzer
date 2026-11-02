# Soccer Statistics Analyzer

## Project Overview

The Soccer Statistics Analyzer is a Java-based command-line application designed to help users organize, compare, and evaluate soccer player statistics. Comparing players often requires searching through multiple websites and manually organizing statistics. This project will centralize player statistics in one application and make player comparisons easier.

Users will be able to enter player information, store statistics, search for specific players, compare performances, and generate rankings based on selected statistical categories.

## Project Goals

- Create a centralized system for storing soccer player statistics.
- Allow users to search for players by name or team.
- Compare two players using their performance statistics.
- Generate rankings based on selected statistical categories.
- Apply Java programming concepts, file handling, and version control.

## MVP Scope

The Minimum Viable Product (MVP) will include:

1. **Add Players:** Allow users to enter a player's name, team, appearances, goals, and assists.
2. **Store Player Data:** Maintain player information using an ArrayList.
3. **Save and Load Data:** Store player information in a CSV file and load it when the application starts.
4. **Search Players:** Find players by name or team.
5. **Compare Players:** Display the statistics of two selected players for comparison.
6. **Rank Players:** Sort players based on a selected statistic, such as goals or assists.

The initial version will use manually entered data rather than connecting to live soccer databases or external APIs.

## Future Plans

After completing the MVP, potential improvements include:

- Integrating an online soccer statistics API to retrieve player data automatically.
- Adding advanced statistics, including goals and assists per appearance.
- Creating graphical charts to visualize player performance.
- Adding filters for leagues, teams, positions, and seasons.
- Allowing users to export rankings and comparisons to CSV files.

These features will be considered after the core application is functional.

## Technology Stack

| Technology | Purpose |
|---|---|
| Java | Primary programming language |
| ArrayList | Store player objects |
| Scanner | Receive user input |
| Collections | Sort and rank player statistics |
| File I/O | Read and write player data |
| CSV | Store player information |
| Visual Studio Code | Development environment |
| Git and GitHub | Version control and project documentation |

No external libraries or APIs are required for the initial version.

## Project Structure

```text
Soccer-Statistics-Analyzer/
├── README.md
├── src/
│   ├── Main.java
│   └── Player.java
├── tests/
├── docs/
│   ├── Project-Design.pdf
│   ├── MVP-Scope.pdf
│   ├── Soccer-Statistics-Analyzer-Architecture.drawio
│   └── Soccer-Statistics-Analyzer-Architecture.png
└── data/
    └── players.csv
```

## Development Plan

Development will be divided into the following milestones:

1. Set up the GitHub repository and Java project structure.
2. Create the Player class and define its attributes.
3. Build the command-line menu.
4. Implement player entry and ArrayList storage.
5. Implement CSV file reading and writing.
6. Add player search functionality.
7. Implement player comparisons and statistical rankings.
8. Test the application, fix errors, and finalize documentation.

Each milestone will be documented through individual Git commits to track development progress.

## Current Status

The project is currently in the planning and initial setup stage. The repository, project structure, and design documentation are being established before implementation begins.