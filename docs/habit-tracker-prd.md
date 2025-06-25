# Product Requirements Document
## Simple Habit Tracker - iOS Application

### Document Information
- **Version**: 2.0
- **Date**: June 25, 2025
- **Status**: Simplified
- **Concept**: Ultra-minimalist habit tracker with Apple Fitness-style trends

---

## 1. Product Vision

A dead-simple iOS app for tracking anything with beautiful Apple Fitness-style trend visualizations. No accounts, no complexity - just track and see trends.

## 2. Core Principle

**One Function**: Track events and show trends. That's it.

## 3. Features

### 3.1 Quick Tracking
- **Add Item**: Name it, pick a color (that's all)
- **Log Event**: One tap from main screen or widget (increments by 1)
- **That's all**

### 3.2 Trends Screen (Like Your Screenshot)
- Grid of tracking cards showing:
  - Icon and name
  - Current value (e.g., "7 TIMES/DAY")
  - Trend arrow (↑ ↓ →)
  - Mini sparkline graph
- Tap any card for detailed view:
  - Full-screen graph
  - Daily/Weekly/Monthly/Yearly views
  - Best streak
  - Total count

### 3.3 Technical Simplicity
- **Storage**: Core Data (local only)
- **Backup**: iCloud (automatic)
- **Privacy**: Everything on-device
- **No accounts**: Works immediately

## 4. User Flow

1. **First Launch**: Empty state with "+" button
2. **Add Habit**: Name, pick icon/color, select unit type
3. **Main Screen**: List of habits with big tap zones
4. **Log**: Tap to increment/log
5. **Trends**: Swipe right or tap "Trends" to see grid

## 5. Design

### Visual Style (Exactly Like Fitness App)
- Black background
- Vibrant colored icons
- Large, bold numbers
- Colored trend arrows
- Round rect cards with subtle borders
- SF Pro Display font

### Interaction
- Tap to log
- Swipe for trends
- Long press for options
- No menus, no settings

## 6. Widget
- Shows up to 4 habits
- Tap to log directly
- Updates immediately

## 7. What We DON'T Build
- User accounts
- Social features  
- Reminders/notifications
- Goals or targets
- Categories or organization
- Import/export
- Detailed settings
- Onboarding flow

---

**Bottom Line**: If Apple Fitness and a habit tracker had a baby, this would be it. Beautiful trends, instant logging, zero friction.