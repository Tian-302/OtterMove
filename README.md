# 🦦 OtterMove — Move a Little, Feel a Lot.

**OtterMove（獭动一下）** is an iOS wellness application designed to help university students take small, meaningful steps toward healthier daily routines.

Through short movement sessions, guided breathing, mood check-ins, and a customizable otter room, OtterMove combines gentle self-care with playful motivation.

> **Move a Little, Feel a Lot.**  
> Small actions. Gentle progress. A happier otter.

**Current Version:** v0.8  
**Platform:** iOS 16.0+  
**Technology:** Swift · SwiftUI · Xcode  
**Project Status:** Prototype

---

## 🌱 Why OtterMove?

University students often spend long hours studying, working on assignments, or sitting in libraries and dormitories.

Even when they recognize the importance of taking breaks, getting started can feel difficult. Traditional fitness applications may demand too much time, energy, or commitment.

OtterMove takes a different approach.

Instead of pushing users toward intense exercise or strict performance goals, it encourages small, manageable actions that fit naturally into everyday student life.

Our design focuses on three principles:

- **Low barriers:** Make it easy to begin, even when energy is limited.
- **Gentle encouragement:** Support users without pressure, guilt, or punishment.
- **Meaningful feedback:** Turn small moments of self-care into visible progress.

---

## ✨ Key Features

### 🏠 1. Cozy Otter Room

A warm, isometric-style room provides a relaxing space for personalization and creative expression.

**Features include:**

- Cream-colored interior with wooden window frames and a peaceful garden view.
- Soft curtains, natural daylight, and cozy decorative details.
- Placeable furniture and decorations, including curtains, paintings, clocks, and books.
- Flexible book placement on wall shelves, desks, and low cabinets.
- Furniture color customization.
- Up to three independent rooms, each preserving its own layout and furniture colors.
- Persistent room arrangements saved when users tap **Done（完成）**.

The room is designed to create a welcoming environment that users can return to throughout the day.

### 🏃 2. Short Movement Sessions

OtterMove offers simple movement activities designed around common student environments and energy levels.

**Available activity modes:**

- **Library · Low Energy（图书馆 · 低电量）**
- **Dormitory · More Energy（宿舍 · 有余力）**

Each mode provides three illustrated movement cards.

Users can:

- Swipe horizontally or tap cards to switch exercises.
- View exercise titles, durations, and instructions.
- Follow visual guidance with arrows, footprints, and movement indicators.
- Start a timer for unlocked exercises.
- Pause and resume an ongoing activity.
- Unlock the next exercise after completing the current one.

The movement illustrations emphasize key postures and accessible movement ranges.

### 😊 3. Daily Mood Check-In

OtterMove encourages users to recognize and express how they feel.

The home screen features six mood cards, each illustrated with a distinct otter expression.

**Features include:**

- Six selectable mood expressions.
- One-tap mood selection and saving.
- A full-body otter displayed on the home screen that reflects the selected mood.
- Separate visual assets for mood cards and the central otter character.

This feature creates a simple, approachable way to acknowledge daily emotions.

### 🧘 4. Guided Breathing & Meditation

The meditation experience combines a structured breathing rhythm with optional background audio.

**Breathing cycle:**

| Phase | Duration |
|---|---|
| Inhale | 4 seconds |
| Hold | 2 seconds |
| Exhale | 6 seconds |

The current breathing phase and countdown appear above the otter character.

**Audio options:**

- Gentle Piano
- Relaxing Ambient
- Natural Water Sounds
- No Music

Users can adjust the volume, switch tracks, and pause or resume meditation.

Audio preferences are saved between sessions. Changing the background track does not restart the breathing session.

### 🌅 5. Dynamic Lakeside Scenery

The lakeside environment changes according to Beijing Time (UTC+8), creating a calm visual atmosphere throughout the day.

| Time (UTC+8) | Environment |
|---|---|
| 06:00–17:00 | Daytime |
| 17:00–19:00 | Sunset |
| 19:00–06:00 | Nighttime |

All three scenes maintain a consistent otter position and lakeside composition.

Water and reflection animations update while the application is active and pause when it enters the background.

---

## 📱 Application Navigation

OtterMove includes five main sections:

| Section | Purpose |
|---|---|
| **Home** | View the otter companion and record daily moods |
| **Movement** | Explore and complete short movement activities |
| **Meditation** | Practice guided breathing with optional background music |
| **Check-In** | Access the daily check-in experience |
| **Room** | Customize and save cozy otter living spaces |

---

## 🚀 Getting Started

### Requirements

- A Mac capable of running a compatible version of Xcode
- Xcode with an iOS 16.0+ simulator runtime
- The OtterMove project files

### Installation

**1. Download or clone the repository.**

```bash
git clone https://github.com/Tian-302/OtterMove.git
cd OtterMove
```

If you received the project as a ZIP archive, extract it on your Mac instead.

**2. Open the Xcode project.**

Open:

```text
OtterMove.xcodeproj
```

Or run:

```bash
open OtterMove.xcodeproj
```

**3. Select the application target and simulator.**

In Xcode, choose:

```text
OtterMove → iPhone Simulator
```

**4. Build and run.**

Press:

```text
⌘ + R
```

Xcode will build and launch the application in the selected simulator.

### Data Persistence

When using the same simulator and application identifier, previously saved application data may remain available.

This includes existing records and room arrangements, provided the application's data has not been removed.

---

## 🧪 How to Test v1.0

We recommend testing the following user journeys.

### Room Customization

1. Open the **Room** section.
2. Select a room and arrange furniture.
3. Add decorative elements such as curtains, paintings, clocks, and books.
4. Place books on compatible furniture.
5. Customize furniture colors.
6. Tap **Done（完成）** to save.
7. Switch between rooms and verify that each arrangement is preserved.

### Movement Experience

1. Open **Movement**.
2. Select Library or Dormitory mode.
3. Switch between the three exercise cards.
4. Confirm that the title, duration, and instructions update.
5. Start an unlocked exercise.
6. Pause and resume the timer.
7. Complete the exercise and verify that the next activity unlocks.

### Mood Check-In

1. Open **Home**.
2. Select one of the six mood cards.
3. Confirm that the selected mood is saved.
4. Verify that the central full-body otter updates accordingly.

### Meditation Experience

1. Open **Meditation**.
2. Open the audio settings using the slider icon.
3. Select a background track and adjust the volume.
4. Start a breathing session.
5. Follow the 4–2–6 breathing cycle.
6. Pause, resume, and change the music.
7. Verify that audio preferences are retained.

### Dynamic Lake Scene

1. Open the lakeside scene.
2. Verify that the correct environment is selected according to Beijing Time.
3. Confirm that the otter position remains consistent across scenes.
4. Check that water animations pause when the app enters the background.

---

## 🎨 Included Assets

All required visual and audio assets are bundled with the project.

### Audio Assets

| File | Description |
|---|---|
| `MeditationPiano.m4a` | Gentle piano soundtrack, approximately 36-second loop |
| `MeditationAmbient.m4a` | Relaxing ambient soundtrack, approximately 48-second loop |
| `MeditationWater.m4a` | Natural water soundtrack, approximately 40-second loop |

The bundled audio files are playable stereo M4A tracks, including music created for this project.

To replace an audio file, use the same filename in Xcode and ensure:

**Target Membership → OtterMove**

is enabled.

### Visual Assets

| Asset | Description |
|---|---|
| `Assets.xcassets/otter7_mood_*.imageset` | Six cropped mood illustrations |
| `Assets.xcassets/otter8_*.imageset` | Garden scenery, plants, woven rug, and full-body otter |
| `Assets.xcassets/otter6_*.imageset` | Armchair and otter paw illustrations |
| `otter5_lake_day` | Daytime lakeside environment |
| `otter5_lake_dusk` | Sunset lakeside environment |
| `otter4_lake` | Nighttime lakeside environment |

The three lakeside images have a resolution of **863 × 1823 pixels** and are configured in the Xcode Asset Catalog.

### Asset Compatibility

Version 1.0 includes compatibility handling for selected older decorations:

- Previous small green plants are converted to wall clocks.
- Previous small rugs are converted to books.

This helps preserve existing room data when updating from an earlier prototype.

---

## 🛠️ Technology Stack

| Technology | Usage |
|---|---|
| **Swift** | Application development |
| **SwiftUI** | Native iOS interface and interactions |
| **Xcode** | Development, building, and simulator testing |
| **Asset Catalog** | Management of images and visual resources |
| **M4A Audio** | Meditation background soundtracks |
| **Git & GitHub** | Version control and collaboration |

---

## 🔍 Verification & Testing

The v1.0 project package has undergone source-level checks covering:

- Swift source syntax
- Xcode project references
- Bundled resource configuration

Full iOS compilation and simulator interaction should be verified on a Mac using Xcode.

### Run Project Checks

From the project root directory:

```bash
bash Tests/run_checks.sh
```

### Run in Xcode

Open `OtterMove.xcodeproj`, select an iPhone simulator, and press **⌘R**.

**Note:** Source-level checks do not replace a successful Xcode build or end-to-end simulator testing.

---

## 👥 Team Responsibilities

| Role | Responsibilities |
|---|---|
| **Project Lead & Product Designer** | User research, requirements, user journey, planning, and coordination |
| **iOS Developer** | SwiftUI interfaces, navigation, and user interactions |
| **Core Logic Developer** | Activity logic, state management, progression, and persistence |
| **UI/UX & Visual Designer** | Otter character, visual assets, interface design, and project poster |
| **QA & Presentation Lead** | Testing, documentation, demo preparation, and presentation |

---

## 🎯 Our Vision

OtterMove is built around a simple idea:

**Taking care of yourself should feel approachable, not overwhelming.**

We want to help students make room for small moments of movement, breathing, and emotional awareness without turning self-care into another demanding task.

OtterMove is currently a prototype, and its features and experience will continue to evolve through testing and feedback.

---

### 🦦 Move a Little, Feel a Lot.

*Small steps matter.*
