# Productivity Manager Extension

_COMPANY_: CODTECH IT SOLUTIONS

_NAME_: SHIV PATEL

_INTERN ID_: CT06DL588

_DOMAIN_: MERN STACK WEB DEVELOPMENT

_DURATION_: 6 WEEKS

_MENTOR_: NEELA SANTOSH

A comprehensive Chrome extension designed to boost your productivity with task management, Pomodoro timer, and distraction blocking features.

## Features

### Task Management

- **Add Tasks**: Quickly add new tasks with a simple input field
- **Mark Complete**: Click on tasks to mark them as done
- **Delete Tasks**: Remove tasks you no longer need
- **Persistent Storage**: Tasks are saved locally and persist across browser sessions

### Pomodoro Timer

- **25-minute Focus Sessions**: Classic Pomodoro technique implementation
- **Timer Controls**: Start and stop the timer as needed
- **Desktop Notifications**: Get notified when your focus session is complete
- **Background Alarms**: Timer continues running even when popup is closed

### Website Blocker

- **Distraction Blocking**: Automatically blocks access to distracting websites
- **Pre-configured Sites**: Blocks YouTube, Facebook, and Instagram by default
- **Full-screen Overlay**: Displays a motivational message when blocked sites are accessed

### Dark Mode

- **Theme Toggle**: Switch between light and dark themes
- **Persistent Preference**: Your theme choice is saved and remembered
- **Modern Design**: Clean, professional interface with smooth transitions

## Installation

1. **Download the Extension**

   ```bash
   git clone https://github.com/yourusername/Productivity-Extension.git
   ```

2. **Load in Chrome**
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode" in the top-right corner
   - Click "Load unpacked" and select the extension folder
   - The extension icon will appear in your browser toolbar

## Technical Details

### Core Technologies

- **Manifest V3**: Latest Chrome extension standard
- **Chrome Storage API**: For persistent data storage
- **Chrome Alarms API**: For background timer functionality
- **Chrome Notifications API**: For desktop notifications
- **Content Scripts**: For website blocking functionality

### Key Files

- **[`manifest.json`](manifest.json)**: Defines extension permissions and configuration
- **[`popup.html`](popup.html)**: Main user interface structure
- **[`popup.js`](popup.js)**: Handles task management, timer, and theme functionality
- **[`background.js`](background.js)**: Manages alarms and notifications
- **[`content.js`](content.js)**: Implements website blocking overlay
- **[`styles.css`](styles.css)**: Modern styling with CSS variables and dark mode support

## Usage

### Managing Tasks

1. Click the extension icon to open the popup
2. Type a task in the input field and click "Add" or press Enter
3. Click on any task to mark it as complete
4. Click the "✕" button to delete a task

### Using the Pomodoro Timer

1. Click "Start" to begin a 25-minute focus session
2. The timer will count down and show desktop notification when complete
3. Click "Stop" to cancel the current session

### Enabling Dark Mode

1. Toggle the "Dark Mode" switch at the bottom of the popup
2. Your preference will be saved automatically

## Permissions

The extension requires the following permissions:

- **Storage**: To save tasks and preferences
- **Notifications**: To alert you when Pomodoro sessions complete
- **Alarms**: To run the timer in the background
- **Host Permissions**: To block distracting websites


## Output
![Image](https://github.com/user-attachments/assets/a3e0cc39-3f8a-426d-97df-42c020df78e7)
_Extension Overview_

![Image](https://github.com/user-attachments/assets/77e6b83a-23fd-440d-9dcb-e47b46db24b0)
_Extension in Light Mode_

![Image](https://github.com/user-attachments/assets/45772b0e-937f-430b-8b78-ef70d29bb835)
_Extension in Dark Mode_

![Image](https://github.com/user-attachments/assets/a9961ad2-d335-4d78-bc99-bef02aac24c0)
_Blocked Websites_

![Image](https://github.com/user-attachments/assets/15f6168b-3807-424c-87b8-99a584ff16f5)
_Notification after completing pomodoro timer_

**Stay focused, stay productive!**
