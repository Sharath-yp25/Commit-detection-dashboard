# 📝 NoteKeeper

A clean, folder-based note-taking app built with React + Vite.

## Features
- **Folder organisation** — create, colour-coded folders; delete removes all notes inside
- **Note management** — create, edit, delete notes with live auto-save
- **3-panel layout** — sidebar → note list → editor
- **Folder assignment** — move a note between folders right from the editor
- **Collapsible sidebar** — toggle to gain more reading space

## File Structure

```
note-keeper/
├── index.html                  # Vite HTML entry point
├── vite.config.js              # Vite + React plugin config
├── package.json
└── src/
    ├── main.jsx                # ReactDOM root render
    ├── App.jsx                 # Root component, wires everything together
    ├── hooks/
    │   └── useNotes.js         # All state logic — folders, notes, CRUD
    ├── components/
    │   ├── Sidebar.jsx         # Folder list, create/delete folders
    │   ├── NoteList.jsx        # Filtered note list, create/delete notes
    │   └── Editor.jsx          # Title + body editor, folder switcher
    └── styles/
        └── global.css          # Design tokens, layout grid, all component styles
```

## Getting Started

```bash
npm install
npm run dev
```

Open http://localhost:5173
