
# Alarm Clock

A minimal, terminal-styled alarm clock web application built with vanilla HTML, CSS, and JavaScript.

## Features

- **Real-time clock** with current date display
- **Multiple alarms** with custom labels
- **Sound selection** - Choose from 5 different alarm sounds:
    - Beep (square wave beeps)
    - Siren (frequency sweep)
    - Melody (musical notes)
    - Buzz (sawtooth pulses)
    - Random (procedurally generated)
- **Enable/disable alarms** without deleting them
- **Local storage** persistence across sessions
- **Full-screen modal** alarm notification with dismiss button
- **Dark monospace aesthetic** inspired by terminal interfaces

## Usage

1. Set the alarm time using the time input
2. Optionally add a label
3. Select your preferred alarm sound
4. Click "+ add" to create the alarm
5. Toggle alarms on/off or delete them from the list
6. When the alarm triggers, a full-screen overlay appears—click "dismiss" to stop it

## Technical Details

- Uses Web Audio API for sound generation via oscillators
- Alarm times stored in browser localStorage
- Single-file HTML implementation with embedded CSS and JavaScript
