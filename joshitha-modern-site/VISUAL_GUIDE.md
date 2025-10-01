# 🎨 Visual Design Guide - JOSHITHA Group Landing Page

## 📐 Page Layout Overview

```
┌─────────────────────────────────────────────────────────────┐
│                      NAVIGATION BAR                          │
│  [Logo] JOSHITHA    Home  About  Services  ...  [Get Touch] │
│                    (Glass morphism effect)                   │
└─────────────────────────────────────────────────────────────┘
│
│  ┌───────────────────────────────────────────────────────┐
│  │                   HERO SECTION                        │
│  │  ┌─────────────────────┐  ┌──────────────────────┐  │
│  │  │  Building           │  │   3D City Skyline    │  │
│  │  │  Tomorrow's         │  │   (Three.js)         │  │
│  │  │  Infrastructure     │  │   [Rotating]         │  │
│  │  │                     │  │   [Animated]         │  │
│  │  │  [Explore Projects] │  │                      │  │
│  │  │  [Contact Us]       │  │   Floating Cards:    │  │
│  │  └─────────────────────┘  │   • 500+ Projects    │  │
│  │                            │   • Class-I          │  │
│  │                            │   • Grade-A          │  │
│  │                            └──────────────────────┘  │
│  └───────────────────────────────────────────────────────┘
│
│  ┌───────────────────────────────────────────────────────┐
│  │                   ABOUT SECTION                       │
│  │  ┌──────────────────┐  ┌──────────────────────────┐  │
│  │  │ Company Profile  │  │  Highlight Cards:        │  │
│  │  │ • Established    │  │  ┌────┐ ┌────┐          │  │
│  │  │   2010           │  │  │ 🏆 │ │ 👥 │          │  │
│  │  │ • Class-I        │  │  └────┘ └────┘          │  │
│  │  │   Contractor     │  │  ┌────┐ ┌────┐          │  │
│  │  │ • Grade-A        │  │  │ 🎯 │ │ 📈 │          │  │
│  │  │   Electrical     │  │  └────┘ └────┘          │  │
│  │  └──────────────────┘  └──────────────────────────┘  │
│  │                                                       │
│  │  ┌─────────────────────────────────────────────────┐ │
│  │  │  Director Profile: Mr. Manohar Budarapu        │ │
│  │  │  [MB] 32+ years experience                     │ │
│  │  └─────────────────────────────────────────────────┘ │
│  └───────────────────────────────────────────────────────┘
│
│  ┌───────────────────────────────────────────────────────┐
│  │                 STATISTICS SECTION                    │
│  │  ┌──────┐  ┌──────┐  ┌──────┐  ┌──────┐            │
│  │  │ 500+ │  │2900+ │  │1000+ │  │ 15+  │            │
│  │  │Projects│ │Crores│ │ Team │  │Years │            │
│  │  └──────┘  └──────┘  └──────┘  └──────┘            │
│  │  (Animated counters with gradient backgrounds)      │
│  └───────────────────────────────────────────────────────┘
│
│  ┌───────────────────────────────────────────────────────┐
│  │              BUSINESS SECTORS SECTION                 │
│  │  ┌────────┐  ┌────────┐  ┌────────┐                 │
│  │  │   🏗️   │  │   🏭   │  │   🏢   │                 │
│  │  │Infra-  │  │Indus-  │  │Institu-│                 │
│  │  │structure│  │trial   │  │tional  │                 │
│  │  └────────┘  └────────┘  └────────┘                 │
│  │  ┌────────┐  ┌────────┐  ┌────────┐                 │
│  │  │   🏠   │  │   ⚡   │  │   💼   │                 │
│  │  │Residen-│  │ Power  │  │Project │                 │
│  │  │tial    │  │Projects│  │Mgmt    │                 │
│  │  └────────┘  └────────┘  └────────┘                 │
│  │  (Interactive hover effects, glassmorphism)          │
│  └───────────────────────────────────────────────────────┘
│
│  ┌───────────────────────────────────────────────────────┐
│  │                 PROJECTS SECTION                      │
│  │  [Completed Projects] [Ongoing Projects]              │
│  │  ┌──────────────────┐  ┌──────────────────┐          │
│  │  │ HPCL Bangalore   │  │ Metro Rail       │          │
│  │  │ 📍 Karnataka     │  │ 📍 Hyderabad     │          │
│  │  │ 💰 ₹45 Crores   │  │ 💰 ₹250 Crores  │          │
│  │  │ ✅ Completed    │  │ ▓▓▓▓▓░░░ 65%    │          │
│  │  └──────────────────┘  └──────────────────┘          │
│  │  ┌──────────────────┐  ┌──────────────────┐          │
│  │  │ NTPC Korba       │  │ Smart City       │          │
│  │  │ 📍 Chhattisgarh  │  │ 📍 Visakhapatnam │          │
│  │  │ 💰 ₹120 Crores  │  │ 💰 ₹180 Crores  │          │
│  │  │ ✅ Completed    │  │ ▓▓▓▓░░░░ 45%    │          │
│  │  └──────────────────┘  └──────────────────┘          │
│  └───────────────────────────────────────────────────────┘
│
│  ┌───────────────────────────────────────────────────────┐
│  │                 CONTACT SECTION                       │
│  │  ┌──────────────────┐  ┌──────────────────────────┐  │
│  │  │ Contact Info:    │  │  Contact Form:           │  │
│  │  │ • Head Office    │  │  [Name]                  │  │
│  │  │ • Phone          │  │  [Email]                 │  │
│  │  │ • Email          │  │  [Phone]                 │  │
│  │  │ • Locations      │  │  [Subject]               │  │
│  │  │                  │  │  [Message]               │  │
│  │  │ [Map Preview]    │  │  [Send Message]          │  │
│  │  └──────────────────┘  └──────────────────────────┘  │
│  └───────────────────────────────────────────────────────┘
│
│  ┌───────────────────────────────────────────────────────┐
│  │                      FOOTER                           │
│  │  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌─────────┐ │
│  │  │ Company  │ │  Quick   │ │ Services │ │ Contact │ │
│  │  │   Info   │ │  Links   │ │          │ │  Info   │ │
│  │  │          │ │          │ │          │ │         │ │
│  │  │ [Social] │ │          │ │          │ │         │ │
│  │  └──────────┘ └──────────┘ └──────────┘ └─────────┘ │
│  │  ─────────────────────────────────────────────────── │
│  │  © 2025 JOSHITHA Infratech | Privacy | Terms         │
│  └───────────────────────────────────────────────────────┘
```

---

## 🎨 Color Palette

### Primary Colors
```
┌─────────────────────────────────────────┐
│ Primary Pink:    #f43f75  ████████████  │
│ Primary Dark:    #e11d5f  ████████████  │
│ Primary Darker:  #c31250  ████████████  │
│ Primary Darkest: #a11246  ████████████  │
└─────────────────────────────────────────┘
```

### Background Colors
```
┌─────────────────────────────────────────┐
│ Dark 900:  #0a0a0a  ████████████████    │
│ Dark 800:  #121212  ████████████████    │
│ Dark 700:  #1a1a1a  ████████████████    │
│ Dark 600:  #2a2a2a  ████████████████    │
└─────────────────────────────────────────┘
```

### Accent Colors
```
┌─────────────────────────────────────────┐
│ Blue (Tech):     #4fc3f7  ████████████  │
│ Green (Success): #4caf50  ████████████  │
│ Orange (Accent): #ff9800  ████████████  │
└─────────────────────────────────────────┘
```

---

## 🔤 Typography

### Font Families
```
Headings:  Montserrat (Bold, 700-900)
Body Text: Inter (Regular, 400-600)
```

### Font Sizes
```
Hero Title:     text-7xl (72px)
Section Title:  text-5xl (48px)
Card Title:     text-2xl (24px)
Body Text:      text-base (16px)
Small Text:     text-sm (14px)
```

---

## 🎭 Design Elements

### Glassmorphism Effect
```css
background: rgba(255, 255, 255, 0.05)
backdrop-filter: blur(12px)
border: 1px solid rgba(255, 255, 255, 0.1)
```

### Shadow System
```
Small:  shadow-lg
Medium: shadow-xl
Large:  shadow-2xl
Glow:   shadow-primary-500/30
```

### Border Radius
```
Small:  rounded-lg (8px)
Medium: rounded-xl (12px)
Large:  rounded-2xl (16px)
Full:   rounded-full
```

---

## 🎬 Animation Types

### 1. Entrance Animations
- **Fade In**: Opacity 0 → 1
- **Slide Up**: translateY(100px) → 0
- **Scale**: scale(0.8) → 1

### 2. Hover Animations
- **Lift**: translateY(0) → -10px
- **Scale**: scale(1) → 1.05
- **Glow**: shadow intensity increase

### 3. Continuous Animations
- **Float**: Vertical oscillation
- **Rotate**: 360° rotation
- **Pulse**: Scale pulsing

### 4. Scroll Animations
- **Parallax**: Different scroll speeds
- **Reveal**: Fade in on scroll
- **Counter**: Number counting up

---

## 📱 Responsive Breakpoints

### Desktop (>1024px)
```
┌─────────────────────────────────────┐
│  [Nav]                              │
│  ┌──────────┐  ┌──────────────────┐│
│  │  Text    │  │   3D Scene       ││
│  │  Content │  │   (Full)         ││
│  └──────────┘  └──────────────────┘│
│  [3 Column Grid]                    │
└─────────────────────────────────────┘
```

### Tablet (640-1024px)
```
┌──────────────────────────┐
│  [Nav with Menu]         │
│  ┌────────────────────┐  │
│  │  Text Content      │  │
│  │  (Centered)        │  │
│  └────────────────────┘  │
│  [2 Column Grid]         │
└──────────────────────────┘
```

### Mobile (<640px)
```
┌─────────────────┐
│ [☰ Menu]        │
│ ┌─────────────┐ │
│ │   Content   │ │
│ │  (Stacked)  │ │
│ └─────────────┘ │
│ [1 Column]      │
└─────────────────┘
```

---

## 🎯 Interactive Elements

### Buttons
```
Primary:   Gradient background, glow shadow
Secondary: Glass effect, border
Hover:     Scale 1.05, lift -2px
Active:    Scale 0.95
```

### Cards
```
Default:   Glass background, subtle border
Hover:     Lift -5px, scale 1.02
Active:    Highlight border
```

### Navigation
```
Desktop:   Horizontal menu
Mobile:    Hamburger → Slide-in menu
Scroll:    Glass background appears
```

---

## 🌟 Special Effects

### 3D City Skyline
```
Elements:
- 7 Buildings (varying heights)
- Animated windows (random glow)
- Floating particles (100+)
- Auto-rotating camera
- Dynamic lighting
```

### Floating Cards
```
Animation:
- Vertical movement: ±20px
- Duration: 4-5 seconds
- Easing: ease-in-out
- Infinite loop
```

### Counter Animation
```
Behavior:
- Start: 0
- End: Target value
- Duration: 2 seconds
- Easing: Linear
- Trigger: On scroll into view
```

---

## 📐 Spacing System

```
Padding:
- Small:  p-4  (16px)
- Medium: p-6  (24px)
- Large:  p-8  (32px)
- XLarge: p-12 (48px)

Margin:
- Small:  m-4  (16px)
- Medium: m-6  (24px)
- Large:  m-8  (32px)
- XLarge: m-12 (48px)

Gap:
- Small:  gap-4  (16px)
- Medium: gap-6  (24px)
- Large:  gap-8  (32px)
```

---

## 🎨 Component Styles

### Glass Card
```
Background: bg-white/5
Blur:       backdrop-blur-md
Border:     border-white/10
Padding:    p-8
Radius:     rounded-2xl
```

### Gradient Button
```
Background: bg-gradient-to-r from-primary-500 to-primary-600
Shadow:     shadow-lg shadow-primary-500/30
Hover:      shadow-primary-500/50, scale-105
Text:       text-white font-medium
```

### Stat Card
```
Background: glass
Icon:       Gradient background
Number:     text-4xl font-bold
Label:      text-sm text-gray-400
Hover:      scale-105, lift -10px
```

---

**This visual guide helps understand the layout and design system of the landing page.**

