# 🥚 Egg Timer Web App – Feature Specification

## 📌 Overview
The Egg Timer Web App is a responsive, browser-based timer designed to assist users in boiling eggs to their preferred doneness. It provides a set of predefined timers, customizable options, and simple controls optimized for both desktop and mobile use.

---

## 🔧 Functional Requirements

### 1. Countdown Timer
- **Description:** Core timer functionality for counting down from a set duration.
- **Inputs:**
  - Time in minutes/seconds (pre-set or custom)
- **Behavior:**
  - Countdown begins on "Start"
  - User can "Pause", "Resume", or "Reset"
- **Output:**
  - Real-time display of remaining time (MM:SS)

---

### 2. Pre-set Timers
- **Description:** Users can quickly start common egg boiling durations.
- **Options:**
  - Soft-boiled (4 minutes)
  - Medium-boiled (6 minutes)
  - Hard-boiled (10 minutes)
- **UI:** Clickable buttons or dropdown

---

### 3. Audible Alarm
- **Description:** Audio alert plays when the timer reaches zero.
- **Behavior:**
  - Sound automatically plays
  - User can dismiss alarm or mute in settings
- **Optional:** Select between 2–3 alarm tones

---

### 4. Visual Timer Display
- **Description:** Countdown displayed numerically and/or graphically.
- **UI:**
  - Large digital timer (MM:SS)
  - Optional circular progress bar or linear progress bar

---

### 5. Responsive Design
- **Description:** UI adapts to various screen sizes and orientations.
- **Platforms:** Desktop, tablet, and mobile browsers
- **Behaviors:**
  - Buttons resize appropriately
  - Timer remains visible at all times

---

### 6. Custom Timer
- **Description:** Allows users to input a custom duration.
- **Input:** Manual entry of minutes and seconds
- **Validation:** Accepts only valid time inputs (e.g., not negative or >60 minutes)

---

### 7. Keyboard Shortcuts
- **Description:** Basic keyboard controls for improved accessibility.
- **Shortcuts:**
  - `Spacebar`: Start/Pause/Resume
  - `R` key: Reset timer
- **Behavior:** Only active when the app is in focus

---

## 🔊 Non-Functional Requirements

### A. Performance
- Timer should have a precision of ±1 second
- Alarm should trigger exactly at zero

### B. Accessibility
- Timer readable via screen readers
- High contrast for readability

### C. Browser Compatibility
- Compatible with latest versions of:
  - Chrome
  - Firefox
  - Safari
  - Edge

---

## 🧩 Optional (Future Consideration)
- Dark mode toggle
- Saving last used custom time
- Background tab notifications
