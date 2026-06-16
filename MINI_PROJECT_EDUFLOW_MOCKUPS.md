# EduFlow Prototype - Visual Mockups & Screen Specifications

Complete visual guide for all 9 screens of the EduFlow online learning platform prototype.

---

## Screen 1: Onboarding - Splash

```
╔═══════════════════════════════════╗
║                                   ║
║                                   ║
║          [EduFlow Logo]           ║
║          (120×120px)              ║
║                                   ║
║    "Learn Anything,               ║
║     Anytime, Anywhere"            ║
║                                   ║
║      Start your learning          ║
║      journey today               ║
║      (Body small, gray)           ║
║                                   ║
║                                   ║
║        [Get Started →]            ║
║      (Primary button 56px)        ║
║                                   ║
║   Already have an account?        ║
║        [Sign In]                  ║
║      (Text link, underline)       ║
║                                   ║
║                                   ║
╚═══════════════════════════════════╝

Design Notes:
• Clean, minimal design
• Large logo creates visual anchor
• Clear primary action
• Secondary action visible but not prominent
• Ample whitespace
• Warm color scheme (future screenshots)

Color Scheme:
- Background: #FFFFFF
- Text: #111827 (dark)
- Button: #6366F1 (indigo)
- Button text: #FFFFFF
```

---

## Screen 2: Onboarding - Learning Goals

```
╔═══════════════════════════════════╗
║ ← Back          [1/3]    Next → ║
║                                   ║
║  What do you want to learn?      ║
║  (H2: 36px bold)                 ║
║                                   ║
║  Select all that apply:          ║
║  (Body small, gray)              ║
║                                   ║
║  ☑️  Career Advancement           ║
║      Learn skills for job growth ║
║                                   ║
║  ☐ Skill Development             ║
║      Build practical expertise   ║
║                                   ║
║  ☑️  Personal Interest            ║
║      Follow your passions        ║
║                                   ║
║  ☐ Academic Support             ║
║      Complete school coursework  ║
║                                   ║
║  ☐ Hobby & Creativity           ║
║      Explore new talents         ║
║                                   ║
║  (3 selected)                    ║
║                                   ║
║        [Continue]                ║
║                                   ║
╚═══════════════════════════════════╝

Interactions:
• Multi-select allowed
• Checkboxes show selection
• Counter updates as items selected
• Continue button enabled when 1+ selected
• Back to step 1/1 navigation

Colors:
- Unchecked: #D1D5DB border
- Checked: #6366F1 background, #FFFFFF checkmark
- Label: #111827
- Description: #4B5563
```

---

## Screen 3: Home Dashboard

```
╔═══════════════════════════════════╗
║ Good morning, Alex! 🔔    👤    ║
║ (16px, greeting)                 ║
╠═══════════════════════════════════╣
║                                   ║
║ LEARNING STATS (Horizontal scroll)║
║                                   ║
║  ┌──────────┐  ┌──────────┐     ║
║  │    🔥    │  │   📚     │     ║
║  │ 7-Day    │  │ 12.5     │     ║
║  │ Streak   │  │ Hours    │     ║
║  └──────────┘  └──────────┘     ║
║                                   ║
║  ┌──────────┐  ┌──────────┐     ║
║  │    ⭐    │  │   🏆    │     ║
║  │ 3        │  │ 5       │     ║
║  │ Courses  │  │ Badges  │     ║
║  └──────────┘  └──────────┘     ║
║                                   ║
╠═══════════════════════════════════╣
║ CONTINUE LEARNING                 ║
║ (14px bold uppercase)             ║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ [Course Image 16:9] 160px      │║
║ │ Python for Beginners           │║
║ │ Code Masters                   │║
║ │ ▓▓▓▓▓░░░░  50%                 │║
║ │ Watched 2 hours ago            │║
║ │ [Continue Watching →]          │║
║ └────────────────────────────────┘║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ [Course Image 16:9] 160px      │║
║ │ UI/UX Design Fundamentals      │║
║ │ Sarah Johnson                  │║
║ │ ▓▓▓▓░░░░░░  35%                │║
║ │ Watched 5 days ago             │║
║ │ [Continue Watching →]          │║
║ └────────────────────────────────┘║
║                                   ║
╠═══════════════════════════════════╣
║ RECOMMENDED FOR YOU               ║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ [Image] [NEW]                  │║
║ │ ⭐⭐⭐⭐⭐ 4.8 (523)           │║
║ │ Advanced JavaScript            │║
║ │ John Doe  •  $49.99            │║
║ │ [❤️] [Add to Cart]              │║
║ └────────────────────────────────┘║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ [Image] [POPULAR]              │║
║ │ ⭐⭐⭐⭐⭐ 4.9 (891)           │║
║ │ Digital Marketing Mastery      │║
║ │ Marketing Pro  •  FREE         │║
║ │ [❤️] [Enroll Now]               │║
║ └────────────────────────────────┘║
║                                   ║
╠═══════════════════════════════════╣
║ 🏠 Home  🔍 Explore  📦 ...      ║
╚═══════════════════════════════════╝

Design Elements:
• Personalized greeting
• Stat cards show at-a-glance progress
• Carousel for horizontal scrolling
• Course cards with clear CTA
• Progress bars visual feedback
• Bottom navigation always visible

Colors:
- Stats background: #F9FAFB
- Progress bar filled: #6366F1
- Progress bar empty: #E5E7EB
- Card background: #FFFFFF
- Shadow: 0 4px 12px rgba(0,0,0,0.08)
```

---

## Screen 4: Course Discovery

```
╔═══════════════════════════════════╗
║ Search courses...        [⚙️]    ║
║ (Search bar 48px)                ║
╠═══════════════════════════════════╣
║                                   ║
║ Quick Filters (Horizontal):      ║
║ [All ▼] [Free] [Paid]           ║
║ [Beginner] [Intermediate]        ║
║                                   ║
║ 2,450 courses found              ║
║ Sort by: Relevance ▼             ║
║                                   ║
╠═══════════════════════════════════╣
║ CATEGORIES (Horizontal scroll):  ║
║                                   ║
║ 💻 Programming | 💼 Business    ║
║ 🎨 Design | 📱 Apps             ║
║ 🎓 Language | 📸 Photography    ║
║                                   ║
╠═══════════════════════════════════╣
║ COURSE CARDS (Vertical scroll):  ║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ [Image 16:9]        [NEW]      │║
║ │                                 │║
║ │ The Complete Python Course     │║
║ │ Programming Experts            │║
║ │ ⭐⭐⭐⭐⭐ 4.8 • 2,543 reviews   │║
║ │ $49.99 ← $99.99 (50% off)     │║
║ │ [❤️] [Explore]                 │║
║ └────────────────────────────────┘║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ [Image 16:9]     [BESTSELLER]  │║
║ │                                 │║
║ │ Web Development Bootcamp       │║
║ │ Code Academy                   │║
║ │ ⭐⭐⭐⭐⭐ 4.7 • 1,891 reviews   │║
║ │ $79.99                         │║
║ │ [❤️] [Explore]                 │║
║ └────────────────────────────────┘║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ [Image 16:9]        [FREE]     │║
║ │                                 │║
║ │ Intro to Machine Learning      │║
║ │ Data Science Institute         │║
║ │ ⭐⭐⭐⭐ 4.5 • 892 reviews      │║
║ │ FREE                           │║
║ │ [❤️] [Enroll]                   │║
║ └────────────────────────────────┘║
║                                   ║
╠═══════════════════════════════════╣
║ 🏠 Home  🔍 Explore  📦 ...      ║
╚═══════════════════════════════════╝

Features:
• Search bar with icon
• Quick filters for rapid refinement
• Category carousel for exploration
• Course cards show all key info
• Discount badges prominent
• Price comparison visible
• Rating with review count

Colors:
- Filter active: #6366F1 background, #FFFFFF text
- Filter inactive: #E5E7EB background
- Discount badge: #EF4444 background
- Price: #6366F1 (primary)
- Old price: #9CA3AF strikethrough
```

---

## Screen 5: Course Details

```
╔═══════════════════════════════════╗
║ ← [Large Course Image 16:9]      ║
║   180px height, full width       ║
║   [Overlay]                      ║
║   Python Bootcamp                ║
║   By: Code Masters               ║
╠═══════════════════════════════════╣
║                                   ║
║ ⭐⭐⭐⭐⭐ 4.8 (2,543)            ║
║ $49.99 ← $99.99 (50% off)        ║
║                                   ║
╠═══════════════════════════════════╣
║ OVERVIEW | CURRICULUM | REVIEWS  ║
║ (Tab navigation)                 ║
╠═══════════════════════════════════╣
║                                   ║
║ COURSE DESCRIPTION               ║
║ (H3: 24px)                       ║
║                                   ║
║ Learn Python from scratch with    ║
║ this comprehensive bootcamp.     ║
║ (Body: 16px)                     ║
║                                   ║
║ What you'll learn:               ║
║ • Python fundamentals           ║
║ • Object-oriented programming   ║
║ • Working with APIs             ║
║ • Real-world projects           ║
║                                   ║
╠═══════════════════════════════════╣
║ ABOUT INSTRUCTOR                  ║
║                                   ║
║ 👤 [Avatar 40×40px]              ║
║ John Developer                   ║
║ Lead Software Engineer           ║
║ ⭐ 4.9 avg rating • 45K+ students║
║ [Follow]                         ║
║                                   ║
╠═══════════════════════════════════╣
║ STUDENT REVIEWS                   ║
║                                   ║
║ ⭐⭐⭐⭐⭐                        ║
║ "Best course I've taken!"        ║
║ - Alex M. (2 weeks ago)          ║
║                                   ║
║ ⭐⭐⭐⭐                         ║
║ "Great content, need more..."    ║
║ - Sarah K. (1 month ago)         ║
║                                   ║
║ [See All Reviews]                ║
║                                   ║
╠═══════════════════════════════════╣
║  [Enroll Now - $49.99] (Sticky)  ║
╚═══════════════════════════════════╝

Interactive Elements:
• Tab switching (smooth transition)
• Collapsible sections (curriculum)
• Follow button toggle
• Sticky CTA at bottom
• Wishlist icon (toggles heart color)
• Smooth scroll to top of page

Colors:
- Tab active underline: #6366F1 (3px)
- Instructor follow button: #E5E7EB → #6366F1 on hover
- CTA button: #6366F1 background, #FFFFFF text
```

---

## Screen 6: Learning Module - Video Lesson

```
╔═══════════════════════════════════╗
║ ← Python for Beginners  ...      ║
║ (Header sticky)                  ║
╠═══════════════════════════════════╣
║                                   ║
║ ┌────────────────────────────────┐║
║ │                                 │║
║ │      [VIDEO PLAYER]            │║
║ │      Playing: Lesson 1         │║
║ │      00:45 / 15:30             │║
║ │      ▓▓▓░░░░░░░ 30%            │║
║ │                                 │║
║ │  ⏮ ⏪ ⏯ ⏩ ⏭ [⛶] [🔊] [1x▼]   │║
║ │                                 │║
║ └────────────────────────────────┘║
║ (16:9 aspect, 280px height)      ║
║                                   ║
║ Lesson 1: Python Basics          ║
║ (H3: 20px)                       ║
║ Module 1 • 15 min                ║
║ [☐ Mark as complete]             ║
║                                   ║
╠═══════════════════════════════════╣
║ LESSON DESCRIPTION                ║
║                                   ║
║ In this lesson, you'll learn:    ║
║ • Python syntax                 ║
║ • Variables and data types      ║
║ • Basic operations              ║
║                                   ║
║ Resources:                       ║
║ [📥 Download Slides]             ║
║ [📥 Download Code Files]         ║
║                                   ║
╠═══════════════════════════════════╣
║ INTERACTIVE FEATURES              ║
║                                   ║
║ [📝 Take Notes] [❓ Q&A]         ║
║ [💬 Comments]                    ║
║                                   ║
║ Ask a question...                ║
║ (2 other students have asked)    ║
║                                   ║
╠═══════════════════════════════════╣
║ LESSON NAVIGATION                 ║
║                                   ║
║ ← Lesson 0: Intro                ║
║   [Complete ✓]                   ║
║                                   ║
║ → Lesson 2: Variables            ║
║   [Estimated 12 min]             ║
║                                   ║
║ [View Full Curriculum]           ║
║                                   ║
╠═══════════════════════════════════╣
║ 🏠 Home  🔍 Explore  📦 ...      ║
╚═══════════════════════════════════╝

Interactive Features:
• Video player controls (play, speed, fullscreen)
• Progress bar draggable
• Progress tracking (✓ mark complete)
• Tab section switching (resources, notes, comments)
• Next lesson button prominent
• Download resources available

Colors:
- Completed lesson: #10B981 (green checkmark)
- Video background: #000000
- Control icons: #FFFFFF
- Progress bar filled: #6366F1
```

---

## Screen 7: Quiz Question

```
╔═══════════════════════════════════╗
║ ← Section 1 Quiz      ⏱ 14:32    ║
║ (Timer countdown)                 ║
║ Question 3 of 5       ████░░░    ║
║ (Progress bar)                    ║
╠═══════════════════════════════════╣
║                                   ║
║ What is the output of this       ║
║ Python code?                     ║
║ (Question text: 16px)            ║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ x = 5                           │║
║ │ y = 10                          │║
║ │ print(x + y)                    │║
║ └────────────────────────────────┘║
║ (Code block: monospace, gray bg)  ║
║                                   ║
╠═══════════════════════════════════╣
║ ANSWER OPTIONS                    ║
║                                   ║
║ ◯ 5                              ║
║                                   ║
║ ◯ 10                             ║
║                                   ║
║ ◉ 15                             ║
║ (Selected - filled circle)        ║
║                                   ║
║ ◯ 510                            ║
║                                   ║
║ ◯ None of the above              ║
║                                   ║
╠═══════════════════════════════════╣
║                                   ║
║ [← Previous] [Next Question →]   ║
║                                   ║
║ (Only shows on Q5:                ║
║  [← Previous] [Submit Quiz])      ║
║                                   ║
║ 🏠 Home  🔍 Explore  📦 ...      ║
╚═══════════════════════════════════╝

Quiz Features:
• Timer shows remaining time
• Progress bar shows question progression
• Radio button options
• Previous/Next navigation
• Submit button on last question
• Can navigate back to review answers
• Timer stops on submit

Colors:
- Selected option: #6366F1 circle, #6366F1 radio dot
- Timer: #EF4444 when < 5 minutes remaining
- Progress: #6366F1 filled portion
```

---

## Screen 8: Quiz Results

```
╔═══════════════════════════════════╗
║                                   ║
║          🎉 Congrats! 🎉          ║
║          (Celebration)            ║
║                                   ║
║            YOU PASSED!            ║
║          (H1: 48px)               ║
║                                   ║
║              85/100               ║
║          (Large score: 48px)      ║
║              Grade: A             ║
║          (Green text: #10B981)    ║
║                                   ║
║         Completed in 12:34        ║
║          (Body small)             ║
║                                   ║
╠═══════════════════════════════════╣
║ PERFORMANCE BREAKDOWN              ║
║                                   ║
║ ✓ Correct:      17/20  (85%)     ║
║ ✗ Incorrect:     3/20  (15%)     ║
║ ⊘ Skipped:       0/20  (0%)      ║
║                                   ║
║ (Green/Red/Gray text indicators) ║
║                                   ║
╠═══════════════════════════════════╣
║ QUESTION REVIEW                   ║
║                                   ║
║ Q1: What is the output?          ║
║ Your answer: 15 ✓                ║
║ [View Explanation]               ║
║                                   ║
║ Q2: Which is correct?            ║
║ Your answer: Loop ✗              ║
║ Correct answer: Function         ║
║ [View Explanation]               ║
║                                   ║
║ Q3: Define variable              ║
║ Your answer: Skipped ⊘          ║
║ [View Explanation]               ║
║                                   ║
╠═══════════════════════════════════╣
║                                   ║
║       [Next Module →]             ║
║      (Primary button)             ║
║                                   ║
║       [Retake Quiz]               ║
║      (Secondary button)           ║
║                                   ║
║    [View Certificates]            ║
║      (Text link)                  ║
║                                   ║
║ 🏠 Home  🔍 Explore  📦 ...      ║
╚═══════════════════════════════════╝

Results Screen Features:
• Large score display for satisfaction
• Pass/Fail message with emoji celebration
• Performance breakdown with colors
• Question-by-question review
• Explanations available for wrong answers
• Clear next action (Next Module or Retake)

Colors:
- Passed: #10B981 (green)
- Failed: #EF4444 (red)
- Correct answer checkmark: #10B981
- Incorrect answer X: #EF4444
- Skipped: #9CA3AF (gray)
- Header: White background for celebration feel
```

---

## Screen 9: Certificates & Achievements

```
╔═══════════════════════════════════╗
║ Certificates              👤  ⓘ  ║
║ (Page header)                     ║
╠═══════════════════════════════════╣
║                                   ║
║ You've earned 3 certificates     ║
║ (Subheading with count)          ║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ CERTIFICATE (Thumbnail)         │║
║ │ ┌──────────────────────────┐   │║
║ │ │ 📜 Certificate            │   │║
║ │ │    EduFlow                │   │║
║ │ │ ✓ PYTHON FUNDAMENTALS     │   │║
║ │ │ Earned: June 15, 2026     │   │║
║ │ └──────────────────────────┘   │║
║ │                                 │║
║ │ Skills: Python, OOP, APIs       │║
║ │                                 │║
║ │ [View] [LinkedIn] [Download]   │║
║ └────────────────────────────────┘║
║                                   ║
║ ┌────────────────────────────────┐║
║ │ CERTIFICATE (Thumbnail)         │║
║ │ ┌──────────────────────────┐   │║
║ │ │ 📜 Certificate            │   │║
║ │ │    EduFlow                │   │║
║ │ │ ✓ WEB DEVELOPMENT         │   │║
║ │ │ Earned: May 20, 2026      │   │║
║ │ └──────────────────────────┘   │║
║ │                                 │║
║ │ Skills: HTML, CSS, JS           │║
║ │                                 │║
║ │ [View] [LinkedIn] [Download]   │║
║ └────────────────────────────────┘║
║                                   ║
╠═══════════════════════════════════╣
║ ACHIEVEMENTS UNLOCKED              ║
║                                   ║
║ 🎖️ 🎖️ 🎖️                        ║
║ First Step   Course Master  Quiz  ║
║ (1 course)   (3 courses)    Ace   ║
║                                   ║
║ 🎖️ 🎖️                            ║
║ Helpful Helper  Streak Master    ║
║ (5 answers)     (30-day streak)   ║
║                                   ║
╠═══════════════════════════════════╣
║ 🏠 Home  🔍 Explore  📦 ...      ║
╚═══════════════════════════════════╝

Certificate Features:
• Clickable certificates (modal view)
• LinkedIn share integration
• PDF download option
• Skills listed for employer credibility
• Achievement badges with descriptions
• Milestone celebrations

Colors:
- Certificate border: #6366F1 (indigo)
- Skills text: #4B5563 (secondary)
- Badge background: #FEF3C7 (amber light)
- Share button: #6366F1
```

---

## Component Library - Detailed Specs

### Button Component

```
PRIMARY BUTTON
┌──────────────────────────────────┐
│      [Enroll Now - $49.99]       │
│  (56px height, full width max)   │
└──────────────────────────────────┘

Properties:
• Height: 56px (large), 40px (medium), 32px (small)
• Width: 100% - 32px (mobile), auto (desktop)
• Padding: 12px 24px (large)
• Font: Inter Semibold 14px
• Border Radius: 8px
• Background: #6366F1
• Text: #FFFFFF
• Shadow: 0 2px 4px rgba(99, 102, 241, 0.15)

States:
- Default: #6366F1
- Hover: #4F46E5 (darker), shadow 0 4px 8px
- Active: #4F46E5 + shadow reduction
- Disabled: #E5E7EB bg, #9CA3AF text, no shadow

Interactions:
• Tap feedback (brief scale down)
• Hover color transition (200ms)
• Loading state (spinner inside button)
```

### Card Component

```
COURSE CARD
┌──────────────────────────────────┐
│ [Image 16:9, 160px] [BADGE]     │
│ Course Title                     │
│ Instructor Name                  │
│ ⭐⭐⭐⭐⭐ 4.8 (456)              │
│ $49.99 ← $99.99 (50% off)       │
│ [❤️] [Explore]                   │
└──────────────────────────────────┘

Properties:
• Background: #FFFFFF
• Border Radius: 12px
• Shadow: 0 4px 12px rgba(0, 0, 0, 0.08)
• Padding: 0 (image bleed) + 12px content
• Spacing between: 12px
• Max width: 100% - 16px margins

States:
- Default: Standard shadow
- Hover: Shadow 0 8px 20px rgba(0, 0, 0, 0.12)
- Active: Scale 1.02
- Disabled: Opacity 0.6, shadow removed

Inner Layout:
- Image: 100% width × 160px (16:9)
- Title: 14px bold #111827, 2 lines max
- Subtitle: 12px #4B5563
- Rating: 14px bold, stars
- Price: 14px bold #6366F1
- Buttons: 36px height each
```

### Input Field Component

```
TEXT INPUT - DEFAULT
┌────────────────────────────────────┐
│ Search courses...                  │
└────────────────────────────────────┘

Properties:
• Height: 48px
• Width: 100% - 16px margins
• Border: 1px #D1D5DB
• Border Radius: 8px
• Padding: 12px 16px
• Font: Inter 14px #111827
• Placeholder: 14px #9CA3AF
• Background: #FFFFFF

States:
- Default: #D1D5DB border
- Focus: #6366F1 border (2px), shadow 0 0 0 4px rgba(99, 102, 241, 0.1)
- Filled: Same as default
- Error: #EF4444 border (2px), shadow 0 0 0 4px rgba(239, 68, 68, 0.1)
- Disabled: #E5E7EB border, #F3F4F6 bg, #9CA3AF text

Animations:
• Border color transition: 200ms
• Focus shadow fade in: 150ms
```

### Progress Bar Component

```
PROGRESS BAR - 50% COMPLETE
┌────────────────────────────────────┐
│ ▓▓▓▓▓░░░░░░░░░░░░  50%           │
└────────────────────────────────────┘

Properties:
• Height: 8px
• Width: 100% - 16px margins
• Border Radius: 4px
• Background (track): #E5E7EB
• Fill (progress): #6366F1
• Animation: Smooth width increase (300ms ease)

Variants:
- Success state: #10B981 (green)
- Warning state: #F59E0B (amber)
- Error state: #EF4444 (red)
- Indeterminate: Animated sliding pattern

Text:
• Percentage displayed (optional)
• Position: Right-aligned, 12px bold
• Color: #4B5563
```

---

## Design System Export

### CSS Variables

```css
:root {
  /* Primary Colors */
  --color-primary: #6366F1;
  --color-primary-light: #818CF8;
  --color-primary-dark: #4F46E5;
  
  /* Semantic Colors */
  --color-success: #10B981;
  --color-warning: #F59E0B;
  --color-danger: #EF4444;
  --color-info: #3B82F6;
  
  /* Neutral Colors */
  --color-white: #FFFFFF;
  --color-gray-50: #F9FAFB;
  --color-gray-100: #F3F4F6;
  --color-gray-200: #E5E7EB;
  --color-gray-300: #D1D5DB;
  --color-gray-400: #9CA3AF;
  --color-gray-500: #6B7280;
  --color-gray-600: #4B5563;
  --color-gray-700: #374151;
  --color-gray-900: #111827;
  
  /* Typography */
  --font-display: 'Poppins', sans-serif;
  --font-body: 'Inter', sans-serif;
  --font-mono: 'Fira Code', monospace;
  
  /* Sizing */
  --spacing-xs: 4px;
  --spacing-sm: 8px;
  --spacing-md: 16px;
  --spacing-lg: 24px;
  --spacing-xl: 32px;
  
  /* Border Radius */
  --radius-sm: 4px;
  --radius-md: 8px;
  --radius-lg: 12px;
  --radius-full: 50%;
  
  /* Shadows */
  --shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.05);
  --shadow-md: 0 4px 12px rgba(0, 0, 0, 0.08);
  --shadow-lg: 0 8px 20px rgba(0, 0, 0, 0.12);
}
```

---

## Prototype Interactions & Animations

### Navigation Flows

```
Tab Navigation (Bottom):
🏠 Home
   ↓ (tap) → Dashboard screen
🔍 Explore (Courses)
   ↓ (tap) → Discovery screen
📦 Downloads
   ↓ (tap) → Downloaded courses
❤️ Wishlist
   ↓ (tap) → Saved courses
👤 Profile
   ↓ (tap) → User profile

Card Navigation:
Course card (tap anywhere)
   ↓ → Course details screen

Continue Learning card (tap):
   ↓ → Video player screen

Next button (quiz/lesson):
   ↓ → Next question/lesson
```

### Transition Animations

```
Screen to Screen:
Type: Fade + slight slide-up (50px)
Duration: 300ms
Easing: ease-in-out cubic-bezier(0.4, 0, 0.2, 1)

Modal Open/Close:
Open: Fade in (150ms) + scale (0.95 → 1.0)
Close: Fade out (100ms) + scale (1.0 → 0.95)

Button Interactions:
Tap: Scale to 0.98 (50ms) → back to 1.0
Hover: Background color transition (200ms)

Progress Bar:
Width animation (300ms ease)
Color transitions (200ms ease)

Quiz Timer:
Countdown smooth number animation
Color change at < 5 minutes (smooth)
```

---

## Figma Prototype Setup

### Component Instances

```
Main Components Created:
• Button (variant: type, size, state)
• Card (variant: course, lesson)
• Input (variant: default, focus, error)
• Checkbox (variant: checked, unchecked, disabled)
• Radio Button (variant: selected, unselected)
• Progress Bar (variant: primary, success, warning)
• Badge (variant: new, bestseller, free)
• Avatar (variant: sizes 24, 32, 40, 64px)
• Rating (variant: 1-5 stars)
• Icon (SVG set from Material Design)

Frames:
• Screen 1: Onboarding (375×812px)
• Screen 2: Learning Goals (375×812px)
• Screen 3: Home Dashboard (375×812px)
• Screen 4: Course Discovery (375×812px)
• Screen 5: Course Details (375×812px)
• Screen 6: Video Lesson (375×812px)
• Screen 7: Quiz Question (375×812px)
• Screen 8: Quiz Results (375×812px)
• Screen 9: Certificates (375×812px)

Total: 9 main screens + 15+ component states = 25+ viewable frames
```

### Prototype Sharing

```
Figma Link Format:
https://www.figma.com/proto/[FILE_ID]/EduFlow-Prototype
?node-id=[FRAME_ID]&scaling=scale-down

Sharing Settings:
✓ View-only access (no edit)
✓ Comment access (feedback)
✓ Prototype mode (interactive flows)
✓ Password protected (if needed)

Access Levels:
- Stakeholders: View-only + comments
- Developers: Full specs + component details
- Designers: Edit access for iterations
- QA Team: Comment + prototype interaction
```

---

## Implementation Handoff Checklist

```
Design Assets:
✓ All 9 screens exported as PNG (100% scale)
✓ Component library in Figma (editable)
✓ Design system guide (PDF)
✓ Color palette (CSS, JSON, Figma styles)
✓ Typography specs (CSS)
✓ Icon set (SVG, 24×24px to 64×64px)
✓ Animation timings (documented)

Developer Resources:
✓ Figma prototype link (interactive)
✓ Component specifications (dimensions, spacing)
✓ CSS variables file
✓ Responsive breakpoints documented
✓ Interaction triggers documented
✓ Form validation rules specified
✓ Error states documented
✓ Loading states documented

QA/Testing:
✓ User flow documentation
✓ Test cases for each screen
✓ Accessibility audit (WCAG AA)
✓ Performance targets (page load, animations)
✓ Browser compatibility matrix
✓ Device testing matrix
✓ Accessibility testing checklist
```

---

**Visual Mockups Complete**  
**Status:** Ready for Developer Implementation  
**Files:** All screens and components documented  

