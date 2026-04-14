# Focus Flow ⚡

A comprehensive productivity tool for Google AI Edge Gallery that combines Pomodoro timer, habit tracking, and goal management in one beautiful interface.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Type](https://img.shields.io/badge/type-JS%20%2B%20Webview-green)
![License](https://img.shields.io/badge/license-MIT-orange)

## ✨ Features

- **⏱️ Pomodoro Timer**
  - Customizable durations (15, 25, 45, 60 minutes or custom)
  - Beautiful circular progress visualization
  - Audio notifications on completion
  - Pause/resume functionality
  - Focus and break modes

- **✅ Habit Tracker**
  - Track daily habits
  - Build streaks with visual badges
  - Persistent data across sessions
  - Daily reset at midnight

- **🎯 Daily Goals**
  - Set and track today's goals
  - Visual progress bar
  - Check off completed goals
  - Auto-reset for new days

- **📊 Statistics**
  - Total focus sessions
  - Minutes focused
  - Day streak tracking
  - Weekly activity visualization
  - Completed goals counter

- **🎨 Beautiful Design**
  - Modern gradient UI
  - Smooth animations
  - Dark mode support (auto + manual)
  - Mobile-optimized touch interface
  - Responsive layout

- **💾 Data Persistence**
  - All data saved locally using localStorage
  - No internet required
  - Privacy-focused

## 🚀 Installation

### Method 1: From URL (Recommended)

1. Open Google AI Edge Gallery app
2. Navigate to Agent Skills
3. Tap the (+) button
4. Select "Load skill from URL"
5. Enter: `https://your-github-pages-url.com/focus-flow/`

### Method 2: Local Install

1. Download the `focus-flow` folder
2. Connect your Android device
3. Push to device:
   ```bash
   adb push focus-flow/ /sdcard/Download/
   ```
4. In the app, tap (+) → "Import local skill"
5. Select the `focus-flow` folder

## 📱 Usage

### Starting a Focus Session

**Voice/Text:**
- "Start a 25 minute focus session"
- "I need to focus for 45 minutes"
- "Start a Pomodoro timer"
- "Help me concentrate on writing code"

**Parameters:**
```json
{
  "action": "focus",
  "duration": 25,
  "customMessage": "Writing code"
}
```

### Taking a Break

**Voice/Text:**
- "I need a break"
- "Start a 5 minute break"
- "Time for a coffee break"

**Parameters:**
```json
{
  "action": "break",
  "duration": 5
}
```

### Tracking Habits

**Voice/Text:**
- "Show my habits"
- "Track my daily habits"
- "Help me build habits"

**Parameters:**
```json
{
  "action": "habits"
}
```

### Managing Goals

**Voice/Text:**
- "Show my goals for today"
- "What are my tasks?"
- "Help me track my goals"

**Parameters:**
```json
{
  "action": "goals"
}
```

### Viewing Statistics

**Voice/Text:**
- "Show my productivity stats"
- "How much have I focused this week?"
- "Show my statistics"

**Parameters:**
```json
{
  "action": "stats"
}
```

## 🛠️ Technical Details

### Structure

```
focus-flow/
├── SKILL.md              # LLM instructions and metadata
├── scripts/
│   └── index.html        # Background logic handler
├── assets/
│   └── webview.html      # Interactive UI
└── README.md             # This file
```

### Data Storage

All data is stored in `localStorage` under the key `focusFlowData`:

```javascript
{
  habits: [
    {
      name: "Morning exercise",
      streak: 5,
      completedToday: true,
      lastCompleted: "2026-04-14",
      createdAt: "2026-04-10T08:00:00.000Z"
    }
  ],
  goals: [
    {
      name: "Finish report",
      completed: false,
      createdAt: "2026-04-14T09:00:00.000Z"
    }
  ],
  stats: {
    totalSessions: 42,
    totalMinutes: 1050,
    streakDays: 7,
    completedGoals: 28,
    lastActiveDate: "2026-04-14",
    weeklyData: [5, 8, 6, 9, 7, 4, 3]
  }
}
```

### Browser Compatibility

- ✅ Chrome/Chromium (Android)
- ✅ WebView (Android)
- ✅ Safari (iOS)
- ✅ Mobile Safari (iOS)

### Web APIs Used

- `localStorage` - Data persistence
- `Audio Context` - Notification sounds
- `URLSearchParams` - Parameter parsing
- `Vibration API` - Haptic feedback (Android)
- `matchMedia` - Dark mode detection

## 🎨 Customization

### Colors

Edit CSS variables in `assets/webview.html`:

```css
:root {
    --primary: #6366f1;        /* Main color */
    --secondary: #ec4899;      /* Accent color */
    --success: #10b981;        /* Success states */
    --warning: #f59e0b;        /* Warnings */
    --danger: #ef4444;         /* Errors */
}
```

### Timer Durations

Modify the duration buttons in `assets/webview.html`:

```html
<button class="duration-btn" onclick="setDuration(20)">20m</button>
<button class="duration-btn" onclick="setDuration(30)">30m</button>
```

### Default Values

Change defaults in `scripts/index.html`:

```javascript
const duration = jsonData.duration || 25; // Default 25 minutes
```

## 📝 To-Do / Future Features

- [ ] Custom timer sound selection
- [ ] Weekly/monthly statistics view
- [ ] Export data to CSV
- [ ] Habit categories
- [ ] Goal prioritization
- [ ] Break reminders
- [ ] Session notes
- [ ] Integration with calendar
- [ ] Multi-language support

## 🐛 Known Issues

- Audio notification may not work on first interaction (browser security)
- Vibration only works on Android devices
- Dark mode toggle requires page reload in some browsers

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

## 📄 License

MIT License - feel free to use and modify for your needs.

## 🙏 Acknowledgments

- Built for [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery)
- Inspired by the Pomodoro Technique by Francesco Cirillo
- Design influenced by modern productivity apps

## 📧 Contact

- **Twitter/X**: [@ChainZenit](https://x.com/ChainZenit)
- **GitHub Issues**: [Create an issue](https://github.com/your-username/focus-flow/issues)
- **Discussions**: [Google AI Edge Gallery Skills](https://github.com/google-ai-edge/gallery/discussions/categories/skills)

---

**Made with ❤️ for focused productivity by [@ChainZenit](https://x.com/ChainZenit)**

⭐ If you find this useful, please star the project!
