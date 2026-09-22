# Intern Information Directory

A React interface for browsing intern records and sorting them by name. This is the `REACT12` version.

## Run locally

Install Node.js and npm, then:

```sh
git clone https://github.com/CyberTekena/REACT12.git
cd REACT12
npm install
npm run start
```

Open the local URL printed by the development server.

## Features

- Display a table of names, pictures, groups, grades, and attendance.
- Search by name.
- Toggle ascending and descending name order.

## Implementation

[App.js](src/App.js) contains the embedded records and search/sort state. [App.css](src/App.css) controls the layout. The page uses hard-coded records rather than a database or personnel API.

## Related versions

[Intern-Information-System](https://github.com/CyberTekena/Intern-Information-System) includes group search; [REACT12](https://github.com/CyberTekena/REACT12) provides the name-search variant.

## Scope

A frontend demonstration, not an operational personnel management system. There is no editing workflow, authentication service, or persistent record storage.
## Verification

Documentation was checked against the source and package scripts. Runtime behavior and deployment have not been certified by this documentation pass.

## Author

Tekena Ajuzieogu · [GitHub](https://github.com/CyberTekena)
