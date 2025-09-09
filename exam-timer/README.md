# Exam Timer Manager

An advanced, browser-based timer application designed to help students and professionals manage their time effectively during exams, study sessions, or complex tasks. This tool allows for the creation of multiple, independent timers, each with configurable durations, labels, and break schedules.

## Features

- **Multiple Timers:** Add as many timers as you need to manage different sections or tasks simultaneously.
- **Global Controls:** Start, pause, reset, and remove all timers with a single click.
- **Count Up / Count Down:** Easily switch the direction for all timers.
- **Configurable Breaks:** For each timer, you can set a specific number of breaks and their duration.
- **Persistent State:** Your timer setup (including durations, labels, and progress) is automatically saved to your browser's local storage and reloaded when you reopen the app.
- **UI Locking:** Lock the interface to prevent accidental changes during an exam.
- **Customizable Labels:** Click on any timer's title to rename it.
- **Easy Time Editing:** Click on a timer's display (when paused) to quickly set a new duration in HHMM format.
- **Dark Mode:** Switch between light and dark themes for your comfort.
- **Volume Control:** Adjust the volume of the end-of-time chime.
- **Responsive Design:** The layout adapts for optimal use on both desktop and mobile devices.

## How to Use

- **Add a Timer:** Click the + Add Timer button to create a new timer. It will start with a default duration of 60 minutes.
- **Set Duration:** Click on the time display (e.g., "60m 00s") of any paused timer. A prompt will appear asking for the time in HHMM format (e.g., 0130 for 1 hour and 30 minutes).
- **Rename Timer:** Click on the "Timer X" label to give it a more descriptive name.
- **Control Timers:** Use the Start, Pause, and Reset buttons on individual cards or use the global controls at the top of the page.
- **Manage Breaks:**
	- Click Edit Breaks on a timer to configure the number of breaks and their duration.
	- Click the X min Break button during a session to start a break. The main timer will pause, and a break timer will begin.
- **Lock UI:** Once your timers are set up, click the 🔓 Unlocked button to lock the UI, preventing accidental clicks.
- **Save/Load:** Your session is saved automatically. Simply close the tab and reopen it later to resume where you left off.

## Running Locally

No server needed. Just open the `exam-timer.html` file in any modern web browser.
