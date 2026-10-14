# Kanban Project

## Business Requirements

- An MVP Kanban-style project management web application
- The application has a single board
- The board has exactly five columns, and each column can be renamed
- Each card has a title and details only
- A drag-and-drop interface moves cards between columns
- Users can add a card to a column and delete an existing card
- No archive, search, or filtering functionality; keep the feature set simple
- Prioritize a polished, professional user experience with simple features
- The application opens with dummy data on the board

## Technical Details

- Implemented as a modern, client-rendered Next.js application
- The Next.js application should be created in the `frontend` subdirectory
- No persistence
- No user management for the MVP
- Use popular libraries
- As simple as possible but with an elegant UI

## Color Scheme

- Accent Yellow: `#ecad0a` - accent lines, highlights
- Blue Primary: `#209dd7` - links, key sections
- Purple Secondary: `#753991` - submit buttons, important actions
- Dark Navy: `#032147` - main headings
- Gray Text: `#888888` - supporting text, labels

## Strategy

1. Write a plan with verifiable success criteria for each phase. Include project scaffolding, a `.gitignore` file, and rigorous unit testing.
2. Execute the plan, ensuring all criteria are met.
3. Carry out extensive integration testing with Playwright or a similar tool, fixing any defects.
4. Complete the work only when the MVP is finished and tested, with the server running and ready for the user.

## Coding Standards

1. Use the latest stable library versions and current idiomatic approaches.
2. Keep it simple: never over-engineer, always simplify, and avoid unnecessary defensive programming. Add no extra features.
3. Be concise. Keep the README minimal. Do not use emojis.
