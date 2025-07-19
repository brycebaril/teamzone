# Timezone Tracker

A simple, elegant tool for tracking team members across different time zones with a NodeSource-inspired UI.

![Timezone Tracker Screenshot](https://via.placeholder.com/800x400?text=Timezone+Tracker+Screenshot)

## Features

- **Real-time timezone visualization**: See where each team member is in their day at a glance
- **Custom emoji identifiers**: Personalized emoji for each team member
- **Working hours highlighting**: Easily identify when team members are in their working hours
- **Persistent storage**: All changes are saved to localStorage

## Usage

### Getting Started

1. Open the `index.html` file in your browser or host it on any static web server
2. The app comes pre-loaded with a sample dataset of team members
3. All changes you make will be saved to your browser's localStorage

### Managing Team Members

- **Add a team member**: Click the "Add New Person" button
- **Edit a team member**: Click on their name, city, or timezone to edit
- **Change emoji**: Click on a team member's emoji to open the emoji picker
- **Remove a team member**: Click the "×" button next to their name
- **Reset data**: Click the "Reset Data" button to restore the initial dataset

## Technical Details

### Dependencies

- No build process required
- Uses CDN-hosted libraries:
  - [Tailwind CSS](https://tailwindcss.com/) for styling
  - [emoji-picker-element](https://github.com/nolanlawson/emoji-picker-element) for emoji selection

## License

MIT
