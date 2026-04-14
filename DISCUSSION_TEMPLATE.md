# Focus Flow - GitHub Discussion Template

Copy and paste this into GitHub Discussions when sharing your skill!

---

# [Focus Flow]: Pomodoro Timer + Habit Tracker + Productivity Stats

## 🎯 Description

**Focus Flow** is a comprehensive productivity tool that brings the power of time management directly to your AI Edge Gallery app. It combines the proven Pomodoro Technique with habit tracking and goal management, all wrapped in a beautiful, intuitive interface.

Perfect for:
- Students studying for exams
- Developers doing deep work
- Anyone building better habits
- Productivity enthusiasts
- Focus seekers

## ✨ Features

### ⏱️ Pomodoro Timer
- **Customizable durations**: 15, 25, 45, 60 minutes (or ask for custom)
- **Beautiful visualization**: Circular progress with gradient colors
- **Audio alerts**: Sound notification when session completes
- **Pause/Resume**: Life happens, we got you covered
- **Focus & Break modes**: Alternate between work and rest

### ✅ Habit Tracker
- **Unlimited habits**: Track as many as you want
- **Streak system**: Build momentum with 🔥 streak badges
- **Daily reset**: Fresh start every day at midnight
- **Visual feedback**: See your progress at a glance
- **Motivational**: Celebrate consistency

### 🎯 Daily Goals
- **Task management**: Add today's important objectives
- **Progress bar**: Visual representation of completion
- **Quick toggle**: Mark goals complete with a tap
- **Achievement counter**: Track total goals completed
- **Daily refresh**: New goals for new days

### 📊 Productivity Statistics
- **Total sessions**: How many Pomodoros completed
- **Minutes tracked**: Total focus time accumulated
- **Day streak**: Consecutive days using the app
- **Goals completed**: Total achievements unlocked
- **Weekly chart**: Visual breakdown of daily activity

### 🎨 Design & UX
- **Modern gradients**: Beautiful purple-to-pink color scheme
- **Dark mode**: Auto-detects system preference + manual toggle
- **Smooth animations**: Professional transitions and effects
- **Mobile-first**: Optimized for touch interactions
- **Responsive**: Works on any screen size

### 💾 Technical Features
- **100% offline**: No internet required after install
- **localStorage**: All data persists locally
- **Privacy-focused**: Your data never leaves your device
- **Fast**: Instant loading, no lag
- **Lightweight**: ~40KB total size

## 📱 Installation

### Method 1: From URL (Recommended)
```
https://podzemniytip.github.io/focus-flow/
```

1. Open AI Edge Gallery
2. Go to Agent Skills
3. Tap (+) → "Load skill from URL"
4. Enter the URL above
5. Done! 🎉

### Method 2: Local Install
```bash
adb push focus-flow/ /sdcard/Download/
```
Then import in app using file picker.

## 🗣️ Voice Commands

Focus Flow integrates seamlessly with Gemma. Just speak naturally:

**Timer:**
- "Start a 25 minute focus session"
- "I need to focus for an hour"
- "Help me concentrate on writing"
- "Start a Pomodoro timer"

**Breaks:**
- "I need a break"
- "Start a 5 minute break"
- "Time for a coffee break"

**Habits:**
- "Show my daily habits"
- "Track my habits"
- "What are my habits?"

**Goals:**
- "Show my goals for today"
- "What are my tasks?"
- "Help me manage my goals"

**Stats:**
- "Show my productivity statistics"
- "How much have I focused this week?"
- "Display my stats"

## 📸 Screenshots

[Add 4-6 screenshots here showing:]
1. Timer view with active session
2. Habits list with streaks
3. Goals with progress bar
4. Statistics dashboard
5. Dark mode view
6. Mobile interface

## 🎥 Demo Video

[Optional: Add a 30-60 second video showing:]
- Starting a timer
- Checking off a habit
- Adding and completing a goal
- Viewing statistics

## 🚀 Why Focus Flow?

### Unique Value Proposition
Unlike simple timer skills, Focus Flow is a **complete productivity system**:

1. **Integrated**: Timer + Habits + Goals in one place
2. **Data-driven**: Track progress over time with stats
3. **Motivational**: Streaks and achievements keep you going
4. **Beautiful**: Actually pleasant to look at and use
5. **Private**: Everything stays on your device

### Use Cases

**For Students:**
- 25-min study sessions → Track studying habit → Goal: "Finish chapter 3"

**For Developers:**
- 45-min coding sessions → Track "Daily commit" habit → Goal: "Fix bug #127"

**For Writers:**
- 50-min writing sessions → Track "Write daily" habit → Goal: "1000 words"

**For Anyone:**
- Build any habit → Track progress → See weekly patterns → Stay motivated

## 🛠️ Technical Details

**Type**: JavaScript Skill with Webview
**Size**: ~40KB
**Dependencies**: None (vanilla JS)
**Browser Support**: Chrome, Safari, WebView
**Offline**: ✅ Yes
**Data**: localStorage only
**API Calls**: None
**Secrets**: Not required

**Technologies:**
- HTML5 + CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Web APIs (Audio Context, localStorage, Vibration)
- SVG (for circular progress)
- URLSearchParams (for LLM communication)

## 📊 Performance

- **Load time**: < 100ms
- **Timer accuracy**: ±1 second
- **Storage used**: ~10-50KB depending on usage
- **Battery impact**: Minimal (only active when visible)

## 🔮 Roadmap

### Planned Features (v1.1+)
- [ ] Custom notification sounds
- [ ] Export stats to CSV
- [ ] Habit categories/tags
- [ ] Goal prioritization (High/Med/Low)
- [ ] Break reminders
- [ ] Session notes
- [ ] Multiple color themes
- [ ] Widget view for quick access

### Community Requests
Let me know what you'd like to see! Open to suggestions.

## 🤝 Contributing

This is an open-source project! Contributions welcome:

- **Bug reports**: Found an issue? Let me know
- **Feature ideas**: Have a suggestion? Share it
- **Code contributions**: PRs welcome
- **Translations**: Help make it multilingual
- **Testing**: Try it and give feedback

**Repository**: https://github.com/podzemniytip/focus-flow

## 📚 Documentation

- **README**: Full documentation
- **QUICKSTART**: Get started in 2 minutes
- **DEPLOYMENT**: How to host your own version
- **CONTRIBUTING**: How to contribute

## 🏆 Recognition

If you find this useful:
- ⭐ Star the repository
- 💬 Share in discussions
- 📱 Share with friends
- 🐦 Tweet about it
- 📝 Write a review

## 📞 Support & Contact

- **Twitter/X**: [@ChainZenit](https://x.com/ChainZenit)
- **Issues**: https://github.com/podzemniytip/focus-flow/issues
- **Discussions**: https://github.com/podzemniytip/focus-flow/discussions

## 📄 License

MIT License - Free to use, modify, and distribute.

## 🙏 Acknowledgments

- Built for [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery)
- Inspired by the Pomodoro Technique
- Thanks to the open-source community

---

## 💡 Example Session

Here's a typical productivity session with Focus Flow:

1. **Morning (9:00 AM)**
   - Say: "Show my habits"
   - Check off: ✅ Morning exercise, ✅ Healthy breakfast

2. **Work Start (9:30 AM)**
   - Say: "What are my goals today?"
   - Add goals: "Finish report", "Review PRs", "Plan sprint"

3. **First Focus Block (9:35 AM)**
   - Say: "Start a 45 minute focus session for finishing the report"
   - Work uninterrupted for 45 minutes
   - ✅ Complete: "Finish report" goal

4. **Break (10:20 AM)**
   - Say: "I need a break"
   - 5 minute break to stretch and hydrate

5. **Continue...**
   - Repeat focus → break cycles
   - Check off goals as you complete them

6. **End of Day (6:00 PM)**
   - Say: "Show my productivity stats"
   - See: 6 sessions, 225 minutes, 3 goals completed
   - Feel accomplished! 🎉

---

**Ready to boost your productivity? Install Focus Flow today!** ⚡

_Questions? Just ask below! I'm here to help._ 💬

## Tags
#productivity #pomodoro #habits #focus #timer #goals #statistics #motivation #offline #javascript #webview #ai-edge-gallery #gemma

---

**Made with ❤️ for the AI Edge Gallery community by [@ChainZenit](https://x.com/ChainZenit)**

⭐ **Star on GitHub** | 🐦 **Follow on X** | 🔗 **Share with Friends** | 💬 **Join Discussion**
