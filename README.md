# AIML_Ajith-ajubhai1
# Personal Knowledge Vault 


## Features 

- **Create Notes** - Add new notes with title and content
- **View All Notes** - Display all stored notes at once
- **Search Notes** - Find notes by keyword in title or content
- **Edit Notes** - Update existing notes by ID
- **Delete Notes** - Remove notes you no longer need
- **Persistent Storage** - All notes are saved in `notes.json`

## Prerequisites 

- Python 3.x installed on your system
- No external dependencies required (uses only standard library)

## Installation 

1. Clone this repository:
```bash
git clone https://github.com/yourusername/personal-knowledge-vault.git
cd personal-knowledge-vault
```

2. Run the application:
```bash
python notes_app.py
```

## Usage 

When you run the application, you'll see a menu with 6 options:

```
========================================
PERSONAL KNOWLEDGE VAULT
========================================
1. Creating Note
2. View All Notes
3. Search for Notes
4. Edit Note
5. Delete Note
6. Exiting the program
========================================
```

### Creating a Note
- Select option `1`
- Enter a title for your note
- Enter the content
- Note will be saved automatically

### Viewing Notes
- Select option `2` to display all stored notes with their IDs, titles, and content

### Searching Notes
- Select option `3`
- Enter a keyword to search
- All notes matching the keyword in title or content will be displayed

### Editing a Note
- Select option `4`
- Enter the ID of the note you want to edit
- Provide new title and content

### Deleting a Note
- Select option `5`
- Enter the ID of the note you want to delete
- Confirm deletion

## File Structure 

```
personal-knowledge-vault/
│
├── notes_app.py        # Main application file
├── notes.json          # Auto-generated storage file (created on first note)
└── README.md           # This file
```

## Data Storage 

Notes are stored in `notes.json` in the following format:

```json
[
  {
    "id": 1,
    "title": "Sample Note",
    "content": "This is a sample note content"
  }
]
```

## Known Issues 🐛

- The edit function has spacing issues in the dictionary keys that may cause errors
- Note IDs are based on list length, which may cause ID conflicts after deletions

## Future Enhancements 🔮

- [ ] Add categories/tags for notes
- [ ] Implement note timestamps
- [ ] Add export functionality (PDF, TXT)
- [ ] Support for markdown formatting
- [ ] Cloud sync capabilities
- [ ] GUI version using tkinter

## Contributing 🤝

This project is part of the SOSC Challenge. Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


