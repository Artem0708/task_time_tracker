# Task Time Tracker ⏱️

A professional time tracking application for monitoring work sessions across different tasks and projects.

## ✨ Features

### Core Functionality
- **Start/Stop Timer** - Simple one-click time tracking
- **Multiple Sessions** - Each task supports multiple work sessions
- **Real-time Counter** - Live timer display for active tasks
- **Automatic Totals** - Calculates total time per task automatically

### Data & Analytics
- **Complete Session History** - Detailed records of all work sessions
- **Flexible Task Management** - Add, reset, or remove tasks easily
- **CSV Export** - Download all data in spreadsheet format
- **Live Statistics** - Overview of tasks, time, and active tracking

### Time Zone Handling
- **UTC Standard** - All times recorded in UTC to prevent confusion
- **Timezone Display** - Your local timezone shown for reference
- **ISO Format** - Standardized timestamps for consistency

## 🖥️ Interface Features

- **Current Timezone** - Clearly displays your local timezone
- **Session Details** - Last session time and total session count per task
- **Active Task Indicator** - Visual highlighting for currently tracking tasks
- **Quick Stats** - At-a-glance overview of your productivity metrics

## 📁 CSV Export Structure

The exported CSV includes detailed session data with the following columns:

| Column | Description |
|--------|-------------|
| **Task Name** | Name of the tracked task/project |
| **Start Time (UTC)** | Session start time in ISO UTC format |
| **End Time (UTC)** | Session end time in ISO UTC format |
| **Duration (seconds)** | Session length in seconds |
| **Duration (hh:mm:ss)** | Session length in readable format |
| **Timezone** | Your local timezone for reference |

## 🔧 Technical Improvements

- **Multi-session Support** - Track the same task across multiple sessions
- **Complete History** - Every session stored with precise timestamps
- **Detailed Exports** - Separate CSV rows for each session
- **UTC Consistency** - Universal time format eliminates timezone issues

## 🚀 How to Use

1. **Enter Task Name** - Type your task in the input field
2. **Start Timer** - Click "Start" to begin tracking time
3. **Stop Timer** - Click "Stop" when you're done
4. **Review History** - View all tasks and accumulated time
5. **Export Data** - Download CSV for reporting or analysis

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Design**: Responsive layout, mobile-friendly
- **Theme**: Dark mode for comfortable extended use
- **Storage**: Browser local storage
- **Export**: Client-side CSV generation

## 💡 Key Benefits

| Benefit | Description |
|---------|-------------|
| **Precision Tracking** | Accurate measurement of task duration |
| **Professional Reports** | Detailed exports for clients and billing |
| **Global Compatibility** | UTC format works across all timezones |
| **User Experience** | Clean, eye-friendly dark interface |

---

**Ideal For**: Freelancers, remote teams, students, developers, and professionals who need detailed time tracking with export capabilities.

## 🎯 Quick Start

Simply open `index.html` in your web browser - no installation required!

The application works completely offline and stores all data locally in your browser.